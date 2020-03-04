# Input Bits

These are the bits that modify the signal passing through your circuit. This changes the output of [output](/output-ls) bits.

This set of bits can really make your device unique, and helps to define the purpose of what you're building.

Many of these bits may sound confusing at first, but if you try them out for a little bit, we're sure you'll get the hang of them.

## Button

![Button Bit](https://i.shgcdn.com/2413271a-cdce-4bab-aeb2-91b2ed6f6522/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The button bit acts like a gate. When the button is unpressed, the gate is closed, and no power is let through. When the button is pressed, the gate is let open, and all the power that was backed up is let through.

In layman's terms, when you press the button, the rest of the circuit turns on, and when you aren't pressing it, the circuit is off.

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

