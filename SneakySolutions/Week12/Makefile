# Steven Strijakov's Fun Quizzes for Fun
# Week12

CC=gcc
CFLAGS=-Wall -Werror -gdwarf-2

all: solution

solution: BST.o main.o
	$(CC) -o solution BST.o main.o

BST.o: BST.c BST.h
	$(CC) -c $(CFLAGS) BST.c

main.o: main.c
	$(CC) -c $(CFLAGS) main.c

clean:
	rm -f BST.o main.o solution
