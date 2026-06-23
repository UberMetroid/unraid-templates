# UberMetroid Unraid Docker Templates

This repository contains official Unraid XML templates for deploying and hosting a suite of clean, secure, and lightweight applications built in Rust.

## Application Suite

*   **[RustDo](https://github.com/UberMetroid/RustDo)**: A minimalist, secure, and clean task manager/todo list.
    *   **Default Port**: `4403`
    *   **Data Directory**: `/app/data`
*   **[RustDrop](https://github.com/UberMetroid/RustDrop)**: A drag-and-drop file sharing portal with customizable retention and quota limits.
    *   **Default Port**: `4401`
    *   **Data Directory**: `/usr/src/app/data` (config) & `/usr/src/app/uploads` (file storage)
*   **[RustPad](https://github.com/UberMetroid/RustPad)**: A collaborative real-time notepad and text editor.
    *   **Default Port**: `4402`
    *   **Data Directory**: `/app/data`

## How to Install on Unraid

To use these templates on your Unraid server:

1. Copy the URL of this repository: `https://github.com/UberMetroid/unraid-templates`
2. Go to your Unraid WebUI.
3. Open the **Docker** tab, go to **Template Repositories** (or via Community Applications configuration), and add this repository link.
4. Search for `RustDo`, `RustDrop`, or `RustPad` to install them with 1-click presets.
