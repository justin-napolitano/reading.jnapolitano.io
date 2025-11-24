---
slug: github-reading-jnapolitano-io-note-technical-overview
id: github-reading-jnapolitano-io-note-technical-overview
title: Technical Overview of reading.jnapolitano.io
repo: justin-napolitano/reading.jnapolitano.io
githubUrl: https://github.com/justin-napolitano/reading.jnapolitano.io
generatedAt: '2025-11-24T18:44:48.585Z'
source: github-auto
summary: >-
  This repo automates building and deploying the static site at
  reading.jnapolitano.io using Python.
tags: []
seoPrimaryKeyword: ''
seoSecondaryKeywords: []
seoOptimized: false
topicFamily: null
topicFamilyConfidence: null
kind: note
entryLayout: note
showInProjects: false
showInNotes: true
showInWriting: false
showInLogs: false
---

This repo automates building and deploying the static site at reading.jnapolitano.io using Python.

## Key Components:
- **Python 3**: Main language.
- **Make**: For build automation.
- **Git**: Version control and deployment.

## Getting Started:
1. **Clone the repo**:
    ```bash
    git clone https://github.com/justin-napolitano/reading.jnapolitano.io.git
    cd reading.jnapolitano.io
    ```
2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3. **Build and deploy**:
    ```bash
    python python-build.py
    ```
   - Ensure your default Git branch is `master` and that you've set up your Git credentials.

## Project Structure:
- **python-build.py**: Handles the build and deployment pipeline.
- **Makefile**: Contains `clean` and `html` targets.
- **deployz/**: Contains scripts for deployment (assumed).

Gotcha: Double-check your Git configurations; they can trip you up.
