myProgram: main.o address.o employee.o address.h employee.h
		g++ main.o address.o employee.o -o myProgram

main.o: main.cpp employee.h address.h
		g++ -c main.cpp

employee.o: employee.cpp address.h
		g++ -c employee.cpp

address.o: address.cpp
		g++ -c address.cpp

clean:
		rm -f *.o

.PHONY: clean
