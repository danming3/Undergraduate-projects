# Makefile
# created by Danming Wang, 04/22/2019

CXX_FLAG = --std=c++11 -g

game: main.o cards.o
	g++ $(CXX_FLAG) -o game main.o cards.o

testcards: testcards.o
	g++ $(CXX_FLAG) -o testcards testcards.o cards.o

main.o: main.cpp
	g++ -c $(CXX_FLAG) main.cpp

cards.o: cards.cpp
	g++ -c $(CXX_FLAG) cards.cpp

testcards.o: testcards.cpp
	g++ -c $(CXX_FLAG) testcards.cpp

clean:
	rm -f main *.o
