# InputDebounce Arduino Library [![Build Status](https://travis-ci.org/Mokolea/InputDebounce.svg)](https://travis-ci.org/Mokolea/InputDebounce)

Simple polling input debounce [Arduino](https://www.arduino.cc/) library.

[![Release](https://img.shields.io/github/release/Mokolea/InputDebounce.svg)](https://github.com/Mokolea/InputDebounce/releases)
![License](https://img.shields.io/github/license/Mokolea/InputDebounce.svg)

## Facts
 - used for push-button like switches
 - delivers input value (state) after it has been stable (not flickering) for longer than the debounce period
 - delivers continuous or single-shot pressed-on time duration [ms]
 - handles input pin with:
    - external pull-down resistor
    - external pull-up resistor
    - internal pull-up resistor (default)

Available from the Arduino IDE [Library Manager](https://www.arduino.cc/en/Guide/Libraries)

## Usage
Just see the [examples](examples):
 - [general](examples/Test_InputDebounce/Test_InputDebounce.ino)
 - using [callback functions](examples/Test_InputDebounce_Callbacks/Test_InputDebounce_Callbacks.ino)
 - using [inheritance](examples/Test_InputDebounce_Inheritance/Test_InputDebounce_Inheritance.ino)

*Apache License 2.0*

-- Mario
