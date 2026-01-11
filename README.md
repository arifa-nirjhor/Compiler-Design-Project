# **MiniLang – A Mini Programming Language using Flex & Bison**
MiniLang is a simple educational programming language developed using **Flex** and **Bison** to demonstrate the basic concepts of compiler design. The project implements lexical analysis, syntax analysis, semantic actions, and pattern matching in a single integrated system.



**Project Features**
* Variable assignment and storage
* Arithmetic expression evaluation
* Conditional statements (`if-else`)
* Looping with `while`
* Pattern matching for:

  * Number validation
  * Name validation
* Error detection and reporting
* Simple symbol table implementation



**Technologies Used**
* Language
* Flex (Lexical Analyzer Generator)
* Bison (Parser Generator)



**Project Structure**
* `minilang.l` → Lexical analyzer (token definitions using regular expressions)
* `minilang.y` → Syntax analyzer (grammar rules and semantic actions)
* `minilang.tab.c / .h` → Generated parser files
* `lex.yy.c` → Generated lexer file



**How It Works**
1. Lexical Analysis:
   Flex scans the input program and converts it into tokens such as identifiers, numbers, keywords, and operators.

2. Syntax Analysis:
   Bison checks whether the token sequence follows the grammar rules of MiniLang.

3. Semantic Processing:
   * Evaluates expressions
   * Stores and retrieves variable values
   * Executes control statements
   * Validates input strings

4. Output Generation:
   The program prints results, validation messages, or error messages based on execution.



**Sample Supported Commands**
* Variable assignment
  x = 10;
* Arithmetic expression
  print(5 + 7 * 2);
* Conditional statement
  if(x < y) print(x); else print(y);
* Loop
  while(x < 10) x = x + 1;
* Pattern matching
  match number "1234";
  match name "John";



**Learning Outcomes**
* Understanding of **regular expressions**
* Hands-on experience with **Flex and Bison**
* Practical knowledge of **compiler front-end design**
* Implementation of **CFG, parsing, and semantic actions**



**Team Contribution**
This project was developed collaboratively by three team members:

* Member 1: Lexer design and token definitions using Flex
* Member 2: Parser design, grammar rules, and semantic actions using Bison
* Member 3: Symbol table implementation, testing, debugging, and documentation



**Future Improvements**
* Add support for:
  * Functions
  * Arrays
  * Input statements
* Improve error messages with line numbers
* Add type checking and semantic validation
* Extend MiniLang into a full interpreter


**Conclusion**
MiniLang demonstrates how a simple programming language can be built using Flex and Bison. It serves as an effective learning tool for understanding lexical analysis, syntax analysis, and basic compiler construction techniques.
