all : calculator.o delete.o header.o main.o printmenu.o report.o taxestimate.o trade.o
	gcc -o all calculator.o delete.o header.o main.o printmenu.o report.o taxestimate.o trade.o
main.o : main.c header.h
	gcc -c main.c
calculator.o : calculator.c 
	gcc -c calculator.c
delete.o : delete.c 
	gcc -c delete.c
trade.o : trade.c 
	gcc -c header.c
printmenu.o :printmenu.c  
	gcc -c printmenu.c
report.o : report.c    
	gcc -c report.c
taxestimate.o : taxestimate.c 
	gcc -c taxestimate.c
clean :
	rm calculator.o delete.o header.o main.o printmenu.o report.o taxestimate.o trade.o


        



  	
        	



