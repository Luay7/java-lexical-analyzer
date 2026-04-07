# Compiler Front-End Project in Java

This project was developed for a Compiler Construction course. It demonstrates two important phases of a compiler front-end: lexical analysis and syntax analysis.

## Project Overview
The project is divided into two phases:

### Phase 1: Lexical Analyzer
This phase implements a lexical analyzer in Java. It reads source code from an input file, identifies lexemes, classifies them into tokens, and writes the results to an output file.

### Phase 2: Recursive Descent Predictive Parser
This phase implements a recursive descent predictive parser in Java. It reads arithmetic expressions from an input file and checks whether each expression follows the predefined grammar rules. The parser prints either `Correct Syntax` or `Syntax Error`.

## Concepts Covered
- Finite Automata
- Lexical Analysis
- Tokenization
- Context-Free Grammar (CFG)
- Recursive Descent Parsing
- Syntax Validation

## Project Structure
- `phase1-lexical-analyzer/` — lexical analyzer implementation
- `phase2-recursive-descent-parser/` — recursive descent parser implementation

## Technologies Used
- Java
- File I/O
- PushbackReader
- BufferedReader
- BufferedWriter
- StringTokenizer

## Purpose
The purpose of this project is to apply compiler construction concepts in practice by implementing two core front-end components: a lexical analyzer and a syntax parser.

## Notes
- Phase 1 focuses on identifying tokens from source code
- Phase 2 focuses on validating the syntax of arithmetic expressions
- Each phase has its own input files, source code, and documentation
