# Matching Symbols

## Problem
- Create a program that can read a string and return
  - True:
    - There are no grouping symbols 
    - For each opening grouping symbol, there is a closing grouping symbol
  - False:
    - For each opening grouping symbol, there is atleast one without a matching closing symbol
    - If there is a closing grouping symbol before an opening grouping symbol
- Grouping symbols:
  - Parentheses: ( )
  - Braces: { }
  - Brackets: [ ]
- Examples
  - True
    - ()(()){([()])}
    - ((()(()){([()])}))
  - False
    - )(()){([()])}
    - ({[])}
    - (
