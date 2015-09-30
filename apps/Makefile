DIR_L = home/heo/lecture/makes/lib
DIR_I = home/heo/lecture/makes/include

main : main.o
	gcc -o main -L/$(DIR_L)/ main.o -lfuncs

main.o : player.c
	gcc -c -I/$(DIR_I) player.c -o main.o

clean :
	rm -rf *.o main
