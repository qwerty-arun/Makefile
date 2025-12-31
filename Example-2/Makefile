CC=gcc
CFLAGS=-I.
DEPS = hellomake.h

%.o: %.c $(DEPS)
	$(CC) -c -o $@ $< $(FLAGS)

hellomake: hellomake.o hellomake.o
	$(CC) -o hellomake hellomake.o hellofunc.o