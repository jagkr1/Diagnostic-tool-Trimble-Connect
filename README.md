# Trimble Object Access Diagnostic

Temporary diagnostic extension for testing how the Trimble Connect Workspace API can access objects loaded in the 3D viewer.

## Files

- `index.html`
- `manifest.json`
- `README.md`

## What to edit

In `manifest.json`, replace:

`https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/index.html?v=1`

with your real GitHub Pages URL.

Example:

`https://jagkr1.github.io/trimble-object-access-diagnostic/index.html?v=1`

## How to test

1. Add the extension to Trimble Connect.
2. Open a project and load the models in the 3D viewer.
3. Select one object in the model.
4. Open the diagnostic extension.
5. Press `Run all tests`.
6. Press `Export diagnostic JSON`.
7. Send the exported JSON back for analysis.

## Important

This is not the final attribute checker. It is only used to find which API method works for accessing loaded objects and properties.
