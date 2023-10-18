# Robust JSON Parser

A Python utility for parsing JSON files that may contain errors or malformed segments. Instead of stopping at the first error, this parser tries to recover and retrieve as many valid JSON objects as possible.

## Features

- Parses entire JSON files, even if they contain errors.
- Skips over malformed segments to retrieve valid JSON objects.
- Outputs the successfully parsed JSON objects in a formatted manner.

## Usage

To use the Robust JSON Parser, execute the script with the path to the JSON file you wish to parse:

```bash
python json_parser.py <path_to_your_json_file>
