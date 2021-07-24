level1: lv1.l lv1.y
		bison -d lv1.y
		flex lv1.l
		gcc -o $@ lv1.tab.c lex.yy.c -lfl