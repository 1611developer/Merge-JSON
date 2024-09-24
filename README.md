# Merge-JSON
Combine two JSON files into one

A simple Python application that combines two JSON files into one. This tool reads two input JSON files, merges their contents, and outputs the combined data to a new JSON file.

## Features

- Combines two JSON files.
- Handles key conflicts by prioritizing the second file's values.
- Outputs the combined JSON in a human-readable format.

## Requirements

- Python 3.12 or later

## Installation

1. Clone the repository or download the source code.
2. Ensure you have Python 3.12 installed on your machine.

## Usage

Run the script from the command line with the following syntax:

```bash
python combine_json.py <file1.json> <file2.json> <output.json>

---------------------------------------------------------------
#Example Inputs


file1.json

{
    "name": "Alice",
    "age": 30,
    "city": "New York"
}


file2.json

{
    "name": "Bob",
    "age": 25,
    "country": "USA"
}


#Example Expected Output

{
    "name": "Bob",
    "age": 25,
    "city": "New York",
    "country": "USA"
}
