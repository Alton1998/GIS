# GIS
## Overview 
The aim of this project is to create a model to perform segmentation of buildings using a drone image on a map
## Pre-requisite
1. Install Pixi
```
powershell -ExecutionPolicy Bypass -c "irm -useb https://pixi.sh/install.ps1 | iex"
```
## Setup

```
pixi install
```
## Workspace Setup

```
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
pip pip install -r workspace/requirements.txt
```

## Notes
The notebook under workspace contains the script for data preparation of GeoTiff and Geojson data.