# rpi-mpu6050


Test your MPU-6050 with your Raspberry pi via I2CBus :

If you are experiencing I2C address Confiliction instead of connecting the VCC port to 3.5v connect AD0 port to 5v

This will change the address from 0x68 to 0x69 :)

If you are connecting your MPU-6050 via AD0 make sure to change the address of the code to 0x69 

How-To:

Download the rpi-MPU6050 file from this repository 

Open Terminal app on your Raspberrypi 

Replace path of downloaded file with the address of your file

Type in terminal : cd /path of downloaded file     

Then Type in terminal : Sudo python rpi-MPU6050.py 

Done !


