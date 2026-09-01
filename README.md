# ATLAS Plugin Repository Demo

Public demo repository for testing the ATLAS plugin repository workflow.

[![Open the ATLAS Plugin Repository install test page.](https://img.shields.io/badge/ATLAS-Install%20Test-0f8f83?style=for-the-badge)](https://rockbaer2007.github.io/atlas-plugin-repository-demo/install.html)
[![Open this repository in Home Assistant.](https://img.shields.io/badge/Home%20Assistant-Repository%20oeffnen-03a9f4?style=for-the-badge)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Frockbaer2007%2Fatlas-plugin-repository-demo)

## Repository URL

Use this URL in ATLAS Administration:

```text
https://raw.githubusercontent.com/rockbaer2007/atlas-plugin-repository-demo/main/repository.json
```

The page explains the ATLAS repository flow, provides the `repository.json` URL
for Administration and keeps the optional My Home Assistant add-on repository
handoff as a separate test action.

## Contents

```text
repository.json
plugins/
  simple-file-editor/
    atlas-plugin.json
    simple-file-editor.atlas-plugin.json
    icon.svg
    logo.svg
    preview.svg
    README.md
```

## Purpose

This repository is the first public reference for:

- the `repository.json` catalog format
- plugin icon, logo and preview metadata
- package install/update/remove testing
- a future reusable ATLAS plugin template

The demo plugin is metadata-only in the first Administration preview and does
not execute plugin code yet.

## Asset Convention

- `icon.svg`: compact square plugin icon for lists and small status rows.
- `logo.svg`: wide ATLAS-branded plugin logo for Hub/Admin cards.
- `preview.svg`: 16:9 plugin preview or screenshot.
