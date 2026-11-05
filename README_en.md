# SWOT Analyse with TOWS
![Format](https://img.shields.io/badge/format-HTML-blue)
![Release](https://img.shields.io/github/v/release/Chrisp-Codes/swot-tows-analyse)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
[![Deutsch](https://img.shields.io/badge/README-Deutsch-informational?style=flat-square)](README.md)

## Goal

Many SWOT templates are static, tied to accounts, or paid. This tool is a single HTML file: interactive, no sign-up, no server.  
It links the SWOT analysis with the TOWS matrix, so strengths, weaknesses, opportunities and threats can be turned into concrete strategies.

## Features

- SWOT matrix with strengths, weaknesses, opportunities and threats
- TOWS matrix (SO, WO, ST, WT) with guiding questions
- Load an example to try it out
- Save and load as JSON file
- PDF export (A4 landscape)
- Automatic backup of the draft in your own browser

## Usage

**Online:** https://chrisp-codes.github.io/swot-tows-analyse/

**Offline:** Download `index.html` and open it in your browser. No installation required.

## Structure

```
index.html   → complete application (HTML, CSS, JavaScript)
LICENSE      → MIT license
README.md    → German README
README_en.md → English README
```

There are no build steps and no dependencies. The only external library is jsPDF, which is loaded only when exporting a PDF.

## Privacy

- No server, no account, no tracking, no cookies.
- Your input stays in your own browser or in the exported JSON file.
- When exporting a PDF, jsPDF is loaded from `cdnjs.cloudflare.com`. This transmits your IP address to the CDN provider. If you want to avoid this, use your browser's print dialog instead.

## Methodology

- **SWOT analysis:** Compares internal strengths and weaknesses with external opportunities and threats.
- **TOWS matrix:** Developed by Heinz Weihrich (1982). It derives strategies from combinations of SWOT factors (SO, WO, ST, WT).

## Contributing

Bug reports and suggestions are welcome, preferably as issues. A fix or reply is not guaranteed.

## Disclaimer

The software is provided without any warranty. Use is at your own risk. The results do not replace professional advice.

## License

MIT License – free use, modification and distribution permitted. See [LICENSE](LICENSE).
