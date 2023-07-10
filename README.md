A single-page, one-column resume and two-page, one-column resume for software developers.

### Quick start

Get started quickly using [Overleaf](https://www.overleaf.com/latex/templates/software-engineer-resume/gqxmqsvsbdjf) template.

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex christian_baran_resume.tex
docker run --rm -i -v "$PWD":/data latex pdflatex christian_baran_two_page_resume.tex
```

### License

Format is MIT. Original template base is by Sourabh Bajaj, modifications are by Christian Baran.
