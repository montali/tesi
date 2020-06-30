# Per andare direttamente al PDF della tesi, [clicca qui.](https://github.com/montali/tesi/blob/master/LaTeXi/tesi.pdf)

# Per andare direttamente alla presentazione, [clicca qui.](https://github.com/montali/tesi/blob/master/Presentazione.pdf)

Tesi di primo livello, Ingegneria dei Sistemi Informativi @UniPR. Realizzazione di un bot per il triage dei pazienti in ospedale.

## Notes

Beware: to build LaTeX files using the package mint, you've gotta add `-shell-escape` to the build options. For example, in VSCode's settings, add:

```json
  "latex-workshop.latex.tools": [
    {
      "name": "latexmk",
      "command": "latexmk",
      "args": [
        "-synctex=1",
        "-interaction=nonstopmode",
        "-shell-escape",
        "-file-line-error",
        "-pdf",
        "-outdir=%OUTDIR%",
        "%DOC%"
      ],
      "env": {}
    },
```
