CC = gcc
CFLAGS = -c -Wall

main: main.o
	$(CC) main.o -o $@

main.o: main.c P07.c
	$(CC) $(CFLAGS) $< -o $@
clean: 
	rm -rf *o
