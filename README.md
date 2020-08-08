### Current Resume

My current resume.

[Resume - PDF](https://github.com/benkant/resume/raw/master/ben_giles_resume.pdf)

For a full curriculum vitae see [LinkedIn](https://www.linkedin.com/in/ben-giles-0xdeadbeef)

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex ben_giles_resume.tex
```

### License

MIT

Forked from https://github.com/sb2nov/resume
