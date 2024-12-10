# Project-Lexical-Analysis

□ This project part is to write a lexical analysis compiler to tokenize a simple program source codecalled CONG-LANG.
□ You should use the idea of regular language and finite automaton, looking ahead to each characterand finding word tokens of the source code.
□ You have to use Python, and you cannot use any libraries to skip the work.
□ the sample input and output are as follows:
-- Input 
--1Pencil = 12Pencil = 1Pencil x2if 1box is 1 then
    Pencil-box = 2Pencil+ 1box ~ 1Pencil
    else
    print 2Pencil
    -- Output 
    --[ID: 1Pencil][OP: =][NUM: 1][ID: 2Pencil][OP: =][ID: 1Pencil][OP: x][NUM: 2][KEY: if][ID: 1box][OP: is][NUM: 1][KEY: then][ID: Pencil-box]...-- Explanations --key (keywords): if, then, else, printop (operators): +, ~, x, /, =, isnum (numbers): decimal numbersid (identifiers): any other words; can begin with numbers
