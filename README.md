Sanger Chromatogram Viewer & FASTA Exporter

A single-file, browser-based tool for viewing Sanger sequencing chromatograms
from `.ab1` (ABIF) files and exporting the called sequence as FASTA.

Features

- Parses `.ab1` (ABIF) files entirely client-side — no upload, no server
- Renders the four fluorescence traces (A/C/G/T) on an HTML5 canvas
- Displays base calls with 10-bp numbering along the top
- Hover over the chromatogram to see the nucleotide number and base
- Drag to select a range; the selected subsequence is shown and can be copied
- Two-axis scrolling (buttons + auto-scroll when dragging to the edges)
- Adjustable peak height and peak width (horizontal spacing)
- Edit the sequence and download it as a `.fasta` file

Usage

1. Open `index.html` in any modern browser.
2. Load a `.ab1` file.
3. Drag over the chromatogram to select a region, then click **Copy Range**.
4. Edit the sequence if needed and click **Download FASTA**.

Notes

- All processing happens locally in the browser; no data leaves your machine.
- Tested with standard ABI sequencer `.ab1` files.

Credits

Developed by **Dr. Abbas Soleimani-Delfan**.
