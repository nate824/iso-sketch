# Iso Sketch — pipe isometric drawing tool

**Live:** https://nate824.github.io/iso-sketch/

Draw piping isometrics point to point on a 30° grid, then turn them into an interactive 3D weld map.

- **Draw:** click a point, move, click: lines snap to N / S / E / W / UP / DOWN (or lock a direction; type a number for an exact length). Click a bend or a point along a leg to branch off (a tee in 3D).
- **Weld:** click a line to place a weld; balloons number with the flow and can be dragged anywhere.
- **Ends:** wave (iso stops, line continues), wave + EXISTING, EOL cap, or plain.
- **Cross:** break the line that runs behind at a crossing.
- **Create 3D iso:** pick pipe size and carbon/stainless, and the 3D model builds right in the page; attach inspection photos named `w01_1_aswelded.jpg`, `w01_2_penetrant.jpg`, `w01_3_developed.jpg` … and download the result as one HTML file.
- Exports a Python build script for a PDF weld map (needs the `weldmap.py` library, not included here).

Your drawing is kept in your browser only. Single HTML file, no server.
