
# when `serial.serialutil.SerialException: [Errno 13] could not open port /dev/ttyUSB0: [Errno 13] Permission denied: '/dev/ttyUSB0'` happens

`sudo usermod -a -G dialout $USER`

`sudo chmod -R 777 /dev/bus/usb/`

restart and voila