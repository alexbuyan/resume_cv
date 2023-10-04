# Build Docker image

```
docker build -t latex .
```

# Build .tex files

```
docker run --rm -i -v "$PWD":/data latex pdflatex alexander_byantuev.tex
docker run --rm -i -v "$PWD":/data latex pdflatex alexander_buyantuev_ml.tex
docker run --rm -i -v "$PWD":/data latex pdflatex alexander_buyantuev_rus.tex
docker run --rm -i -v "$PWD":/data latex pdflatex alexander_buyantuev_ml_rus.tex
```
