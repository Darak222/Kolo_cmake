myProgram: main.o employee.o address.o
	g++ -o myProgram main.o employee.o address.o

main.o: main.cpp employee.h address.h
	g++ -c main.cpp

address.o: address.cpp
	g++ -c address.cpp

employee.o: employee.cpp address.h
	g++ -c employee.cpp

clean:
	rm *.o myProgram
