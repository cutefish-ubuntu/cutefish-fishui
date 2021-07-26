# cutefish-fishui
CutefishOS GUI library, based on Qt Quick. 

# FishUI

FishUI is a GUI library based on QQC2 (Qt Quick Controls 2), every Cutefish application uses it.

## Features

* Light and Dark Mode
* Borderless window (XCB Window move & resize)
* Blurred window
* Window shadow
* Desktop-level menu
* The style of the Qt Quick control
* ...

## Dependencies

```bash
sudo apt install libqt5x11extras5-dev libkf5windowsystem-dev qtbase5-private-dev libxcb1-dev libxcb-shape0-dev libxcb-icccm4-dev -y
```

## Build
Before build, make sure you have necessary Qt environment.

```bash
git clone https://github.com/cutefishos/fishui.git
mkdir ~/fishui/build $$ cd ~/fishui/build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
sudo make install
```

## License

FishUI is licensed under GPLv3.

![GPLv3](https://raw.githubusercontent.com/cutefish-ubuntu/cutefish-ubuntu/master/img/gpl3.png)
