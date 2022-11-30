# PyCal

A very simple Python PDF Calendar program forked from https://github.com/adc-code/PyCal.

I modified it to add a recurring chore schedule to the day boxes.

## Usage

The month, year, parameter and output file are specified are command line arguments.  That is for a monthly calendar: 

> python MakeCal.py [YEAR] [MONTH] [PARAMETER FILE] [OUTPUT FILE]

or for a yearly calendar:

> python MakeCal.py [YEAR] [PARAMETER FILE] [OUTPUT FILE]

for example:

> python MakeCal.py 2020 5 params.yaml MonthMay.pdf

> python MakeCal.py 2020 params.yaml Year2020.pdf

> python MakeCal.py 2023 7 SampleYamlFiles/MonthBoxedLandsChores.yaml cal_jul.pdf 