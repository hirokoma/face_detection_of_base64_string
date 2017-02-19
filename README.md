- python 2.7.11
- download haarcascade_frontalface_default.xml

~~~
brew install opencv
ln -s /usr/local/Cellar/opencv/2.4.13.2/lib/python2.7/site-packages/cv.py cv.py
ln -s /usr/local/Cellar/opencv/2.4.13.2/lib/python2.7/site-packages/cv2.so cv2.so

python detect_base64.py BASE64_STRING_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
~~~
