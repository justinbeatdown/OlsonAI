# OlsonAI

**Your PC. Your Files. Your AI.**

OlsonAI is a local-first Windows desktop AI assistant built to make everyday computer work faster, safer, and easier. It combines conversational AI with practical file tools, creation utilities, organization workflows, local search, cleanup tools, and desktop integration while keeping the user in control of file-changing actions.

> **Current public beta:** OlsonAI **1.0 Beta 9** (`1.0.0-beta.9`)

## What’s new in Beta 9

Beta 9 is a major usability and Create Suite update focused on smoother Windows behavior, better file workflows, clearer guidance, and a more complete out-of-box setup experience.

- **Create Suite File Converter** — batch-convert common image, audio, video, data, and text formats locally.
- **Audio → MIDI Transcription** — transcribe detected musical notes from MP3, WAV, FLAC, OGG, and M4A audio into usable MIDI with local Spotify Basic Pitch support.
- **What’s New screen** — after an update, OlsonAI explains what changed, where to find it, and how to use it on first launch.
- **Home Command Center** — recent activity, quick actions, local component status, and safe Undo for supported operations.
- **Smoother Windows minimize/restore** — rebuilt taskbar and system-tray transitions to reduce flicker, lag, and awkward restore behavior.
- **Drag & drop** — route compatible files and folders directly into supported OlsonAI tools.
- **Optional “Send to OlsonAI” Explorer integration** — bring files and folders into OlsonAI from the Windows right-click workflow.
- **Bundled runtime components** — OlsonAI now ships with its required application runtime components so users do not need to separately install Python, Ollama, FFmpeg, Basic Pitch, or ONNX Runtime.
- **Permission-gated local AI setup** — the large Gemma model is downloaded only after the user approves it.
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
- Large local AI model downloads are not silent; OlsonAI asks first.
- Local AI runs through an Ollama-based local runtime bundled with OlsonAI.
- Diagnostic reports are intentionally sanitized and exclude chat contents, prompts, file contents, filenames, and personal workspace paths.

## Out-of-box setup

Beta 9 is designed so a new user can install OlsonAI without separately installing Python, Ollama, FFmpeg, Basic Pitch, or ONNX Runtime.

The main installer includes OlsonAI and its required runtime components. On first use of local conversational AI, OlsonAI checks for the Gemma model and asks for permission before downloading it.

Typical flow:

1. Download and install OlsonAI.
2. Launch OlsonAI.
3. Approve the local AI model download when prompted.
4. OlsonAI downloads and prepares the model locally.
5. Start using OlsonAI.

## Storage requirements

- **Installer download:** approximately **1.38 GB** for Beta 9.
- **Additional local AI model download:** approximately **3.3 GB** for the recommended Gemma model.
- **Recommended free disk space before setup:** at least **6–8 GB** to allow room for installation, the local model, caches, updates, and working space.

Actual installed size can vary by Windows configuration, model cache state, and future updates.

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
- No separate Python installation required
- No separate Ollama installation required
- No separate FFmpeg installation required
- No separate Basic Pitch installation required
- Internet connection required only for downloads/updates and initial local-model retrieval
- A dedicated GPU is **not required**; OlsonAI can fall back to CPU/system RAM, though local AI responses may be slower without GPU acceleration

## Installation

1. Open the latest OlsonAI release on GitHub.
2. Download `OlsonAI_Setup_1.0.0_Beta9.exe`.
3. Run the installer.
4. Launch OlsonAI from the Start Menu or desktop shortcut.
5. Follow the in-app setup guidance.
6. Approve the local AI model download when prompted if you want to use local conversational AI.

Because OlsonAI is currently distributed as a beta, Windows may display a SmartScreen warning on unsigned or newly distributed builds. Review the file/source before choosing to continue.

## Updates

OlsonAI includes an update system that checks the public beta manifest, verifies downloaded installers with SHA-256, and launches the installer when an update is approved.

After installing a newer version, OlsonAI can show a **What’s New** walkthrough on first launch so users know what changed and how to use it.

## Beta software disclaimer

OlsonAI is pre-release beta software and is provided **as-is**, without warranties of any kind to the extent permitted by applicable law. Beta releases may contain bugs, incomplete edge-case handling, or behavior that changes between versions.

OlsonAI includes tools that can create, rename, move, organize, convert, and remove user-approved files. Review proposed actions before approval and keep independent backups of important data.

Where applicable, OlsonAI favors review gates, safe Undo, and the Windows Recycle Bin rather than silent destructive behavior, but no software can guarantee against data loss, incompatibility, interruption, or other unexpected results.

This project documentation is general information, not legal advice.

## Privacy & data safety

OlsonAI is built around a simple rule: **the user stays in control.**

- Routine local file operations are designed to remain local.
- File-changing operations are review-driven before execution.
- Diagnostics exclude chat contents, prompts, file contents, filenames, and personal workspace paths.
- Large local model downloads require user approval.
- Users should maintain backups of important files before using beta file-management tools.

## Third-party software & licenses

OlsonAI includes, bundles, or integrates third-party software and models. Those components remain subject to their own licenses and terms.

Current Beta 9 components include, among others:

- **Ollama** — local model runtime
- **FFmpeg / imageio-ffmpeg** — media conversion support
- **Spotify Basic Pitch** — Audio → MIDI transcription
- **ONNX Runtime** — local inference runtime used by Audio → MIDI
- **Google Gemma** — local conversational model family used by OlsonAI

See `THIRD_PARTY_NOTICES.md` in the source/release materials for attribution and licensing details. The exact licenses and notices for redistributed binaries should be reviewed for each public release, especially FFmpeg, whose licensing depends on how the distributed binary was built.

## AI-assisted development disclosure

OlsonAI was created by **Justin Olson** with development assistance from ChatGPT/OpenAI. AI-assisted development tools have been used during coding, testing, debugging, documentation, and iteration. Third-party models and runtimes retain attribution to their respective creators.

## Reporting bugs

When reporting an issue, include:

- OlsonAI version
- What you were doing
- What you expected to happen
- What actually happened
- A screenshot when useful

Beta 9 includes privacy-conscious diagnostic reporting to make tester feedback more actionable without including chat contents, prompts, file contents, filenames, or personal workspace paths.

## Current release

**OlsonAI 1.0 Beta 9**

Release tag: `v1.0.0-beta.9`

Installer: `OlsonAI_Setup_1.0.0_Beta9.exe`

Installer size: approximately **1.38 GB**

SHA-256:

```text
9B707495E19299FE1032C7E896A085538101C3928422F93F1EB8E3D44F3AECD6
```

---

**OlsonAI — Your PC. Your Files. Your AI.**
