## PyGuiTemp
An empty template for making a PyQT4 GUI in python<br>

## Requirements
Download the PyQT4 wheel for your device and install with pip<br>
```
https://pypi.org/simple/pyqt4-windows-whl/
```

## Usage
Set up ENVIRONMENT VARIABLES for the PyQT4 dir<br>
Every time you make changes to the design.ui, run the following command to update the design.py<br>
```
pyuic4 design.ui -o design.py
```
Run GUI with:<br>
```
python main.py
```
