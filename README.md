# latex_report_template
Latex report template that leverages a dockerfile, can be run in vscode or github.dev


For vscode, use.

```
chmod +x ./latexdockercmd.sh
./latexdockercmd.sh /bin/sh -c "pdflatex lwarp_template.tex && pdflatex lwarp_template.tex
"

chmod +x ./moveFiles.sh
./moveFiles.sh
```