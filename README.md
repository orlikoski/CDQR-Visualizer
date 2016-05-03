## NAME
CDQR Visualizer — Cold Disk Quick Response Visualizer by Alan Orlikoski

## What is CDQR?
The CDQR Visualization tool converts the CDQR Reports into a format that can be visualized by the TimeFlow application.

## What's New
It is currently in Beta and works best on EVTX logs in the "Event Log Report.csv"

## Fixes

## Known Bugs

## Important Notes

## SYNOPSIS
Windows 64-bit binary
```
usage: cdqr2tf.exe [-h] [-v] src_file
```
Python 3.4
```
usage: cdqr2tf.py [-h] [-v] src_file  
```

## DESCRIPTION
This program converts the CDQR (https://github.com/rough007/CDQR) Reports to Timeflow format in addition to various parsing enhancements of the data.  Here is Timeflow Wiki (https://github.com/FlowingMedia/TimeFlow/wiki).  I have included a compiled version of Timeflow in the "dep" folder.  This version has some slight tweaks to the original version that make it with with CDQR Visualization tool.  Download "dep\TimeFlow_custom.7z", extract the contents to a folder and execute the "timeflow_64bit_bundled_jre.exe".


## ARGUMENTS
* `src_file` — Source File location: "Y:\Case\Tag009\Reports\Event Log Report.csv"

## OPTIONS
* `-h` , `--help` — Show this help message and exit.
* `-v : --version` — Show version

## PARSER LIST

## DEPENDENCIES
1. 64-bit Windows Operating System 
2. Timeflow Wiki (https://github.com/FlowingMedia/TimeFlow/wiki)
3. [Python v3.4](https://www.python.org/downloads/release/python-340/) (if using cdqr2tf.py source code)

## EXAMPLES
```
cdqr2tf.exe "Reports\Event Log Report.csv"
```
```
cdqr2tf.py "Reports\Event Log Report.csv"
```

## AUTHOR
* [Alan Orlikoski](https://github.com/rough007)