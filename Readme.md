# PyImageSearch Tesseract OCR

https://www.pyimagesearch.com/2020/05/25/tesseract-ocr-text-localization-and-detection/

## Secondary Blog

https://www.pyimagesearch.com/2018/08/20/opencv-text-detection-east-text-detector/

## Background

I started with the Tesseract OCR blog and then wanted to try to see if Tesseract could read license plates.  He actually does a bad job of this.  There were some suggestions on trying to localize the text first and then use Tesseract.  This is where I started to look at the second blog to see if the localizing of text would help.  The first thing I did was just try to take the 'car wash' image from the second blog to see if Tesseract could read the text and it could not.  I will see if text localization can first help.


## OpenCV

Make sure OpenCV 4+ is installed

## Install Tesseract on MacOC

`brew install tesseract --HEAD`

## Other Libs

`pip install pillow`

`pip install pytesseract`

`pip install imutils`

## License Plate Dataset

https://www.kaggle.com/mobassir/fifty-states-car-license-plates-dataset?

## TODO

* Why does this not work well with License plates?
