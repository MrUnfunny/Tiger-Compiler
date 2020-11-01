a.out: main.o prog1.o slp.o util.o
	gcc main.o prog1.o slp.o util.o

main.o: main.c slp.h util.h
	gcc -c main.c

prog1.o: prog1.c slp.h util.h
	gcc -c prog1.c

slp.o: slp.c slp.h util.h
	gcc -c slp.c

util.o: util.c util.h
	gcc -c util.c

clean: 
	rm -f a.out util.o prog1.o slp.o main.o
