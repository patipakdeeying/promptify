# Promptify Files 🚀

**Promptify Files** is a lightweight, browser-based utility designed to help developers quickly convert their codebase into a structured, AI-ready prompt. Whether you're working with Gemini, Claude, or ChatGPT, this tool formats your files and folder structures into a clean Markdown format that LLMs can easily parse and understand.

## ✨ Features

* **Folder & File Support**: Upload individual files or entire directories recursively using the native folder picker.
* **Drag & Drop**: Simply drag your project folder onto the interface to begin processing.
* **Visual Project Tree**: Automatically generates a directory structure tree (e.g., `├── src/`) to give the AI context of your file organization.
* **Markdown Code Blocks**: Wraps file contents in appropriate Markdown tags (e.g., ` ```javascript `) with automatic language detection.
* **Automatic Copy**: Instantly copies the generated prompt to your clipboard the moment processing is finished.
* **Privacy First**: All processing happens locally in your browser using the `FileReader` API. **No files are ever uploaded to a server.**
* **Smart Filtering**: Automatically skips binary files (images, audio, etc.) and ignores heavy folders like `node_modules` or `.git`.

## 🛠️ How to Use

1. Open [live URL](https://patipakdeeying.github.io/promptify/) or host it your self.
2. Click **Add Folder** to select your project directory or drag it into the drop zone.
3. Wait a split second for the "Processing" indicator to finish.
4. The generated prompt is now in your clipboard! Paste it directly into your favorite AI chat.

## 📝 Supported Languages

The tool automatically detects and tags dozens of languages, including:
* JavaScript / TypeScript / JSX / TSX
* Python / Ruby / PHP / Go / Rust
* Lua / C++ / C# / Java
* HTML / CSS / SCSS
* Markdown / JSON / YAML / SQL

## 🛡️ Privacy

Promptify Files values your privacy. It does not use any backend or tracking. Your source code stays in your browser.

---

*Made for developers who want to talk to AI more efficiently.*
