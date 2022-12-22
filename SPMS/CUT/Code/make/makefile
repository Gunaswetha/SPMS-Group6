all: main.o header.o
	gcc -o all main.o 


main.o: main.c
	gcc -c main.c


header.o: header.h
	gcc -c header.h

memcheck:
	valgrind main.o 2> memcheck.txt

clean:
	rm all main.o

 	


        



  	
        	



