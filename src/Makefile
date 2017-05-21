#CROSS_COMPILE=arm-linux-

all:test

test:test.o
	$(CROSS_COMPILE)gcc test.o -o test
test.o:test.c
	$(CROSS_COMPILE)gcc -c test.c -o test.o 

clean:
	rm test 
