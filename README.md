# reading.jnapolitano.io

A Python-based project focused on building and deploying the static site reading.jnapolitano.io. This repository contains automation scripts for dependency management, building HTML documentation, and deployment processes.

## Features

- Automated dependency installation via pip
- Build automation using Makefile commands (clean and html targets)
- Git commit and push automation integrated into the build pipeline

## Tech Stack

- Python 3
- Make (for build automation)
- Git (for version control and deployment)

## Getting Started

### Prerequisites

- Python 3 installed
- pip package manager
- Make utility
- Git

### Installation

Clone the repository:

```bash
git clone https://github.com/justin-napolitano/reading.jnapolitano.io.git
cd reading.jnapolitano.io
```

Install dependencies:

```bash
pip install -r requirements.txt
```

### Usage

Run the build script to clean previous builds, generate HTML, commit changes, and push to the remote repository:

```bash
python python-build.py
```

(Note: This assumes the default branch is `master` and that you have configured git credentials.)

## Project Structure

```
reading.jnapolitano.io/
├── deployz/                # Deployment related scripts or configurations (assumed)
├── python-build.py         # Main Python script handling build and deployment pipeline
├── requirements.txt        # Python dependencies
├── Makefile                # Makefile with targets such as 'clean' and 'html' (assumed)
```

- `python-build.py` contains classes for configuration, dependency installation, and build pipeline automation.
- `deployz/` directory likely holds deployment scripts or related resources.

## Future Work / Roadmap

- Expand automation to include testing and linting steps
- Add configuration for multiple deployment environments
- Improve error handling and logging in build scripts
- Document deployment process in more detail
- Modularize build pipeline for easier extension

---

*Note: Some assumptions were made regarding the Makefile presence and deployment directory contents based on standard practices.*