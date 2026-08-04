# voltaris

> A built, static snapshot of the Voltaris team website — compiled output rather than source.

<!-- badges -->
![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white)

![last commit](https://img.shields.io/github/last-commit/adzetto/voltaris?style=flat-square&color=informational) ![repo size](https://img.shields.io/github/repo-size/adzetto/voltaris?style=flat-square&color=informational) ![top language](https://img.shields.io/github/languages/top/adzetto/voltaris?style=flat-square) ![language count](https://img.shields.io/github/languages/count/adzetto/voltaris?style=flat-square)

---

## What this is

A **built snapshot** of the Voltaris team website: hashed JavaScript bundles, an
asset manifest, images and 3D model binaries. There is no `src/` here and no
build step, because this is the output of one.

Editing files in this repository by hand works exactly once. The next build from
source overwrites them.

## Where the source is

- **[voltaris-website-white](https://github.com/adzetto/voltaris-website-white)** — the React source, Docker setup and deployment scripts

Make changes there.

## What is in the tree

| Path | Contents |
|---|---|
| `3D/`, `models/` | glTF and Draco-compressed vehicle models |
| `static/` | Compiled JS, CSS and media with content hashes |
| `team/`, `sponsors/` | Photographs and logos |
| `index.html`, `404.html` | Entry points |

## About Voltaris

An electric vehicle student team at İzmir Institute of Technology. The
engineering repositories are separate from this one:
[`AKS`](https://github.com/adzetto/AKS),
[`dashboard`](https://github.com/adzetto/dashboard),
[`motor_driver`](https://github.com/adzetto/motor_driver),
[`voltaris-hotspot`](https://github.com/adzetto/voltaris-hotspot).

## Repository layout

```text
voltaris/
├── .idea/
├── 3D/
├── models/
├── sponsors/
├── static/
├── team/
├── 404.html
├── CleanTechnicalAnimation.gif
├── asset-manifest.json
├── favicon.ico
├── favicon.svg
├── index.html
├── logo192.png
├── logo512.png
```

---

**112** tracked files · **12.3 MB** · **1** languages · last pushed **2025-04-25**
