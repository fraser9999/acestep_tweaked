

# ConfyUI Workflow for ACE-Step Audio Plugin 🎵

This repository contains a **workflow.json** file for **ConfyUI**, specifically designed for the **ACE-Step plugin**.
With this workflow, you can **enhance the quality of music generation** and efficiently process the resulting audio files.

---

## 🔹 What is ACE-Step?

ACE-Step is a local audio plugin that allows you to **create your own songs on your computer** – similar to Udio, Suno, or Riffusion.
It generates music directly on your system, **completely free** and without any cloud dependency.

---

## 🔹 Workflow Features

The workflow offers:

1. **Audio Quality Enhancement**

   * Optimized render quality
   * Improved DSP audio enhancement options

2. **Stem Splitting**

   * Extract individual instruments or vocals as separate tracks
   * Perfect for further editing in DAWs like FL Studio

3. **Flexible Versions**

   * Multiple versions for different render qualities and audio enhancement levels
   * Original version vs. Tweaked version (higher audio quality)

---

## 🔹 Use Cases

* **Tweaked Version:** Use this version if you want the **best possible audio quality** from ACE-Step.
* **Stem Splitting:** Split songs into individual stems and process them further with:

  * **RVC Voice Changer** for vocals
  * **FL Studio** plugins like SoundGoodizer or Voice Doubling

---

## 🔹 Installation

1. Download the `workflow.json`.
2. Open **ConfyUI** and import the workflow.
3. Choose the desired version (Original or Tweaked) and adjust audio settings.
4. Generate your song and optionally use stem splitting for advanced editing.

---

## 🔹 Notes

* ACE-Step works **locally** – no cloud required.
* Audio quality depends on the chosen workflow version and audio settings.
* Experiment with DSP and stem splitting to achieve creative results.

---


## 🔹 Optional Extras: `nodes_audio.py`

This repository also includes a **patched version of `nodes_audio.py`**.

* **Purpose:** Enables ConfyUI to save audio files directly as **WAV** format.
* **Installation:**

  1. **Backup** the original `audio_nodes.py` file.
  2. Copy the patched version into the **`confyui_extras`** directory.
* Once installed, ConfyUI will be able to export audio outputs in WAV format, making further editing and processing easier.

---


## 🔹 License

This workflow is **free to use** for personal projects.


