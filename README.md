# MarkdownPDFStyle-ryomashita

Style files for converting markdown to pdf with [vscode-markdown-pdf](https://github.com/yzane/vscode-markdown-pdf)

## Recommended vscode-markdwon-pdf configuration

Reference: https://github.com/yzane/vscode-markdown-pdf/blob/master/README.md#options

- [markdown-pdf.styles](https://github.com/yzane/vscode-markdown-pdf/blob/master/README.md#markdown-pdfstyles) 
  - set local path to tye css stylesheets.
  -  All `\` need to be written as `\\` (Windows).

- [arkdown-pdf.breaks](https://github.com/yzane/vscode-markdown-pdf/blob/master/README.ja.md#markdown-pdfbreaks)
  - set true (default: false).
  - enable hard_linke_breaks.

- [markdown-pdf.mermaidServer](https://github.com/yzane/vscode-markdown-pdf/blob/master/README.ja.md#markdown-pdfmermaidserver)
  - set `https://unpkg.com/mermaid@9/dist/mermaid.min.js`
  - Issue&Solution: https://github.com/yzane/vscode-markdown-pdf/issues/312
  
## Setting default style
https://www.jackjasonb.com/2021/03/22/markdown-pdf-css/
1. clone `github-markdown.css`
2. delete `.markdown-` from all selectors
3. config `vscode-markdown-pdf.styles`