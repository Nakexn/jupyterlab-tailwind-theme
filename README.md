# JupyterLab Tailwind theme

A JupyterLab theme extension inspired by [Tailwind CSS](https://tailwindcss.com/).

```
  ✨ With support for new release of JupyterLab (>= v2.0)
```

## Light theme
![](style/images/jupyterlab-tailwind-launcher-screen-light.png)
</br>
</br>
![](style/images/jupyterlab-tailwind-notebook-example-light.png)
</br>
</br>
## Dark theme
![](style/images/jupyterlab-tailwind-launcher-screen-dark.png)
</br>
</br>
![](style/images/jupyterlab-tailwind-notebook-example-dark.png)
</br>
</br>

Tip: To display matplotlib charts in dark mode execute `plt.style.use('dark_background')` after importing the package
</br>
![](style/images/matplotlib-tip-dark.png)
</br>
</br>
</br>

## Prerequisites

* JupyterLab

## Installation

```bash
jupyter labextension install jupyterlab-tailwind-theme
```

## Development

For a development install (requires npm version 4 or later), do the following in the repository directory:

```bash
npm install
jupyter labextension link .
```

To rebuild the package and the JupyterLab app:

```bash
npm run build
jupyter lab build
```
