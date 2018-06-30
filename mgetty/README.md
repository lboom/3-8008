Basic mgetty setup (debian/ubuntu)
---------------------------------

First you will need to determine the serial(or USB) port that your
modem is connected to. `dmesg` will help here. Once you have determined
the correct settings, edit the services file included here and then 
run the following commands.
```
sudo cp mgettyUSB0.service /etc/systemd/system/.
sudo systemctl daemon-reload
sudo systemctl enable mgettyUSB0.service
```

Your mileage may vary.
