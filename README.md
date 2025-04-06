AFLL Mini Project - Grammar & Parser for Python Constructs
This project, developed as part of the Automata Formal Language and Logic (UE23CS242A) course at PES University, demonstrates the application of context-free grammar (CFG) and lexical parsing using Python to describe and validate core constructs of a programming language.

Team Members
M Niranjan - PES2UG23CS308

Keerthan P.V - PES2UG23CS272

Objective
To describe and implement grammar rules for basic constructs of a programming language and create a lexer and parser using PLY (Python Lex-Yacc).

Key Features
Defined context-free grammars for:

Function declarations

While loops

Datatype declarations

Conditional statements (if-elif-else)

Array declarations

Implemented a Python parser using PLY, capable of handling:

if-else, for, switch-case, function_def, and more

Lexical analysis for Python-like tokens (identifiers, numbers, keywords, etc.)

Parsing test cases to validate the grammar implementation

Technologies Used
Language: Python

Libraries: PLY (Python Lex-Yacc)

How to Run
bash
Copy
Edit
python afll_parser.py
Make sure ply is installed:

bash
Copy
Edit
pip install ply
Sample Test Cases
The program parses several code snippets including:

python
Copy
Edit
for i in range(10) {
    break;
}

if (x < y) {
    something();
} else {
    something_else();
}

def function():
    return 0;
Output
Displays whether the parsing was successful for each input based on the defined grammar rules.
