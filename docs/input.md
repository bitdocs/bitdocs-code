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

