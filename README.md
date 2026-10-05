# Turbo Transcriber

A free Windows transcription app for students. Whisper runs on your own PC; no paid API key is required.

## Download and install

1. Open [Releases](https://github.com/mavtrevor/turbo-transcriber/releases).
2. Under Assets, download **Turbo-Transcriber-Windows-x64.zip** (about 587 MB).
3. Right-click the ZIP and choose **Extract All**.
4. Open the extracted folder and double-click **Install.cmd**.
5. Open **Turbo Transcriber** from your desktop or Start menu.

The app opens in your browser at http://localhost:3000. Allow a little time for Whisper to load. Use **Stop Turbo Transcriber** when finished; closing the browser does not stop the service.

## Requirements

- 64-bit Windows 10 or 11, with an Intel/AMD CPU supporting AVX.
- 8 GB RAM or more recommended.
- 4 GB free disk space during installation.

The complete package includes Node, Python, Whisper, the small model, decoding dependencies, settings, and the Microsoft C++ runtime installer. If the Microsoft runtime is missing, Windows may request administrator permission to install it. No model download or API key is needed after installation.

## Features

- Audio and video transcription, plus translation into English.
- Batch uploads with separate progress for each file; files process sequentially.
- Editable transcripts, manual speaker labels, and recording playback.
- TXT, SRT, VTT, CSV, JSON, and browser PDF exports, with timestamp options.

Transcripts and recordings are stored in your browser on your PC. Export important work before clearing browser data. Review transcripts against the recording, especially names and important quotes.

This repository provides the student download package. Third-party license notices are included in the ZIP.
