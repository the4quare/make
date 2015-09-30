DIR = home/heo/lecture/makes/include

libfuncs.a : func1.o func2.o
	ar rv libfuncs.a func1.o func2.o

func1.o : func1.c /$(DIR)/func1.h
	gcc -c func1.c -I/$(DIR)

func2.o : func2.c /$(DIR)/func2.h
	gcc -c func2.c -I/$(DIR)

clean :
	rm -rf *.o *.a
