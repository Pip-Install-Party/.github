# Welcome to Pip Install Party 

This organization was established to facilitate the development of a BNF interpreter.

The interpreter was the culminating project for CS460: Programming Languages at Sonoma State University during the Fall 2024 semester. Collaboratively created by a team of five students, this project presents an interpreter designed to process and execute code written in Backus-Naur Form (BNF), a C-like programming language. The interpreter interprets the input in BNF, analyzes its structure and logic, and executes the corresponding computations to generate the desired output. This project exemplifies advanced concepts in parsing, syntax analysis, data structures, and interpreter design.

The interpreter was constructed through a modular design, composed of several key components that work in sequence to process the input code. These components include:

1.	[Comment Removal](https://github.com/Pip-Install-Party/Ignoring-Comments): Eliminates non-executable comments to prepare the input for further processing.
   
2.	[Tokenization](https://github.com/Pip-Install-Party/Tokenization): Breaks the input into meaningful tokens, such as keywords, identifiers, and symbols, forming the building blocks of the program.
   
3.	[Recursive Descent Parsing](https://github.com/Pip-Install-Party/Recursive-Descent-Parser): Analyzes the tokenized input based on the defined BNF grammar, ensuring syntactical correctness while building a structural representation of the code. Generates a Concrete Syntax Tree (CST) representing program strucutre.
   
4.	[Symbol Table Generation](https://github.com/Pip-Install-Party/Symbol-Table): Creates a mapping of variables, functions, and other symbols to their corresponding definitions and values, enabling efficient lookup during execution.
   
5.	[Abstract Syntax Tree (AST) Generation](https://github.com/Pip-Install-Party/Abstract-Syntax-Tree): Constructs a tree representation of the program that encapsulates its logical structure and relationships, serving as the foundation for execution.

6.	[Interpreter](https://github.com/Pip-Install-Party/Interpreter): Constructs the full interpreter using a combination of the prior componets.

Each component builds on the outputs of the previous stage, concluding in a fully functional interpreter capable of processing complex inputs and producing correct results. This layered approach highlights the importance of modularity and abstraction in software engineering and programming language design.

## Contributors
<a href="https://github.com/Pip-Install-Party/Interpreter/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Pip-Install-Party/Interpreter" alt="contrib.rocks image" />
</a>


### Connect With Us

Blake Marshall - [Github](https://github.com/officialblake) | [LinkedIn](https://www.linkedin.com/in/blakemarshalll)  
Brandon Robison - [Github](https://github.com/brandonuscg) | [LinkedIn](https://www.linkedin.com/in/brandon-robinson-uscg/)  
Holden Ea - [Github](https://github.com/holdenkea) | [LinkedIn](https://www.linkedin.com/in/holden-ea-28a535208/)  
Jacob Sellers - [Github](https://github.com/JacobS999) | [LinkedIn](https://www.linkedin.com/in/jacob-sellers-83840826a)  
Rolando Yax - [Github](https://github.com/Ryax3) | [LinkedIn](https://www.linkedin.com/in/rolandoyax/) 
