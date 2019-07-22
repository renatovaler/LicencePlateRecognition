# LicencePlateRecog using dakflow , opencv 


LicencePlateRecognition : we use darkflow (yolo) object detection api for detecting a licence plate in a image then crop the image to process the data in the cropped image.

Here We use pytesseract for detecting ocr data in image , just some modification's in the code you  can use any ocr detection algorithm example use could use GoogleVisionApi too

This Code now works for Images and videos 

Please Follow the enlisted commands below to make the program up and running 

``` 
cd LicencePlateRecognition
```


``` 
virtualenv venv
```
``` 
source venv/bin/activate
```
```
pip install -r requirements.txt
```

``` 
pip install . 
```
(or)
```
python setup.py build_ext --inplace
```

#usage

```
python runPlates.py -i <path_to_img>
```
(or)

```
python runPlates.py --image <path_to_img>
```
(processing video's)
```
python runPlates.py --video <path to video >
```


To show Processing Images/Frames

```
python runPlates.py --video/image <video/image file path > --show True/False

```

(for all options)

```
python runPlates.py -h 
```

