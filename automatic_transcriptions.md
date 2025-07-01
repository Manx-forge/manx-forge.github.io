---
layout: default
title: Automatic Transcriptions
permalink: /automatic_transcriptions/
---
<h2 style="text-align: center;">Automatic Transcriptions</h2>

This repository serves as a central index for **automatically transcribed resources in Manx**, with a particular focus on transparency, traceability, and reproducibility. It is designed to bring together a wide range of transcriptions from diverse sources, while clearly distinguishing between **real** and **synthetic** data.

None of the original audio files will be uploaded here due to **file size constraints** and the potential for **copyright infringement or restrictive licensing conditions**. Where the original recordings are publicly available, a link to the source will be provided alongside the transcriptions, usually in a metadata.tsv file.

## Purpose

The goal of this repository is to:
- Provide **open access** to automatically generated Manx transcriptions
- Track the **origin and method** of each transcription (e.g., model used, data type)
- Facilitate the **reuse** of these transcriptions for downstream NLP tasks
- Make a clear distinction between **real-world audio** and **synthetic inputs**, enabling responsible and informed research use

## Model

All automatic transcriptions in this repository were generated using a **DNN-HMM hybrid model** trained on the [Loayr dataset](https://github.com/Manx-forge/loayr) — a curated speech corpus of Manx containing diverse and domain-rich content. The hybrid model was developed using the Kaldi toolkit and fine-tuned specifically for Manx.

## Repository Structure

The repository will be organized by:
- **Source domain** (e.g. podcasts, educational audio, folklore)
- **Corpus** (e.g. Manx Radio Broadcasts)
- **Transcription format** (e.g. `.txt`, `.srt`)

Each corpus will include:
- Metadata indicating the original audio source
- Details about the transcription process
- Relevant statistics

## Why include synthetic data?

Synthetic data can be useful for several tasks:

- 🗣 **Text-to-Speech (TTS) training**: Paired synthetic audio and text can augment low-resource datasets.
- 📝 **Automatic subtitling**: Transcripts aligned to speech can help subtitle previously uncaptioned Manx content.
- 🔄 **Data augmentation**: For bootstrapping more robust ASR models through multi-condition training.

📣 Contributions of new automatically transcribed resources — real or synthetic — are welcome. Please open an issue or pull request with your additions.
