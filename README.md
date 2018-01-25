# TTS

## Text-to-Speech for Arduino

- requires an amplifier on the PWM output pin (see below)
- see [blog articles](http://programmablehardware.blogspot.ie/search/label/tts)

## Supported Hardware

- ATmega328-based Arduinos (e.g., Uno, Pro, Pro Mini, etc.): pins 3, 9, 10
- [ArduTouch](https://github.com/maltman23/ArduTouch): pin 9
- ATmega1280-based Arduinos (e.g., Mega): pins 44, 45, 46
- Arduino Leonardo: pin 5
- Arduino Due: pins DAC0 or DAC1
- Teensy 3.2: pin A14
- Teensy 3.5, 3.6: pins A21, A22
- Teensy LC: pin A12

## Amplifier

![alt tag](images/Arduino-LM386.png)

## Credits
- original implementation by Clive Webster in [Webbotlib](http://webbot.org.uk/iPoint/30.page)
- ported to Arduino by [Gabriel Petrut](http://www.tehnorama.ro/minieric-modulul-de-control-si-sinteza-vocala/)
- Stephen Crane modified it to use pins other than pin 10 with the help of [this tutorial](https://sites.google.com/site/qeewiki/books/avr-guide/pwm-on-the-atmega328)
- [manitou48](https://github.com/manitou48) added support for Leonardo
and ARM processors with DAC (Teensy, Due)

## See Also
- Teensy [forum](https://forum.pjrc.com/threads/44587-TTS-(Text-to-Speech)-Library-Port)
- separate port/hack for MBED ARM with DAC [repository](https://developer.mbed.org/users/manitou/code/tts/)
- Hackaday article on [LM386 amplifiers](https://hackaday.com/2016/12/07/you-can-have-my-lm386s-when-you-pry-them-from-my-cold-dead-hands/)
