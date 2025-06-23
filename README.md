## How to generate .pdf from .tex

Use `pdflatext ./resume.pdf` command to convert tex file to pdf format.

### Troubleshooting
If you face any error like `! LaTeX Error: File 'fullpage.sty' not found.`

Run command `sudo apt-get install texlive-latex-extra --no-install-recommends` and try again.
This will download all the extras that are needed for latex package. however, this package is quite big (north of 300MB), so `--no-install-recommends` can be added to reduce the package size


