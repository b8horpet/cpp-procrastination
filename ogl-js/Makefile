MOZJSCFLAGS=-I/usr/include/mozjs-24/ -lmozjs-24 -lz -lpthread -ldl
OGLCFLAGS=-lGL -lGLU -lglut -lpthread -ldl  -lutil -lm

OPTIONS=$(OGLCFLAGS) $(MOZJSCFLAGS) -std=c++11

all: main.cpp
	g++ main.cpp $(OPTIONS) -o app.o

clean:
	rm -f *.o
