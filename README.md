# Custom Firmware Patches For Ginko Synthese Grains

http://www.ginkosynthese.com/product/grains/

This is a quick and dirty Ruby script that converts wav files and
outputs firmware based on framen amenbreak for the Grains Eurorack module.

*NOTE* If you're only looking for ino files they can be found inside the `patches` folder

## Requirements

I'm using a mac and I since this is "quick and dirty" I didn't consider file seperators for other OS. I might fix that in the future.

You will need sox

```
brew install sox
```

## App Usage

```
ruby app.rb path/to/sound.wav
```

Thats it :)

## Grains Controls

* Knob 1: Loop start
* Knob 2: Loop length
* Knob 3: Pitch
* Input 3: Gate trigger

## Credit

All credit for the Arduino code goes to Framen and the following sources:

* http://www.ginkosynthese.com/product/grains/
* http://playground.arduino.cc/Code/PCMAudio
* michael@hurts.ca
* https://www.facebook.com/HRTLmuzik
* https://github.com/thatpixguy/hrtl-amen
