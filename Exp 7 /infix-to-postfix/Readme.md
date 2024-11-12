yacc -d infix-to-postfix.y     

lex infix-to-postfix.l         

gcc lex.yy.c y.tab.c -o infix-to-postfix     

./infix-to-postfix