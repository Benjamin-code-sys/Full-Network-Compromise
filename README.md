# Full Lab Report — `report.ctb`

> ⚠️ **Lab-only:**  
> &nbsp;&nbsp;&nbsp;&nbsp;This `.ctb` is a full report of a lab engagement I performed on systems I own.  
> &nbsp;&nbsp;&nbsp;&nbsp;Do **not** use techniques in this file against systems you do not own or have written permission to test.

---

## What this file is
- &nbsp;&nbsp;&nbsp;&nbsp;`report.ctb` — CherryTree database with the complete lab notebook.  
- &nbsp;&nbsp;&nbsp;&nbsp;Contains reconnaissance, commands run, screenshots, timelines, and findings.  
- &nbsp;&nbsp;&nbsp;&nbsp;Sanitized where appropriate for public hosting.

---

## Quick verification
- &nbsp;&nbsp;&nbsp;&nbsp;Open `report.ctb` in CherryTree to view structured notes.  
- &nbsp;&nbsp;&nbsp;&nbsp;If you prefer not to install CherryTree, see **Alternative: View** below.

---

## How to open the file (install CherryTree)

### Windows
- &nbsp;&nbsp;&nbsp;&nbsp;Download the CherryTree installer or portable ZIP from official sources.  
- &nbsp;&nbsp;&nbsp;&nbsp;Run installer or unzip portable archive.  
- &nbsp;&nbsp;&nbsp;&nbsp;Launch CherryTree and use **File → Open** to load `report.ctb`.

### Ubuntu / Debian / Linux
- &nbsp;&nbsp;&nbsp;&nbsp;Option A (snap): `sudo snap install cherrytree`  
- &nbsp;&nbsp;&nbsp;&nbsp;Option B (apt): `sudo apt update && sudo apt install cherrytree`  
- &nbsp;&nbsp;&nbsp;&nbsp;If using snap and external drives: `sudo snap connect cherrytree:removable-media`  
- &nbsp;&nbsp;&nbsp;&nbsp;Open CherryTree and use **File → Open**.

### macOS
- &nbsp;&nbsp;&nbsp;&nbsp;If you use Homebrew: `brew install cherrytree`  
- &nbsp;&nbsp;&nbsp;&nbsp;If build issues occur, follow upstream build-from-source notes.  
- &nbsp;&nbsp;&nbsp;&nbsp;Open CherryTree and use **File → Open**.

---

## Opening tips inside CherryTree
- &nbsp;&nbsp;&nbsp;&nbsp;Use the left node tree to navigate sections (recon, escalation, artifacts).  
- &nbsp;&nbsp;&nbsp;&nbsp;Right-click nodes to export single nodes to HTML or text.  
- &nbsp;&nbsp;&nbsp;&nbsp;Use **File → Export** to create HTML or plain text versions.

---

## Alternative: view without installing
- &nbsp;&nbsp;&nbsp;&nbsp;Export `report.ctb` to HTML from CherryTree: **File → Export → HTML (single file)**.  
- &nbsp;&nbsp;&nbsp;&nbsp;Open exported `report.html` in any browser.  
- &nbsp;&nbsp;&nbsp;&nbsp;Convert HTML to Markdown with `pandoc` if you want `.md`:  
```bash
pandoc -f html -t gfm -o report.md report.html
