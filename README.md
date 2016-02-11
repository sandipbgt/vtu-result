# vtu-result

A  Python script to export results of all students from [results.vtu.ac.in](http://results.vtu.ac.in) to Excel file format.

## Installation
```sh
$ git clone https://github.com/sandipbgt/vtu-result.git
$ cd vtu-result
$ pip install -r requirements.txt
```
## Usage
```sh
$ python3 app.py --college-code 1st --branch cs --year 14 --usn-from 000 --usn-to 100 --file results_cs
```

`--college-code or -c`: college code. eg: 1st

`--branch or -b`: branch of student either cs, or is. eg: cs

`--year or -y`: year in two digit. eg: 14

`--usn-from or -uf`: starting usn number in three digit number. eg: 000

`--usn-to or -ut`: ending usn number in three digit number. eg: 100

`--file or -f`: name of the file to be created either relative or abolute path eg: results_cs


# Contributing
Feel free to submit a pull request or an issue!
