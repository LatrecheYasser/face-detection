# Face Detection 
---- 
a very small project to detect images that contain faces (the output 0 to say no face and 1 to say yes), using python, and the pytorch library

to run it `docker build -t face/python . `  and  `  docker run -it -p 8888:8888 -v /$(pwd)/../workspace:/workspace  face/python  `