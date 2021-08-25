# PoWSB-distribution
Python script to create pie graphics of PoW/PoB/PoS blocks distribution in Slimcoin.

Usage: 

python PoWSB-distribution.py [-h] [-s] beginning_date ending_date


Positional arguments:

beginning_date  - the date to start from, format yyyy-mm-dd

ending_date     - the date to end with, format yyyy-mm-dd


Optional arguments:

-h, --help      show this help message and exit

-s, --sum       sum rewards per block type

With the -s flag one can see the rewards distribution in the chosen period. Without that flag the graphic would report the number of the blocks distribution per type.

The data are taken from the file data.csv which is also present in this repository.

The data.csv file contains the blocks up to 2524262 (2021-08-13 21:13:35 UTC) at the moment. So chose your desired time span consequently. 
