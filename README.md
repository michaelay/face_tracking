# To compile
gcc -I/usr/local/Cellar/opencv/2.4.2/include/opencv/ -L/usr/local/Cellar/opencv/2.4.2/lib/ -lopencv_core -lopencv_objdetect -lopencv_highgui -lopencv_imgproc -o facedetect facedetect.c

# To run
./facedetect --cascade=haarcascade_frontalface_alt.xml 0

# Useful links
http://www.cognotics.com/opencv/servo_2007_series/part_5/page_5.html
