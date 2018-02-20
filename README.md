# Stuff I've done 
```pip install gfm
jupyter lab --NotebookApp.nbserver_extensions="{'jubo.hello':True}" 
 python jubo/convert.py && bokeh serve outputs.ipynb.py         
```


# xkcd_ext

A JupyterLab extension.


## Prerequisites

* JupyterLab

## Installation

```bash
jupyter labextension install xkcd_ext
```

## Development

For a development install (requires npm version 4 or later), do the following in the repository directory:

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

