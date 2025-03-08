# Bangla Text Normalization (TN)



## Directory Structure
```
.
├── Dataset/    # Semiotic class test cases
└── *.csv       # Linguistic resource files
```

## Linguistic Resources
Resource files in CSV format:
- `Symbol.csv` - Common symbols and their pronunciations
- `Abbreviation.csv` - Standard abbreviations
- `Acronym.csv` - Common acronyms
- `Ordinal.csv` - Ordinal number expressions

## Test Cases
The `Dataset/` directory contains 11 semiotic classes with extensive test cases:

| Semiotic Class | Test Cases |
|----------------|------------|
| ABBREVIATION   | 101        |
| ACRONYM        | 99         |
| CARDINAL       | 214        |
| DATE           | 168        |
| DECIMAL        | 113        |
| DIGIT          | 127        |
| ELECTRONIC     | 101        |
| MONEY          | 139        |
| ORDINAL        | 79         |
| SYMBOL         | 123        |
| TIME          | 107        |

## Total Coverage
1,371 test cases across all semiotic classes
