# python-regex-patterns

## Description
This Python script demonstrates the use of regular expressions (regex) for various text processing tasks, including pattern matching, finding, replacing, and splitting strings. The script showcases examples of searching for specific patterns, such as words, digits, email addresses, IP addresses, and more.

## Installation
To run this project, you'll need to have Python installed.

## Usage
Run the script using the following command:
```sh
python regex_patterns.py
```

## Code Explanation
This script performs the following tasks using regular expressions:

- **Basic Pattern Matching:**
  - Finds all occurrences of specific patterns, such as "I", "Python", and various case-sensitive/insensitive patterns.
  
- **Character Class and Special Sequences:**
  - Searches for word characters (`\w`), non-word characters (`\W`), whitespace characters (`\s`), and digit characters (`\d`).

- **Quantifiers and Groups:**
  - Uses quantifiers like `{n}`, `{n,}`, and `{n,m}` to find patterns with specific lengths or repetitions.
  - Demonstrates the use of alternation (`|`) to match multiple patterns.

- **Boundaries and Anchors:**
  - Searches for patterns at word boundaries (`\b`), non-word boundaries (`\B`), and line/string boundaries (`^`, `$`).

- **Compiling Patterns:**
  - Compiles regex patterns for repeated use and demonstrates searching and matching within the compiled patterns.

- **Substitution and Splitting:**
  - Replaces occurrences of patterns with specified strings.
  - Splits strings based on regex patterns.

- **Advanced Pattern Matching:**
  - Extracts email addresses from text.
  - Matches and validates IP addresses.

## Output
The script prints the results of each regex operation to the console, including the matched patterns, positions, and modifications.

## License
This project is licensed under the MIT License.
