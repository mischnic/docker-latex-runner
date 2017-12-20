# Docker image for compiling latex documents

*Doensn't contain a complete TeX Live distribution for size reasons*


For installing missing/more packages:
```Dockerfile
FROM mischnic/texlive-runner

RUN tlmgr install your-package

...
```