## smasher-stats
Start of a python smash statistics project

Welcome to SmasherStats. This is super basic for now.

SmasherStats is written in python 3.5, so make sure you have that installed before running.

Download python 3.5 here: https://www.python.org/downloads/

The default setting is to return a smasher's Melee results for the current year only.

## How to run the program

    Usage: python smasherstats.py [options]

    Get tournament results of specified smasher

    Options:
      -h --help                show this help message and exit
      -s --smasher <tag>       The tag of the smasher you want results for
      -i --input_file <path>   Path to input file where tags are stored
      -o --output_file <path>  Path to output file where results are put
      -t --threshold <place>   Tournaments where the smasher placed worse will have
                               their names displayed
      -y --year <year>         Specified year used in conjunction with -c
      -c --comparison <str>    What comparison string to use when comparing the date to -y
      -g --game <game>         Specified game to get tournament results for
                               [default: Melee]
Possible comparison strings:
 - ==
 - !=
 - <
 - >
 - <=
 - >=