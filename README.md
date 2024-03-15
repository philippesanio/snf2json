# SNF2JSON

This tool is a simple file converter that takes a Sniffles (SNF) file and converts it into a JSON like object.
The purpose of this converter is to make it easier to work with the Sniffles file format which is consists of multiple 
pickled objects. If not converted they can only be loaded by importing the Sniffles package.

To preserve the original data structure, the pickled objects are converted into a JSON like object structure, which can
easily be loaded into a Python dictionary.

Installation:
```bash
pip install snf2json
```
Usage:

For compression use the .gz extension in the output filename. 
```bash
snf2json <sample.snf> <new_sample.snfj.gz>
```
or
```bash
snf2json <sample.snf> <new_sample.snfj>
```
