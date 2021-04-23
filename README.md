# plate_detector
To detect the nameplate of cars.

Step1:
Run:
```
export DISPLAY=:0; g++ -o Project3 Project3.cpp `pkg-config opencv4 --cflags --libs`

./Project3 Resources/haarcascade_russian_plate_number.xml
```

Step2:
Show your license plate in front of your webcam. 

Step3:
Run:
```
cd Plates
```
Then you could check the resulting detected license plates/
