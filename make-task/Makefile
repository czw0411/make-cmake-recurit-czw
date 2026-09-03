CC = gcc
CFLAGS = -Wall -Wextra -Iinclude

calculator: main.o calculator.o logger.o
	gcc -o calculator main.o calculator.o logger.o

main.o: src/main.c include/calculator.h include/logger.h
	gcc $(CFLAGS) -c src/main.c

calculator.o: src/calculator.c include/calculator.h
	gcc $(CFLAGS) -c src/calculator.c

logger.o: src/logger.c include/logger.h
	gcc $(CFLAGS) -c src/logger.c

.PHONY: clean
clean:
	rm -f calculator main.o calculator.o logger.o
