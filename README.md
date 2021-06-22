# RGB-Pi
[![RGB Pi!](https://i.imgur.com/EDbCBTo.gif)](https://github.com/ACyberCat/RGB-Pi)
[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
[![issues](https://img.shields.io/github/issues/ACyberCat/RGB-Pi.svg)](https://github.com/ACyberCat/RGB-Pi/issues)
[![GitHub release](https://img.shields.io/github/release/ACyberCat/RGB-Pi.js.svg)](https://GitHub.com/ACyberCat/RGB-Pi/releases/)
[![Language](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)

Ultilizing the PWM signal and python to program ARGB/NeoPixels LED's on Raspberry Pi


## Demo
https://imgur.com/a/LwrkGD7

## Wiring
This project uses the RaspberryPi's GPIO pins to send the data signal to the supported LEDs.
>For wiring refer to this documentation:
https://learn.adafruit.com/neopixels-on-raspberry-pi/raspberry-pi-wiring


  
## Installation 

This Project is based off of the following libraries:
- jgarff's rpi_ws281x https://github.com/jgarff/rpi_ws281x

```python
sudo pip install rpi_ws281x
cd rpi_ws281x
```
- To run the 1st demo script run this command:
```python
cd rpi_ws281x/python/examples
sudo python3 strandtest.py 
```

## License

Distributed under the [MIT](https://choosealicense.com/licenses/mit/) License.


  
## Roadmap

- Button control Support

- Add more animations

- Create linked webapp for cross-platform control

- Automate change of animations according to set triggers
## Contributing

#### Contributions are always welcome!
1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/AmazingFeature)
3. Commit your Changes (git commit -m 'Add some AmazingFeature')
4. Push to the Branch (git push origin feature/AmazingFeature)
5. Open a Pull Request
## Authors

- [@ACyberCat](https://www.github.com/ACyberCat)

[![Discord Profile](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://imgur.com/a/4pm8HLD)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/RealCyberCat)
[![Reddit](	https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/user/CyberCat_)