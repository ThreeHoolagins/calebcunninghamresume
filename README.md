# Caleb Cunningham — Resume

LaTeX resume built with [Awesome-CV](https://github.com/posquit0/Awesome-CV).

## Latest PDF

The latest resume is always available at:

```
https://github.com/ThreeHoolagins/calebcunninghamresume/releases/latest/download/caleb_cunningham_resume.pdf
```

## Versioned Artifacts

Every push to `master` triggers a GitHub Actions workflow that:

1. Compiles `resume.tex` with XeLaTeX
2. Creates a new release with an incrementing tag (`v1`, `v2`, `v3`...)
3. Uploads the PDF as a release asset

All previous releases remain accessible from the [Releases page](https://github.com/ThreeHoolagins/calebcunninghamresume/releases). Each version's PDF can be downloaded individually from its release.

## Local Build

```bash
xelatex resume.tex
```

Requires XeLaTeX (TeX Live recommended).
