# CircuitPython_CLUE_Yahboom_Gamepad
![Image of the CLUE and Yahboom gamepad](https://github.com/jisforjt/CircuitPython_CLUE_Yahboom_Gamepad/blob/main/images/CLUE_and_Yahboom_Gamepad.png)
This is a higher-level library to allow Adafruit's [CLUE](https://www.adafruit.com/product/4500) and Yahboom's Micro:bit Compact [Gamepad](http://www.yahboom.net/study/SGH) to communicate while maintaining all the functionality of the CLUE, except for touch features.


## Dependencies
This library depends on:
* [Adafruit CircuitPython](https://github.com/adafruit/circuitpython) v.6.3.0

The test example also depends on:
* [Adafruit_CLUE**](https://github.com/adafruit/Adafruit_CircuitPython_CLUE) v.3.0.0

**Repository is available in the Circuitpython Bundle v.6.X


## Instalations
Follow Adafruit's [CLUE Overview](https://learn.adafruit.com/adafruit-clue) instructions under _CircuitPython on CLUE_. During the installation process, you will download the latest _library bundle_ and transfer several libraries to the CLUE. Also, transfer the dependencies listed above to your _lib folder_.
Download this repository and copy _jisforjt_yahboom_gamepad.py_ onto your CIRCUITPY drive. 


## Usage
You can create a new main.py file and use:
```python
from jisforjt_yahboom_gamepad import gamepad
```

## License
The code of the repository is made available under the terms of the MIT license. See license.md for more information.
