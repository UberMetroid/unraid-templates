# UberMetroid Unraid Docker Templates

This repository contains official Unraid XML templates for deploying and hosting a suite of clean, secure, and lightweight applications built in Rust.

## Application Suite

| Icon | Application | Description | Default Port | Data Directory |
| :---: | :--- | :--- | :---: | :--- |
| <img src="https://raw.githubusercontent.com/UberMetroid/RustDo/main/frontend/Assets/favicon.png" width="48" height="48"> | **[RustDo](https://github.com/UberMetroid/RustDo)** | A minimalist, secure, and clean task manager/todo list. | `4403` | `/app/data` |
| <img src="https://raw.githubusercontent.com/UberMetroid/RustDrop/main/frontend/Assets/assets/icon.png" width="48" height="48"> | **[RustDrop](https://github.com/UberMetroid/RustDrop)** | A drag-and-drop file sharing portal with customizable retention and quota limits. | `4401` | `/usr/src/app/data` (config) & `/usr/src/app/uploads` (storage) |
| <img src="https://raw.githubusercontent.com/UberMetroid/RustKan/main/logo.png" width="48" height="48"> | **[RustKan](https://github.com/UberMetroid/RustKan)** | A clean, secure, and lightning-fast Kanban board application. | `4405` | `/usr/src/app/data` |
| <img src="https://raw.githubusercontent.com/UberMetroid/RustPad/main/frontend/Assets/rustpad.png" width="48" height="48"> | **[RustPad](https://github.com/UberMetroid/RustPad)** | A collaborative real-time notepad and text editor. | `4402` | `/app/data` |
| <img src="https://raw.githubusercontent.com/UberMetroid/RustWho/main/frontend/Assets/assets/logo.png" width="48" height="48"> | **[RustWho](https://github.com/UberMetroid/RustWho)** | A lightning-fast, privacy-respecting WHOIS, IP, and ASN lookup utility. | `4404` | None (stateless) |
| <img src="https://raw.githubusercontent.com/UberMetroid/Rustle/master/public/favicon.png" width="48" height="48"> | **[Rustle](https://github.com/UberMetroid/Rustle)** | An optimized Wordle game clone. | `4409` | None (stateless) |

## How to Install on Unraid

To use these templates on your Unraid server:

1. Copy the URL of this repository: `https://github.com/UberMetroid/unraid-templates`
2. Go to your Unraid WebUI.
3. Open the **Docker** tab, go to **Template Repositories** (or via Community Applications configuration), and add this repository link.
4. Search for `RustDo`, `RustDrop`, `RustKan`, `RustPad`, `RustWho`, or `Rustle` to install them with 1-click presets.
