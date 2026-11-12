# ComfyUI Workflow Reader

Read-only viewer for ComfyUI workflows. Runs entirely in the browser: no ComfyUI, no Python, no server. Files never leave your machine.

**Open it:** https://dchatel.github.io/comfyui_workflow_reader/

Or download `index.html` and open it locally.

## Supported inputs

- `.json` — UI workflow or API prompt (API prompts get an automatic layout)
- `.png` — `workflow` / `prompt` text chunks
- `.webp` — ComfyUI EXIF metadata
- `.mp4` / `.mov` — container metadata (native ComfyUI and VideoHelperSuite)
- anything else (`.webm`, `.mkv`…) — raw scan for an embedded workflow

Drop a file on the page, use **Ouvrir…**, or paste (Ctrl+V).

## Usage

- Wheel to zoom, drag to pan, `F` to fit.
- Click a widget value to copy it; click a node for the side panel with full values and connections.
- Double-click a subgraph node (or ⤵) to enter it; `Esc` / breadcrumb to go back.
- Search with `/` or Ctrl+F, Enter for next match.
- **Copier JSON** / **.json** extracts the workflow from an image or video.
