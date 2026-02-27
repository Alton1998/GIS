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

## Examples
<img width="1520" height="788" alt="building_car_detect" src="https://github.com/user-attachments/assets/fc20459e-0a5b-4a56-91f2-f36798897754" />
<img width="1523" height="777" alt="building detect" src="https://github.com/user-attachments/assets/bcd06980-f580-4970-ad5d-90b93f1c5f43" />
<img width="1262" height="607" alt="image" src="https://github.com/user-attachments/assets/ee3ee0b8-4574-41ae-9bab-db59f534089f" />
<img src="https://github.com/user-attachments/assets/bc97c0ca-58fd-4873-8850-d268f23fe713" width="600">



