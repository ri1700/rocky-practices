helloworld: main.o helloworld.o
	gcc -o helloworld main.o helloworld.o

main.o: main.c
	gcc -c main.c

helloworld.o: helloworld.c
	gcc -c helloworld.c

clean:
	rm -f helloworld *.o
