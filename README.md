# UberMetroid Unraid Docker Templates

This repository contains official Unraid XML templates for deploying and hosting a suite of clean, secure, and lightweight applications built in Rust.

All container images are **Nix-built** (no Alpine) and published to Docker Hub. For the build source, see each application's `flake.nix`.

## Application Suite

| Icon | Application | Description | Default Port | Data Directory |
| :---: | :--- | :--- | :---: | :--- |
| <img src="https://raw.githubusercontent.com/UberMetroid/unraid-templates/main/icons/beam.png" width="48" height="48"> | **[beam](https://github.com/UberMetroid/beam)** | A secure web portal for file transfers, uploads, and payload sharing. | `4401` | `/app/data` (config) & `/app/uploads` (storage) |
| <img src="https://raw.githubusercontent.com/UberMetroid/unraid-templates/main/icons/pad.png" width="48" height="48"> | **[pad](https://github.com/UberMetroid/pad)** | A collaborative, real-time rich text editor and notepad. | `4402` | `/app/data` |
| <img src="https://raw.githubusercontent.com/UberMetroid/unraid-templates/main/icons/todo.png" width="48" height="48"> | **[todo](https://github.com/UberMetroid/todo)** | A minimalist, secure, and clean task manager/todo list. | `4403` | `/app/data` |
| <img src="https://raw.githubusercontent.com/UberMetroid/unraid-templates/main/icons/trace.png" width="48" height="48"> | **[trace](https://github.com/UberMetroid/trace)** | An IP and ASN Whois lookup tool for analyzing network endpoints. | `4404` | `/app/data` |
| <img src="https://raw.githubusercontent.com/UberMetroid/unraid-templates/main/icons/grid.png" width="48" height="48"> | **[grid](https://github.com/UberMetroid/grid)** | A visual project management board for tracking tasks and workflows. | `4405` | `/app/data` |
| <img src="https://raw.githubusercontent.com/UberMetroid/unraid-templates/main/icons/pulse.png" width="48" height="48"> | **[pulse](https://github.com/UberMetroid/pulse)** | A real-time host statistics, system telemetry, and HUD visor monitor. | `4406` | *N/A* |

## How to Install on Unraid

To use these templates on your Unraid server:

1. Copy the URL of this repository: `https://github.com/UberMetroid/unraid-templates`
2. Go to your Unraid WebUI.
3. Open the **Docker** tab, go to **Template Repositories** (or via Community Applications configuration), and add this repository link.
4. Search for `beam`, `pad`, `todo`, `trace`, `grid`, or `pulse` to install them with 1-click presets.
