all: pgm.o	hough

hough:	hough.cu pgm.o
	nvcc hough.cu pgm.o -o hough

pgm.o:	misc/pgm.cpp
	g++ -c misc/pgm.cpp -o ./pgm.o
