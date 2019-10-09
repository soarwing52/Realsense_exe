## Main usage
double click to open the measure exe

Esc/Q :leave

Space: switch between modes

Video mode:
any other key can go to the next picture
![video](https://github.com/soarwing52/Realsense_exe/blob/master/img/video%20mode.JPG)

Measure mode:
right key to go to the next picture, left will go the the previous picture.
left click, hold to measure, right click to erase
note:go back will take longer to find frames.
![measure](https://github.com/soarwing52/Realsense_exe/blob/master/img/measure%20mode.JPG)

## Data Capture:
with Intel D435 & GPS reviever

it will take picture every 25 meters while driving

Space: take on photo manually

P: pause auto mode, manual picture still available

R: start a new record

Esc/Q: shutdown

it will create 2 csv files, one for current location and one will show all the locations

## Data process:
select the folder with the recorded data(the one contains bag & foto_log)

start with create jpg, it will generate the pictures from the bag file

then the create list will read the jpg files and match a list with the coordinates of the time recorded

with geotag it will read the match list and write the coordinates to the photos.


technical:
It will base on the matcher.txt and find the corresponding frame number, to get the correct measure, therefore it takes longer

![command](https://github.com/soarwing52/Realsense_exe/blob/master/img/technical.JPG)

Creator:

Jay(Che-Yi), Hung

Creation Date: 2019/10/08

Camera: Intel Realsense D435
