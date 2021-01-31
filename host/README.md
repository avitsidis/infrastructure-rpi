# Setup Host Raspberry Pi

1. Download Raspberry pi imager : [https://downloads.raspberrypi.org/imager/imager_1.5.exe]
2. once SD card written, put ssh file in the boot partition
3. run host.setup commands
4. ansible-playbook -e ansible_python_interpreter=/usr/bin/python3 all.yml
