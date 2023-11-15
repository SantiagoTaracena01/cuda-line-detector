all: pgm.o	hough	hough-constant	hough-shared

hough:	hough.cu pgm.o
	nvcc hough.cu pgm.o -o hough -lopencv_core -lopencv_highgui -lopencv_imgcodecs -lopencv_imgproc -I/usr/include/opencv4

hough-constant:	hough-constant.cu pgm.o
	nvcc hough-constant.cu pgm.o -o hough-constant -lopencv_core -lopencv_highgui -lopencv_imgcodecs -lopencv_imgproc -I/usr/include/opencv4

hough-shared:	hough-shared.cu pgm.o
	nvcc hough-shared.cu pgm.o -o hough-shared -lopencv_core -lopencv_highgui -lopencv_imgcodecs -lopencv_imgproc -I/usr/include/opencv4

pgm.o:	misc/pgm.cpp
	g++ -c misc/pgm.cpp -o ./pgm.o
