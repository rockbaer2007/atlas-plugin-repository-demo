# ATLAS Plugin Repository Demo

Public demo repository for testing the ATLAS plugin repository workflow.

## Repository URL

Use this URL in ATLAS Administration:

```text
https://raw.githubusercontent.com/rockbaer2007/atlas-plugin-repository-demo/main/repository.json
```

Test the Home Assistant add-on repository handoff:

[![Open your Home Assistant instance and add this repository.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Frockbaer2007%2Fatlas-plugin-repository-demo)

The button opens the My Home Assistant handoff page with the repository URL
pre-filled. It is meant for testing the handoff flow; ATLAS plugin installation
continues to use the `repository.json` URL above.

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
