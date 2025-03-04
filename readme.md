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
To run the project, run one of the two python files below by pasting the following commands into terminal:
```bash
python sensor_display_trial.py
```
or
```bash
python sensor_display.py
```
Depending on the update status of the code, one or the other of the two commands above might give you better results. Try both.

System level commands for v4.2 (latest update as of 3 March 2025):

| Action                      | Key   |
| --------------------------- | ----- |
| Panic Button/stop all notes | P     |
| Octave DOWN/UP              | Z / X |
| Transpose DOWN/UP           | C / V |
| Drop D Tuning               | D     |
| Perfect Fourths Tuning      | F     |
| Cycle through scale modes   | S     |
| Tuning panic button (revert to typical guitar tuning)                       | A     |
| Quit Program                | Q     |


[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg