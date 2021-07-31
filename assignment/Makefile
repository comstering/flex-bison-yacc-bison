calc: calc.l calc.y calc.h
	bison -d calc.y
	flex -ocalc.lex.c calc.l
	gcc -o $@ calc.tab.c calc.lex.c calc-funcs.c

clean: 
	rm -rf calc.tab.h calc.tab.c calc.tab.c calc