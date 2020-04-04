Project Name : The Lexer Analysis For Cool Language. 
__________________________________________________


Project Team Names :
--------------------
1-Ahmed Gamal Hassan 
2-Ahmed Samir AbdElfattah
3-Abdallah Hellmy Attia
4-Abdallah Mohamed Mostafa
5-Amr Muhammed Fahim
6-Muhamed Ahmed Amin
__________________________________________________

Project Files:
--------------

1-Lexical Rules for cool Languages ==> Lexer_grammer.g4 

2-To Output Tokens and Errors in Files ==> Lexer_IO.java

3-Cool Program (test case without error)==>good.cl

4-Cool Program (test case with error)==>bad.cl

5-Lexer_grammer.g4 file generates ==>Lexer_grammer 
____________________________________________________

Lexer_IO:
---------

-To Output Tokens and Errors in Files

Lexer_IO Functions:
--------------------
1-Lexer_IO constructor ==> get Tokens Stream from The Input File

2-Lex() ==> To Fill OutputTokens and Errors in Two Lists

3-WriteTokens() ==> Write Tokens in The Output File

4-PrintError() ==> To Print Lexical Errors
____________________________________________________

Lexer_grammer:
--------------

-Lexical Rules for cool Languages 

Rules:
------
1-KeyWords
2-Identifiers
3-Operators
_____________________________________________________

good file:
----------
-Cool Program (test case without error)

Example:
--------
Input ==>  x : Int;

Output ==>
 
           3
           ID
           x
           3
           COLON
           3
           INT
           3
           SEMICOLON
_____________________________________________________

bad file:
---------

-Cool Program (test case with error)

Example:
--------
Input ==>  x <- $4;

Output ==> lexical Error line Number :9
           lexical Error Name :$
_____________________________________________________







 






 










