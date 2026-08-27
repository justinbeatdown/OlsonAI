# OlsonAI

### Your PC. Your Files. Your AI.

**OlsonAI** is a local-first Windows desktop AI assistant designed to help you organize, understand, clean, search, and work with the files on your computer — without turning basic PC tasks into a complicated workflow.

OlsonAI combines a conversational AI assistant with practical desktop tools, file management, automation, and system utilities in one application.

> **Current Release:** OlsonAI 1.0 Beta 8  
> **Platform:** Windows  
> **Status:** Active Beta Development

---

## What is OlsonAI?

OlsonAI is designed around a simple idea:

**Your AI assistant should be able to help with your actual computer, not just answer questions in a chat box.**

You can talk naturally with OlsonAI or use dedicated tools for specific jobs.

OlsonAI can help organize messy folders, find duplicate files, identify unnecessary clutter, rename files intelligently, search your computer, analyze files and images, create new files, and more.

Much of OlsonAI is designed to operate locally on your computer, with user approval required before potentially destructive actions are performed.

---

## Features

### Ask OlsonAI

A conversational AI assistant built directly into OlsonAI.

Use it for:

- General questions and conversation
- Help using your computer
- File-related requests
- Starting OlsonAI tools
- Creating content
- Summarizing information
- Casual conversation
- Interactive games
- Context-aware assistance

OlsonAI includes local AI support and is being actively developed to provide more natural, useful, and context-aware conversations.

---

### Smart Organize

Turn cluttered folders into useful folder structures.

Smart Organize can:

- Analyze the contents of a folder
- Identify different types of files
- Suggest logical categories
- Create an organization plan
- Suggest improved filenames
- Move files into organized folders
- Allow you to review proposed changes before applying them

**OlsonAI does not reorganize your files until you approve the plan.**

---

### Smart Rename

Analyze files and suggest cleaner, more descriptive filenames.

Useful for:

- Downloads
- Photos
- Documents
- Project files
- Poorly named exports
- Automatically generated filenames

Review the proposed names before OlsonAI makes changes.

---

### Smart Search

Search your computer using more natural queries instead of manually digging through folders.

Designed to make finding files faster when you know what you're looking for but don't remember exactly where it is.

---

### Duplicate Finder

Find exact duplicate files that are wasting storage space.

Features include:

- SHA-256 exact duplicate detection
- Duplicate grouping
- File size information
- Location information
- Review before removal
- Safe cleanup through the Windows Recycle Bin

Files are not permanently deleted automatically.

---

### Smart Cleanup

Find files that are likely unnecessary while keeping the user in control.

Smart Cleanup supports:

- Quick scans
- Selected-folder scans
- Full PC scans
- Optional deeper scanning of hidden/cache locations
- Temporary file detection
- Cache and junk detection
- Duplicate detection
- File explanations
- Confidence information
- Review before cleanup

Items approved for removal are sent to the **Windows Recycle Bin** whenever possible instead of being permanently erased.

System folders and personal content are protected by safety rules.

---

### Ask My Files

Use OlsonAI to work with and understand information stored in your files.

Designed for things like:

- Asking questions about documents
- Finding information
- Understanding file contents
- Summarizing material
- Locating relevant files

---

### Image Analyzer

Analyze images directly inside OlsonAI.

Use it to better understand images, identify visible content, and incorporate images into AI-assisted workflows.

---

### Clipboard AI

Work with content already copied to your Windows clipboard.

Designed to make quick AI-assisted actions possible without constantly moving information between applications.

---

### Create Studio

Turn an idea into an actual file without leaving OlsonAI.

Create Studio supports multiple output formats, including:

- TXT
- Markdown
- Word documents
- PDF
- CSV
- Excel
- HTML
- Python
- PowerShell
- Batch files
- JSON
- Images

Choose the file type, destination, and what you want OlsonAI to create.

You can review generated content before saving it.

---

## Task Center

OlsonAI includes a centralized task system for longer-running operations.

Tasks can continue while you navigate elsewhere in the application.

The Task Center provides information about:

- Active tasks
- Progress
- Completed tasks
- Failed tasks
- Task status
- Relevant tool navigation

When a task finishes, OlsonAI can notify you and provide a direct route back to the tool that performed the work.

---

## Approval System

OlsonAI is designed around **review before action**.

Operations that can modify, move, rename, or remove your files can require approval before execution.

The approval system helps make it clear:

- What OlsonAI wants to do
- Which files are affected
- Why an action is being suggested
- What will happen after approval

The goal is simple:

**AI should help manage your computer without silently taking control of it.**

---

## Local AI

OlsonAI is being developed with a **local-first architecture**.

Supported local models can perform AI tasks directly on your computer, reducing dependence on external AI services.

Benefits include:

- Greater privacy
- Local processing
- No per-message API charge for supported local operations
- Continued functionality without depending entirely on cloud services

Performance depends on your computer hardware and the model being used.

---

## Memory

OlsonAI can optionally remember useful preferences between conversations.

Memory is:

- Optional
- User controlled
- Viewable from Settings
- Clearable by the user

You can disable OlsonAI memory at any time.

---

## Desktop & System Tray

OlsonAI is designed to behave like a normal Windows desktop application.

It supports:

- Windows taskbar integration
- System tray operation
- Minimize-to-tray behavior
- Close-to-tray behavior
- Background tasks
- Startup and notification sounds
- One-click sound mute control

Tray behavior can be configured from **Settings**.

---

## Updates

OlsonAI includes a built-in update system.

The application can check the official OlsonAI GitHub release channel for new versions.

Updates use:

- Versioned releases
- Release manifests
- SHA-256 installer verification

SHA-256 verification helps ensure that the downloaded installer matches the installer published for that release.

---

## Safety Philosophy

OlsonAI deals with real files on real computers, so safety is a major part of the project.

Whenever practical, OlsonAI follows these principles:

1. **Analyze first**
2. **Explain what it found**
3. **Show the proposed action**
4. **Ask for approval**
5. **Perform the approved action**
6. **Prefer reversible operations**

For example, cleanup operations generally prefer the **Recycle Bin** over permanent deletion.

---

## Requirements

OlsonAI is currently developed for:

- **Windows 10 / Windows 11**
- 64-bit Windows recommended
- Sufficient RAM for local AI models
- Additional disk space for local models
- Internet connection for application updates

Local AI performance varies significantly depending on CPU, RAM, GPU, and model size.

---

## Installation

The easiest way to install OlsonAI is through the GitHub **Releases** section.

1. Open the latest OlsonAI release.
2. Download the Windows installer.
3. Run the installer.
4. Follow the installation prompts.
5. Launch OlsonAI.

Because OlsonAI is currently beta software, Windows may display additional security prompts for unsigned or newly published builds.

---

## Beta Software

> **OlsonAI is currently beta software.**

Features may change, bugs may occur, and some functionality is still actively being developed.

Beta testers are encouraged to report unexpected behavior so it can be investigated before a stable release.

**Do not use beta software as your only copy of irreplaceable data. Maintain backups of important files.**

---

## Reporting Bugs

Found something broken?

Please use the GitHub **Issues** section to report it.

Helpful bug reports include:

- OlsonAI version
- Windows version
- What you were trying to do
- What you expected to happen
- What actually happened
- Screenshots when applicable
- Steps that reproduce the problem

---

## Feature Requests

Ideas and suggestions are welcome.

Use GitHub Issues to suggest:

- New tools
- Workflow improvements
- UI improvements
- AI capabilities
- File-management features
- Quality-of-life changes

OlsonAI is actively evolving based on real-world testing and feedback.

---

## Current Development Status

OlsonAI is under active development.

The current development focus includes:

- AI conversation quality
- Local AI performance
- File-management intelligence
- Safer automation
- Windows integration
- Task reliability
- UI responsiveness
- Create Studio
- Image generation and analysis
- Better system-wide workflows

---

## Privacy

OlsonAI is designed around a local-first approach, but **not every current or future feature should automatically be assumed to operate entirely offline**.

Features that communicate with external services should be clearly identified as development progresses.

Users should always understand when information is being processed locally versus externally.

---

## Project

**OlsonAI Desktop Assistant**

Created and maintained by **Justin Olson**

### Your PC. Your Files. Your AI.

---

## Releases

Download the newest public build from the **Releases** section of this repository.

If you're already using OlsonAI, you can also check for updates from:

**Settings → Updates & Beta Feedback → Check Now**

---

### Thanks for testing OlsonAI

OlsonAI is being built to make AI genuinely useful on a Windows PC — not just another chatbot sitting in a browser.

If you're testing an early build, reporting bugs, suggesting features, or simply trying it out:

**Thank you for helping make OlsonAI better.**
