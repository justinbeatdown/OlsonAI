# OlsonAI

**Your PC. Your Files. Your AI.**

OlsonAI is a local-first Windows desktop AI assistant built to make everyday computer work faster, safer, and easier. It combines conversational AI with practical file tools, creation utilities, organization workflows, local search, cleanup tools, and desktop integration while keeping the user in control of file-changing actions.

> **Current public beta:** OlsonAI **1.0 Beta 9** (`1.0.0-beta.9`)

## What’s new in Beta 9

Beta 9 is a major usability and Create Suite update focused on smoother Windows behavior, better file workflows, and clearer guidance.

- **Create Suite File Converter** — batch-convert common image, audio, video, data, and text formats locally.
- **Audio → MIDI Transcription** — transcribe detected musical notes from MP3, WAV, FLAC, OGG, and M4A audio into usable MIDI with local Spotify Basic Pitch support.
- **What’s New screen** — after an update, OlsonAI explains what changed, where to find it, and how to use it on first launch.
- **Home Command Center** — recent activity, quick actions, local component status, and safe Undo for supported operations.
- **Smoother Windows minimize/restore** — rebuilt taskbar and system-tray transitions to reduce flicker, lag, and awkward restore behavior.
- **Drag & drop** — route compatible files and folders directly into supported OlsonAI tools.
- **Optional “Send to OlsonAI” Explorer integration** — bring files and folders into OlsonAI from the Windows right-click workflow.
- **Component readiness checks** — clearer status for Ollama, FFmpeg, Basic Pitch, Pillow, and local-model requirements.
- **Privacy-conscious diagnostics** — tester reports avoid chat contents, prompts, file contents, filenames, and personal workspace paths.
- **Workflow polish** — clearer review/approval flows, empty states, keyboard shortcuts, friendly errors, and improved task feedback.

## Core features

### Ask OlsonAI

A conversational desktop assistant designed for natural everyday interaction. OlsonAI can help answer questions, work with local context, assist with files, and route actions into its built-in tools.

### Create Suite

Create and work with useful file types from one place, including TXT, Markdown, DOCX, PDF, CSV, XLSX, HTML, Python, PowerShell, Batch, JSON, and PNG output.

Beta 9 also adds:

- **Convert Files** for batch format conversion.
- **Audio → MIDI** for local music transcription.

### Smart Organize

Analyze a folder, review OlsonAI’s proposed organization plan, approve it, and then apply the changes. File-changing actions remain review-gated before execution.

### Smart Rename

Generate and review clearer filenames before OlsonAI makes changes. Supported operations can appear in Recent Activity with safe Undo when possible.

### Smart Search

Search local files with progress reporting and cancellation support.

### Duplicate Finder

Find exact duplicate files using SHA-256 comparison. OlsonAI protects a keeper copy and lets the user review duplicate copies before sending approved items to the Windows Recycle Bin.

### Smart Cleanup

Scan selected folders or broader PC locations for supported cleanup candidates. Cleanup stays review-driven and uses the Windows Recycle Bin rather than silently deleting files permanently.

### Ask My Files

Use OlsonAI to work with supported local documents and file content without turning basic file workflows into a cloud-first experience.

### Image Analyzer

Inspect and work with local images from inside OlsonAI.

### Clipboard AI

Bring clipboard content into OlsonAI for quick assistance.

### Game Mode

OlsonAI includes stateful games such as Hangman, Trivia, Rock Paper Scissors, Tic-Tac-Toe, Number Guessing, Riddles, Would You Rather, Word Association, 20 Questions, and Guess Who / Guess What.

## Local-first by design

OlsonAI is designed around local desktop workflows.

- Local file tools do not upload source files simply to perform routine file operations.
- File-changing actions use explicit review/approval flows.
- Large optional local components are not silently downloaded.
- Local AI can run through Ollama-supported models.
- Diagnostic reports are intentionally sanitized and exclude chat contents, prompts, file contents, filenames, and personal workspace paths.

Some optional functionality may require locally installed components such as **Ollama**, **FFmpeg**, or **Spotify Basic Pitch**. OlsonAI reports component readiness rather than hiding missing dependencies.

## Updates

OlsonAI includes an update system that checks the public beta manifest, verifies downloaded installers with SHA-256, and launches the installer when an update is approved.

After installing a newer version, OlsonAI can show a **What’s New** walkthrough on first launch so users know what changed and how to use it.

## Windows integration

OlsonAI includes Windows desktop behavior such as:

- Taskbar integration
- Start Menu shortcuts
- System tray support
- Optional minimize-to-tray behavior
- Drag-and-drop routing
- Optional **Send to OlsonAI** Explorer integration
- Startup and completion sounds with a persistent mute toggle

## Requirements

- Windows 10 or Windows 11, 64-bit
- Sufficient disk space for OlsonAI and any optional local AI models/components
- Ollama for supported local conversational AI workflows
- FFmpeg for supported audio/video conversion workflows
- Basic Pitch support for Audio → MIDI transcription

The downloadable Windows installer contains the OlsonAI application itself. Optional large local models/components are handled separately and are not silently downloaded by OlsonAI.

## Installation

1. Open the latest OlsonAI release on GitHub.
2. Download the current Windows installer.
3. Run the installer.
4. Launch OlsonAI from the Start Menu or desktop shortcut.
5. Follow the in-app setup/onboarding guidance.

Because OlsonAI is currently distributed as a beta, Windows may display a SmartScreen warning on unsigned or newly distributed builds. Review the file/source before choosing to continue.

## Beta software

OlsonAI is actively being tested and improved. Beta releases may contain bugs, incomplete edge-case handling, or behavior that changes between versions.

For file-changing tools, review the proposed action before approval and keep backups of important data.

## Reporting bugs

When reporting an issue, include:

- OlsonAI version
- What you were doing
- What you expected to happen
- What actually happened
- A screenshot when useful

Beta 9 also includes privacy-conscious diagnostic reporting to make tester feedback more actionable without including chat contents, prompts, file contents, or filenames.

## Privacy & safety philosophy

OlsonAI is built around a simple rule: **the user stays in control.**

Actions that can modify files are designed to show what is about to happen before execution. Where appropriate, OlsonAI uses the Recycle Bin, safe Undo, and review steps instead of destructive one-click behavior.

## Project

OlsonAI was created by **Justin Olson**, with development assistance from ChatGPT/OpenAI. OlsonAI’s local conversational functionality can use models served through Ollama; model attribution remains with the respective model creators.

## Current release

**OlsonAI 1.0 Beta 9**

Release tag: `v1.0.0-beta.9`

Installer: `OlsonAI_Setup_1.0.0_Beta9.exe`

SHA-256:

```text
01DFCA9E8156655A91637ABB02B5B4B30398926C5D06922DD10FD4BE83C27FA4
```

---

**OlsonAI — Your PC. Your Files. Your AI.**
