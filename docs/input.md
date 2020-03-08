# Input Bits

These are the bits that modify the signal passing through your circuit. This changes the output of [output](/output-ls) bits.

This set of bits can really make your device unique, and helps to define the purpose of what you're building.

Many of these bits may sound confusing at first, but if you try them out for a little bit, we're sure you'll get the hang of them.

## Button

![Button Bit](https://i.shgcdn.com/2413271a-cdce-4bab-aeb2-91b2ed6f6522/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The button acts like a gate, when you press it, it lets power through, but when it's not pressed, power isn't let through.

## Delay

![Delay Bit](https://cdn.shopify.com/s/files/1/1494/3290/products/9ZxKWVaQ_2048x.jpeg?v=1571439466)

The delay bit repeats audio that is given to it depending on a certain time and feedback.

### How to Use

This bit only works when given a sound with a bit like the [oscillator](#oscillator) or the [keyboard](#keyboard)

This bit has two knobs, time and feedback. The time knob controls the amount of time each sound and each silence lasts for. The feedback knob controls how many times the sound will repeat. If the feedback is turned up to the max, the sound will repeat forever.

Remember, since a sound is produced with this bit, you will only be able to hear the sound by using the [speaker](/output-ls/#speaker) bit after it.

## Dimmer

![Dimmer Bit](https://cdn.shopify.com/s/files/1/1494/3290/products/ua9EofWg_720x.jpeg?v=1571439466)

The dimmer bit limits the amount of power that goes through it, thus reducing the intensity of things like [lights](/output-ls) and [buzzers](/output-ls/#buzzer).

The more you turn the dimmer counter-clockwise, the less power there is, until there is no power going through at all. This can also be used to control the motion of the [servo](/output-md/#servo) in TURN mode.

## Envelope

![Envelope Bit](https://cdn.shopify.com/s/files/1/1494/3290/products/yxg1ZcZw_2048x.jpeg?v=1580401247)

This bit is used to change the character of a sound to fit a certain instrument.

### How to Use

The two main settings, attack and decay, determine how long or short the sound sounds. The attack setting determines how long the sound takes to ramp up to max volume. Zero attack would mean that the sound is instantly at max volume.

The decay setting determines how long the sound takes to go down to zero. A zero decay would mean the sound is instantly over after the sound stops coming.

The third connection point at the top allows you to trigger the effect with another bit, like the [keyboard](#keyboard).

## Keyboard

![Keyboard Bit](https://i.shgcdn.com/ac13b0bb-5d3b-4fa3-b604-1e3447c3c252/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

This bit is similar to an electronic keyboard, as it allows you to play specific notes with keys.

### How to Use

The keyboard is similar to the [oscillator](#oscillator), in the way that it produces a tune. However, the keyboard has a similar layout to a piano, and plays specific notes rather than electronic tunes.

Pressing a key will produce a tone, and that tone will come out depending on two key modes, hold and press. In press mode, the note will come out while a key is pressed, but not after. In hold mode, the last played note will continue to be played until the mode is changed or the power is cut.

The octave slide on the left will change the octave, meaning that when the slide is down, the notes are lower, and when the slide is up, the notes are higher.

You'll notice there are two output connections. The normal postitioned one will output the sound signal according to what you pressed, the top one will output a normal 5V power signal when a key is pressed. This power output will still adhere to the key mode the keyboard is on.

## Other Info

This bit can be used in conjuction with the [oscillator](#oscillator) to change the tune, pitch, and waveform of the notes.

## Light Sensor

![Light Sensor Bit](https://cdn.shopify.com/s/files/1/1494/3290/products/0G5dBlAQ_2048x.jpeg?v=1580401388)

This bit will gradually increase power as it is exposed to more and more light, or the reverse in dark mode. Its function is similar to the [button](#button), though it activates gradually with light rather than instantly with a press.

### How to Use

The light sensor gradually increases the power up to 5V (max power) as light increases. While the [button](#button) jumps instantly to 5V when pressed, the light sensor gradually works up to 5V as the light shined on it increases. The speed at which the light sensor gets to full power can be changed with the sensitivity slider.

The light/dark mode switch will change in what ways the light sensor releases power. On light mode, the sensor will release power as light level goes up, but on dark mode, the sensor will release power as the light level goes down.

### Other Info

Some older models may use a screwdriver dial instead of a slide for sensitivity. This works the same, however, you'll need to use the purple [screwdriver](/placeholder) to change the sensitivity setting

## Microphone

![Microphone Bit](https://i.shgcdn.com/01e9f4ed-6d3a-42a8-bc27-573548bc6a07/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The microphone bit recieves audio from a seperate device or through it's microphone, and sends either sound or a 5V signal out after it.

### How to Use

The microphone bit has two ways of inputting sound. The first is to simply play sound into the microphone. The second way is to connect an external device to the bit with a 3.5mm audio cable, and play music or sound on that device.

When the microphone recieves sound in any way, it will then transmit that sound to the next bit in the device. However, the bit can change its mode from sound to other. In other mode, instead of sending a sound, it will send a simple 5V signal when a sound is recieved.

## Mix

![Mix Bit](https://i.shgcdn.com/ba8c1df4-71e9-4a9f-a1f7-71298f93a45d/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The mix bit allows you to combine to sound inputs into one output.

### How to Use

You can use something like an [oscillator](#oscillator) to generate the tune for the bit. The two dials on the large portion of the bit control the volume of each input. 

## Motion Trigger

![Motion Trigger Bit](https://i.shgcdn.com/6a256fe4-0415-4c81-ba84-10b830aa2cfc/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The motion trigger bit works similarly to the [button](#button), though instead of sending a signal on a click, it sends a signal when it detects movement.

### Other Info

The range of this bit is around 10ft x 10ft, and is very sensitive, so don't feel like it's not working if it's constantly sending an on signal while you're working on it.

## MP3 Player

![MP3 Player Bit](https://i.shgcdn.com/fcfa6a25-66df-4c43-8a26-faae0f0cef79/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The MP3 player bit plays MP3 files off of a Micro-SD card inside the bit.

### How to Use

To start, load all of your mp3 files onto a micro-sd card and add a number in the front according to the order you want tracks to be played (ex: "bigman.mp3" and "smallboy.mp3" turn into "1bigman.mp3" and "2smallboy.mp3").
The numbers do not have to be in the front without spaces, just the first thing on the file.

The mode switch on the side determines how the tracks will be played. In once mode, it will play the current track once. In loop mode, it will continuously loop through the whole SD card. In next mode, it will just play the next track, and in all mode, it will play the whole card through once.

You can connect the bit to a speaker to play the music, or output it with the 3.5mm output jack.

## Oscillator

![Oscillator Bit](https://i.shgcdn.com/613261c5-de38-4e25-8647-2cfafdc50719/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The oscillator bit can adjust or create a tone by changing its tune, pitch and waveform.

## How to Use

The oscillator has three settings, tune, pitch, and waveform. The pitch dial is used to adjust the pitch of the bit. A higher value on the dial will mean a higher pitch. The waveform switch can switch between a square and sawtooth waveform, which both produce different sounds.

You can attach the oscillator after a sound producing bit like the [keyboard](#keyboard) to modify its sound. In this case, the tune slide actually does something, as it will modify the tune of the recieved sound. The pitch and waveform dials work the same when modifying sound.

## Pressure Sensor

![Pressure Sensor Bit](https://i.shgcdn.com/bd5b3ece-239b-479a-841b-a6c6e11bee6b/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The pressure sensor works similarly to the [light sensor](#light-sensor), but sends power based on the pressure put on the black circle.

## Proximity Sensor

![Proximity Sensor Bit](https://i.shgcdn.com/bd5b3ece-239b-479a-841b-a6c6e11bee6b/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

This bit works similarly to the [light sensor](#light-sensor), but sends power based on how close an object is to the sensor.