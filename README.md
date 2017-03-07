# xboxdrv-cfg
xboxdrv config for 4 wireless xbox360 controllers

Install
-------
* copy xboxdrv.serice in your systemd service directory (e.g. /usr/lib/systemd/system/xboxdrv.service)
* copy xboxdrv.conf into /etc
```
   git clone https://github.com/JackMcCrack/xboxdrv-cfg.git
   sudo cp xboxdrv-cfg/xboxdrv.serice /usr/lib/systemd/system/
   sudo cp xboxdrv-cfg/xboxdrv.cfg /etc
```   
   

* systemd requires a daemon reload to use new/updated serice files, just run:
```
   systemctl daemon-reload
```

Start/Stop xboxdrv
------------------
```
   systemctl start xboxdrv
   systemctl stop xboxdrv
```

See also:
* https://pingus.seul.org/~grumbel/xboxdrv/

Tested successfully
-------------------
* Geometry Wars
* STARWHALE
