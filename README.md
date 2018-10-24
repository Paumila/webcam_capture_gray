# webcam_capture_gray

Realitzem unes modificacions en el programa per poder cambiar el color de la webcam

S'utilitzen les següents comandes:

Change color image to grayscale image
 cvtColor( image, grayimage, CV_BGR2GRAY );

Change color image to Luv image
 cvtColor( image, Luvimage, CV_BGR2Luv );

Change color image to Luv image
 cvtColor( image, HSVimage, CV_BGR2HSV );

Amb aquestes comandes el que fem es passar la imatge de la webcam a diferents colors (GrayScale, Luv i HSV)
