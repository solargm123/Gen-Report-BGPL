# Solar Engineering Tools Center — Project Summary

## Project purpose
A single Main page (`index.html`) acts as the entry point for the current Solar Engineering report tools.

## Current tools
1. **Troubleshooting Report**
   - Fill project and incident information
   - Before / After photo sections
   - Maximum 2 photos per section
   - Comment under each photo
   - EPC / BGPL signature support
   - Export PDF
   - Export Word
   - Main button returns to `index.html`

2. **Solar Survey Report Generator**
   - Solar site survey data entry
   - Photo/report workflow
   - Preview
   - Export Word (.docx)
   - Export PDF
   - Main button returns to `index.html`

## Main page
- `index.html` is the Main / Home page.
- Minimal Ambient UI
- Bai Jamjuree UI font
- Light / Dark mode
- ASK logo removed from the Index page as requested.
- Two tool cards link directly to the corresponding HTML tools.

## Final file structure
Solar_Engineering_Tools_Main/
- index.html
- Troubleshooting_Report_Form.html
- Solar_Survey_Report_Generator.html

## Navigation
- Main → Troubleshooting Report
- Main → Solar Survey Report Generator
- Troubleshooting Report → Main
- Solar Survey Report Generator → Main

## Working files
- Main: `index.html`
- Troubleshooting: `Troubleshooting_Report_Form.html`
- Solar Survey: `Solar_Survey_Report_Generator.html`

## Recommended next development
- Keep `index.html` as the permanent application entry point.
- Add future tools as new cards on the Main page.
- Keep tool files independent so updates to one tool do not affect the others.
- When deploying to GitHub Pages, upload all three HTML files into the same directory.
