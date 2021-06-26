# PoWSB-distribution
Python script to create graphics of PoW/PoB/PoS blocks distribution in Slimcoin

usage: python PoWSB-distribution.py [-h] [-s] beginning_date ending_date

positional arguments:
  beginning_date  - the date to start from, format yyyy-mm-dd
  ending_date     - the date to end with, format yyyy-mm-dd

optional arguments:
  -h, --help      show this help message and exit
  -s, --sum       sum rewards per block type

With the -s flag one can see the rewards distribution in the chosen period. Without that flag the graphic would report the number of the blocks distribution per type.
The data are taken from the file data.csv which is also present in this repository.

The data.csv file contains only the blocks from 2021-02-10 to 2021-05-31 at the moment. So chose your desired time span consequently. 
