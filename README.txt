Robot 

Sep 11, 2021

Referencias:
1) https://circuitdigest.com/microcontroller-projects/web-controlled-raspberry-pi-surveillance-robot

- Install Python 3
- Create a virtual environment under /var/www/lab_app
- git clone https://github.com/apinelli/robot
- In crontab (crontab -e):
@reboot /var/www/lab_app/start_robot.sh &

