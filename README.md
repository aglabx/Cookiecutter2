# Cookiecutter2: fast and parallel raw reads extraction and filtering using kmers

Parallel and enhanced implementation of the previously published Cookiecutter tool (https://www.biorxiv.org/content/10.1101/024679v1).

## Installation

Clone from github and then compile:

```
git clone
cd Cookiecutter2
make
```

## Usage

```
cookiecutter2.py -1 data_1.fastq -2 data_2.fastq -o outpit_prefix -m split -t 32 --hits 3 --library library.kmers
```

- **m**, **mode**: split, extract or remove;
- **t**, **threads**: a number of threads;


## Usage examples

## Known issues

## Citation

## Copyright Notice

Cookiecutter was written by Aleksey Komissarov (ad3002@gmail.com) Copyright (c) 2019-2020 Aleksey Komissarov.

This code is licensed under the same GNU General Public License v2 (or at your option, any later version). See http://www.gnu.org/licenses/gpl.html
