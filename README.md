# 🖼️ rimg

**rimg** is a lightweight Bash tool for filtering out image URLs from large URL collections such as those obtained from Wayback Machine or recon tools like `gau`, `waybackurls`, etc.

## 🚀 Features

- Removes common image extensions: `.jpg`, `.jpeg`, `.png`, `.gif`, `.bmp`, `.svg`, `.webp`, `.ico`
- Accepts piped input or redirection
- Usable in UNIX pipelines (e.g., with `httpx`)
- Vim-friendly

## 🛠️ Installation

```bash
sudo curl -o /usr/local/bin/rimg https://raw.githubusercontent.com/byteoverride/rimg/main/rimg
sudo chmod +x /usr/local/bin/rimg

