# robot


## To make the app start everytime the system reboots

1. Created robot.py.service under /etc/systemd/system
2. sudo systemctl enable robot.py  -->  Created symlink /etc/systemd/system/default.target.wants/robot.py.service → /etc/systemd/system/robot.py.service.
3. sudo systemctl start robot.py
4. To check status: sudo systemctl status robot.py


## Video Settings

1. Uses "Motion" (Survelliance Software) module at port 8081


## Access from outside

1. Currently using Serveo


## References

https://circuitdigest.com/microcontroller-projects/web-controlled-raspberry-pi-surveillance-robot


