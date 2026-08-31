# ATLAS Plugin Repository Demo

Public demo repository for testing the ATLAS plugin repository workflow.

## Repository URL

Use this URL in ATLAS Administration:

```text
https://raw.githubusercontent.com/rockbaer2007/atlas-plugin-repository-demo/main/repository.json
```

## Contents

```text
repository.json
plugins/
  simple-file-editor/
    atlas-plugin.json
    simple-file-editor.atlas-plugin.json
    icon.svg
    preview.svg
    README.md
```

## Purpose

This repository is the first public reference for:

- the `repository.json` catalog format
- plugin icon and preview metadata
- package install/update/remove testing
- a future reusable ATLAS plugin template

The demo plugin is metadata-only in the first Administration preview and does
not execute plugin code yet.
