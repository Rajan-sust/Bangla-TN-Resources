# Bangla Text Normalization (TN)

## Resources
- CSV format linguistic resources:
    - Symbols (`Symbol.csv`)
    - Abbreviations (`Abbreviation.csv`)
    - Acronyms (`Acronym.csv`)
    - Ordinal numbers (`Ordinal.csv`)

## Test Cases
Test cases for 11 semiotic classes available in `Dataset/` directory:

| Class         | Count |
|--------------|--------|
| ABBREVIATION | 101    |
| ACRONYM      | 99     |
| CARDINAL     | 214    |
| DATE         | 79     |
| DECIMAL      | 113    |
| DIGIT        | 10     |
| ELECTRONIC   | 8      |
| MONEY        | 51     |
| ORDINAL      | 79     |
| SYMBOL       | 123    |
| TIME         | 107    |

## Structure
```
.
├── Dataset/    # Test cases
└── *.csv       # Resource files
```
