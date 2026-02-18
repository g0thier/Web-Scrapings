# Web Scrapings

## Description

This repository contains practical web scraping notebooks for three real use cases:
- Job listings extraction from JobScout24
- PDF capture and post-processing workflows for ScholarVox
- Batch video downloads from YouTube

![Capture](/docs/images/Capture.png)

## Table of Contents

- [Web Scrapings](#web-scrapings)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [🎯 Objective of the project](#-objective-of-the-project)
  - [👥 Target audience](#-target-audience)
  - [⚙️ What this repository includes](#️-what-this-repository-includes)
  - [🗂️ Repository structure](#️-repository-structure)
  - [🚀 Quick start](#-quick-start)
  - [🐳 Install \& run](#-install--run)
  - [🥽 Security](#-security)
  - [📰 Changelog](#-changelog)
  - [🩷 Acknowledgements](#-acknowledgements)
  - [🧰 Environment](#-environment)
  - [🧪 Project Status](#-project-status)
  - [🔒 License](#-license)
  - [🤝 Contributing](#-contributing)
  - [👤 Author](#-author)

## 🎯 Objective of the project

Build and maintain reusable notebook-based scraping workflows for data collection, document capture, and media retrieval.

## 👥 Target audience 

- Python developers who prefer exploratory notebook workflows
- Students and practitioners learning practical scraping and automation techniques
- People who need small, focused scraping pipelines instead of a full framework

## ⚙️ What this repository includes

- `.gitignore` for macOS configuration
- Community and governance files:
  - `CODE_OF_CONDUCT.md`
  - `CONTRIBUTING.md`
  - `SECURITY.md`
  - `CHANGELOG.md`
  - `LICENSE.md`
  - `ACKNOWLEDGEMENTS.md`
- Scraping notebooks in `notebooks/`:
  - `notebooks/Jobscout24/notebook.ipynb`
  - `notebooks/Scholarvox/notebook.ipynb`
  - `notebooks/Scholarvox/bounding_box.ipynb`
  - `notebooks/Youtube/notebook.ipynb`
- Basic documentation assets in `docs/images/`

## 🗂️ Repository structure

```text
Web-Scrapings/
├── docs/
│   └── images/
├── notebooks/
│   ├── Jobscout24/
│   │   └── notebook.ipynb
│   ├── Scholarvox/
│   │   ├── auth_state.json
│   │   ├── bounding_box.ipynb
│   │   └── notebook.ipynb
│   └── Youtube/
│       └── notebook.ipynb
├── .gitignore
├── ACKNOWLEDGEMENTS.md
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE.md
├── README.md
└── SECURITY.md
```

## 🚀 Quick start

1. Create and activate a Python virtual environment.
2. Install Jupyter and required libraries (see Environment section).
3. Open the notebook for your use case:
   - `notebooks/Jobscout24/notebook.ipynb`
   - `notebooks/Scholarvox/notebook.ipynb`
   - `notebooks/Youtube/notebook.ipynb`
4. Update notebook parameters (search terms, URLs, paths, output names).
5. Run cells from top to bottom and review outputs.

## 🐳 Install & run

Install the common notebook stack:

```bash
pip install jupyter requests beautifulsoup4 lxml yt-dlp playwright pypdf PyPDF2 pymupdf
```

For Playwright-based workflows (ScholarVox), install browser binaries once:

```bash
python -m playwright install
```

## 🥽 Security

- See [SECURITY.md](/SECURITY.md) for vulnerability reporting guidelines.

## 📰 Changelog

Track all notable project changes in [CHANGELOG.md](/CHANGELOG.md).

Recommended:
- Follow a consistent format such as Keep a Changelog
- Create an entry for each release
- Include Added, Changed, Fixed, and Removed sections when relevant

## 🩷 Acknowledgements

- See [ACKNOWLEDGEMENTS.md](/ACKNOWLEDGEMENTS.md) for credits to people, tools, libraries, and communities that support this project.

## 🧰 Environment

- **Python >= 3.10** recommended
- Notebook execution environment (`jupyter`)
- Main libraries used across notebooks:
  - `requests`, `beautifulsoup4`, `lxml`
  - `playwright`, `pypdf`, `PyPDF2`, `pymupdf`
  - `yt-dlp`

## 🧪 Project Status

- 🔬 **Status**: experimental
- 🧭 **Roadmap**: iterative notebook improvements per source and use case

## 🔒 License

- See [LICENSE.md](/LICENSE.md).

## 🤝 Contributing

Contributions are welcome.
- See [CONTRIBUTING.md](/CONTRIBUTING.md)
- Code of conduct available in [CODE_OF_CONDUCT.md](/CODE_OF_CONDUCT.md).

## 👤 Author

Gauthier Rammault
