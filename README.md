# Mangaplus Downloader

[![Latest Github release](https://img.shields.io/github/tag/hurlenko/mloader.svg)](https://github.com/hurlenko/mloader/releases/latest)
![Python](https://img.shields.io/badge/python-v3.6+-blue.svg)
![License](https://img.shields.io/badge/license-GPLv3-blue.svg)

## **mloader** - download manga chapters from mangaplus.shueisha.co.jp

## 🚩 Table of Contents

- [Installation](#-installation)
- [Usage](#-usage)
- [Command line interface](#%EF%B8%8F-command-line-interface)

## 💾 Installation

The recommended installation method is using `pip`:

```bash
pip install https://github.com/hurlenko/mloader/archive/master.zip
```

After installation, the `mloader` command will be available. Check the [command line](%EF%B8%8F-command-line-interface) section for supported commands.

## 📙 Usage

Get the id of the chapter you want to download from the url: mangaplus.shueisha.co.jp/viewer/**[chapter_id_here]**.

Note that title downloads (title id's have form `[website]/title/[title_id]`) are not supported but you can pass multiple chapter id's.

Chapters can be saved as `CBZ` (default) archives or separate images by passing the `raw` parameter.

## 🖥️ Command line interface

Currently `mloader` supports these commands

```bash
Usage: mloader [OPTIONS] [CHAPTERS]...

Options:
  -o, --out <directory>  Save directory (not a file)  [default:
                         mangaplus_downloads]
  -r, --raw              Save raw images  [default: False]
  --help                 Show this message and exit.
```