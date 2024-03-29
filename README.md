# Smooth shock wave effect

## For running the application were used:
* __PyCharm 2020.3.2 (Professional Edition) Build #PY-203.6682.179, built on December 30, 2020__
* __Runtime version: 11.0.9.1+11-b1145.63 amd64__
* __VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o.__
* __Windows 10 10.0__

## For compiling source code following libraries were used:
* __pygame==2.0.1__ 
* __numpy==1.21.2__
* __pillow==8.3.2__

## Start-from-zero
* __Download and install Python__ https://www.python.org/downloads/ 
* __Open terminal in project folder and run the following commands:__ \
`pip install -r requirements.txt`\
`python main.py -im "Background_image.jpg" -wpv 6 -wd 1.01 -id 4 -cr 120`
 

## Image loading:
* __Drop image to project folder and specify it's name as shown below:__ \
`filename = "Background_image.jpg"` \
`Image = pygame.image.load(filename)`


## Shock wave params:

* __wave_propagation_velocity__ by default is `5`, in range `0 <= wave_propagation_velocity <= 30`
* __wave_distortion__ by default is `1.05`, in range `1 <= wave_distortion <= 1.2`
* __image_depth__ by default is `3`, in range `1 <= image_depth <= 8`
* __circle_radius__ by default is `100`, in range `80 <= circle_radius <= 120`

## Visualization




https://user-images.githubusercontent.com/70857282/133938830-10767b7a-323c-4e6c-ba83-08574bc8e34d.mp4


