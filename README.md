# jupyterlab_xkcd_tutorial

Show a random xkcd.com comic in a JupyterLab panel


## Prerequisites

* JupyterLab

## Installation

```bash
jupyter labextension install @oscar6echo/xkcd-extension
```

## Development

For a dev install (requires npm version>=4 and <=9), do the following in the repo directory:

```bash
npm install
npm run build
jupyter labextension link .
```

To rebuild the package and the JupyterLab app:

```bash
npm run build
jupyter lab build
```

