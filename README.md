# SampleRepo
### Boston University
### Author: Katia Bulekova
This repository contains a few basic Python and R scripts, plus unit tests.

## Scripts

The scripts live in `./scripts`:


- `string_reverse.py`: reverses a string
- `is_even.py`: checks if an integer is even
- `add_numbers.R`: adds two numbers
- `string_reverse.R`: reverses text
- `add_numbers.py`: adds two numbers
- `is_even.R`: checks if an integer is even


## How to run the scripts

From the repository root, execute:

```bash
python scripts/add_numbers.py 2 3
python scripts/string_reverse.py hello
python scripts/is_even.py 8
```

To run the R versions:

```bash
Rscript scripts/add_numbers.R 22 33
Rscript scripts/string_reverse.R hello
Rscript scripts/is_even.R 88
```

## Run unit tests

```bash
python -m unittest discover -s tests -q
```
