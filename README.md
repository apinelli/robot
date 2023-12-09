# robot

## To make the app start everytime the system reboots

1. Created robot.py.service under /etc/systemd/system
2. sudo systemctl enable robot.py  -->  Created symlink /etc/systemd/system/default.target.wants/robot.py.service → /etc/systemd/system/robot.py.service.
3. sudo sytemctl start robot.py
4. To check status: sudo systemctl status robot.py



