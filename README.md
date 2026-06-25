# UberMetroid Unraid Docker Templates

This repository contains official Unraid XML templates for deploying and hosting a suite of clean, secure, and lightweight applications built in Rust.

## Application Suite

| Icon | Application | Description | Default Port | Data Directory |
| :---: | :--- | :--- | :---: | :--- |
| <img src="https://raw.githubusercontent.com/UberMetroid/adam/main/frontend/Assets/favicon.png" width="48" height="48"> | **[adam](https://github.com/UberMetroid/adam)** | A minimalist, secure, and clean task manager/todo list. | `4403` | `/app/data` |
| <img src="https://raw.githubusercontent.com/UberMetroid/aura/main/frontend/favicon.png" width="48" height="48"> | **[aura](https://github.com/UberMetroid/aura)** | An AI-assisted search tool integrated with status polling and image generation. | `4408` | `/app/data` |
| <img src="https://raw.githubusercontent.com/UberMetroid/beam/main/frontend/Assets/assets/icon.png" width="48" height="48"> | **[beam](https://github.com/UberMetroid/beam)** | A secure web portal for file transfers, uploads, and payload sharing. | `4401` | `/app/data` (config) & `/app/uploads` (storage) |
| <img src="https://raw.githubusercontent.com/UberMetroid/glyph/main/frontend/public/favicon.png" width="48" height="48"> | **[glyph](https://github.com/UberMetroid/glyph)** | A web-based word guessing application built in a single Cargo package. | `4409` | None (stateless) |
| <img src="https://raw.githubusercontent.com/UberMetroid/grid/main/logo.png" width="48" height="48"> | **[grid](https://github.com/UberMetroid/grid)** | A visual project management board for tracking tasks and workflows. | `4405` | `/app/data` |
| <img src="https://raw.githubusercontent.com/UberMetroid/pad/main/frontend/Assets/pad.png" width="48" height="48"> | **[pad](https://github.com/UberMetroid/pad)** | A collaborative, real-time rich text editor and notepad. | `4402` | `/app/data` |
| <img src="https://raw.githubusercontent.com/UberMetroid/trace/main/frontend/Assets/assets/logo.png" width="48" height="48"> | **[trace](https://github.com/UberMetroid/trace)** | An IP and ASN Whois lookup tool for analyzing network endpoints. | `4404` | None (stateless) |

## How to Install on Unraid

To use these templates on your Unraid server:

1. Copy the URL of this repository: `https://github.com/UberMetroid/unraid-templates`
2. Go to your Unraid WebUI.
3. Open the **Docker** tab, go to **Template Repositories** (or via Community Applications configuration), and add this repository link.
4. Search for `adam`, `aura`, `beam`, `glyph`, `grid`, `pad`, or `trace` to install them with 1-click presets.
