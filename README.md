# einky

<img src="./docs/images/inky_clock.jpg" width="500"/>

**einky** is a small open-source project that lets you use a Raspberry Pi with an E-Ink display to show useful info like time, weather, calendar, or custom text and images.  
It’s simple, quiet, and looks like paper — no glare, no distractions.

### What You Need
- Raspberry Pi (3, 4, or Zero 2 W)  
- MicroSD card (8GB or more)  
- Any supported E-Ink display (Inky or Waveshare)  
- Power supply and frame/stand  

### How to Install
```bash
git clone https://github.com/fatihak/InkyPi.git
cd InkyPi
sudo bash install/install.sh
```

That’s it! After reboot, your display will start working.

### Update
```bash
cd InkyPi
git pull
sudo bash install/update.sh
```

### Uninstall
```bash
sudo bash install/uninstall.sh
```

Simple, clean, and open-source.
