nwgeo
=====

parser for NWChem output, specifically to get geometries from an optimization.

usage: nwgeo [-h] [-a] [-o OUTPUT] [-q] input

positional arguments:
  input                 NWChem output file

optional arguments:
  -h, --help            show this help message and exit
  -a, --all             print all coordinates from optimization to output
  -o OUTPUT, --output OUTPUT
                        set output file name
  -q, --quiet           do not print friendly information
