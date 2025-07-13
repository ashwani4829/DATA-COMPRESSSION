# Lexical Analyzer in C

**Author:** Ashwani Dwivedi
**Intern ID:** CT04DG1794
**Company:** CODTECH IT SOLUTIONS
**Mentor:** Neela Santosh
**Domain:** C Programming
**Duration:** 4 Weeks

---

## Overview

A basic lexical analyzer in C that reads a source code file and breaks it into tokens: keywords, identifiers, operators, and numbers. All logic is written from scratch using standard C functions.

---

## Features

* Detects keywords, identifiers, numbers, and operators
* Supports multi-character tokens
* Ignores whitespace and newlines
* Uses `ungetc()` for accurate parsing

---

## Technologies Used

* C Language
* Libraries: `stdio.h`, `stdlib.h`, `string.h`, `ctype.h`

---

## File Structure

```
lexical_analyzer.c     # Lexer code  
input.c                # Sample input  
README.md              # Documentation  
```

---

## Compile and Run

```bash
gcc lexical_analyzer.c -o lexer
./lexer
```

Enter the input file name when prompted (e.g., `input.c`).

---

## Key Learnings

* Basic lexical analysis techniques
* Token classification using character-by-character scanning
* Foundations of compiler design