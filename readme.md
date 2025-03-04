# TacTile

## Description
TacTile is an digital musical instrument that makes cool sounds. It uses a conductive fabric sensor matrix with a middle layer of velostat connected to a Teensy board to detect touch and play musical notes based on the location of touch.

## Python Version
Please make sure you run this in Python 3.12.7

## Initial Setup
To create the project, run the command 
```bash
python -m venv .venv
```

Initialise the venv by entering
```bash
source .venv/bin/activate
```

Install all dependencies using
```bash
pip install -r requirements.txt
```

Update by using
```bash
pip install --upgrade pip
```

## Using the Instrument
To run the project, run the following file using:

```bash
python sensor_display_trial.py

or

python sensor_display.py
```