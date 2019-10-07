I3-Data-Shuffler
================
Intentionally simplistic [I3](https://github.com/icasr/I3) demo.

This app takes spreadsheet data (in CSV, XLSX or [pretty much anything else](https://docs.sheetjs.com/#file-formats)) and randomly sorts or deletes data.


Command Line Interface
======================

```
Usage: shuffle --input=inputFile --output=outputFile [--order] [--delete-percent=number]

Options:
  -V, --version                     output the version number
  -i, --input <path>                Specify the input file
  -o, --output <path>               Specify the output file
  -r, --order                       Randomize the output order (ignores the first line which is assumed to be the headers
  -d, --delete-percentage <number>  Delete the given percentage of lines, randomly
  -s, --sheet <name>                Which worksheet to use within the data, if none specified the first is used
  -v, --verbose                     Be verbose - use multiple to increase verbosity
  -h, --help                        output usage information
```
