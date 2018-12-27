# led_devicce_driver_2
Device driver for separately shining two LEDs.

## Demonstration
- https://youtu.be/MVUase_HDJ0

## Requirements
- Raspberry Pi 3 Model B
  - Raspbian
  
- Linux Kernel Source
  - kernel build scripts : https://github.com/ryuichiueda/raspberry_pi_kernel_build_scripts.git
 
- 2 LEDs


## Usage
```
make
sudo insmod myled.ko
sudo chmod 666 /dev/myled0
```

## Licence
This repository is licensed under the GPLv3 license
