CC = gcc
CFLAGS = -c -Wall

main: main.o
	$(CC) main.o -o $@

main.o : main.c P05.c
	$(CC) $(CFLAGS) $< -o $@
clean: 
	rm -rf *o
