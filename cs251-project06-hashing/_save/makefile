build:
	rm -f program.exe
	g++ -g -std=c++11 -Wall main.cpp hash.cpp -o program.exe

test:
	rm -f program.exe
	g++ -g -std=c++11 -Wall maincatch.cpp hash.cpp test01.cpp -o program.exe

testall:
	rm -f program.exe
	g++ -g -std=c++11 -Wall maincatch.cpp hash.cpp test*.cpp -o program.exe
	
run:
	./program.exe

valgrind:
	valgrind --tool=memcheck --leak-check=yes ./program.exe
