CFLAGS = -Wall
CPPFLAGS =
LDFLAGS =

.PHONY: all clean help

all: reversi

reversi: reversi.o
	gcc -o reversi reversi.o

reversi.o: reversi.c
	gcc -c reversi.c

clean:
	rm -rf reversi *.o

help:
	cat help.txt