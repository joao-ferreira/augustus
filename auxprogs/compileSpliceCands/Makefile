compileSpliceCands : compileSpliceCands.o list.h list.o
	$(CC) -o compileSpliceCands compileSpliceCands.o list.o;
#	cp compileSpliceCands ../../bin
compileSpliceCands.o : compileSpliceCands.c 
	$(CC) -Wall -pedantic -ansi -c compileSpliceCands.c 

all : compileSpliceCands

clean : 
	rm -f compileSpliceCands compileSpliceCands.o ../../bin/compileSpliceCands list.o
