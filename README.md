No Name Yet

ROM based on AOSP for the Nexus 6. No Drama. No Bullshit. 


To sync

type in a command prompt
mkdir android
cd android
repo init -u git://github.com/Hive-Resurrection/android.git -b lp
repo sync -jX


X represents the number of jobs to conduct simultaneously. This number is recommended to be the number of cores, plus 1.

example: an 8 core should use -j9
