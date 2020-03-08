# Switch Input Bits

These are the bits that modify the signal passing through your circuit. This changes the output of [output](/output-ls) bits.

This set of bits can really make your device unique, and helps to define the purpose of what you're building.

Many of these bits may sound confusing at first, but if you try them out for a little bit, we're sure you'll get the hang of them.

These bits switch other bits on and off.

## Button

![Button Bit](https://i.shgcdn.com/2413271a-cdce-4bab-aeb2-91b2ed6f6522/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

When the button is pressed, it sends an ON signal. When it is not pressed, it sends an OFF signal.

## Dimmer

![Dimmer Bit](https://cdn.shopify.com/s/files/1/1494/3290/products/ua9EofWg_720x.jpeg?v=1571439466)

The dimmer bit limits the amount of power that goes through it, thus reducing the intensity of things like [lights](/output-ls) and [buzzers](/output-ls/#buzzer).

The more you turn the dimmer counter-clockwise, the less power there is, until there is no power going through at all. This can also be used to control the motion of the [servo](/output-md/#servo) in TURN mode.

## Pulse

![Pulse Bit](https://i.shgcdn.com/dec22683-4e1f-495e-a5e2-537823d308d2/-/format/auto/-/preview/3000x3000/-/quality/lighter/0)

The pulse bit sends power out at a consistent and specific rate that is determined by the slider on the bottom of the bit.

## Roller Switch

![Roller Switch Bit](https://i.shgcdn.com/9f008c63-5ed7-4661-b84c-389a26757ee8/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The roller switch works like the [button](#button), as when you click the switch, power is let through. However, you can also invert this, by making the power turn off when the top-left switch is set to open.

## Sequencer

![Sequencer Bit](https://i.shgcdn.com/a289d9e0-2791-40da-9275-e019bd05d14f/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The sequencer can activate up to 8 different outputs in a certain order.

### How to Use

The sequencer bit has two settings. The dial in the middle determines how the sequence is progressed. Forward will go 1-8, backwards will go 8-1, pendulum will go 1-8, then 8-1, like a pendulum, and random will simply turn on a random output.

The switch on the side determines how fast the sequence is progressed. In step mode, the next output is activated whenever a new pulse is recieved. You should use this setting with a [pulse](#pulse) bit to control the speed of the sequence. When the setting is on speed, it will progress based on the voltage. The voltage can be controlled with a [dimmer](#dimmer).

## Slide Dimmer

![Slide Dimmer Bit](https://i.shgcdn.com/9e565834-262d-40ef-b7f4-fdbe5c9fbb64/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The slide dimmer works like a normal [dimmer](#dimmer), but uses a slide instead of a dial to adjust voltage.

## Slide Switch

![Slide Switch Bit](https://i.shgcdn.com/bd3f664a-85d8-438d-b4f2-e24a7a48b1bb/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The slide switch lets power through when set to ON, but doesn't when set to OFF.

## Timeout

![Timeout Bit](https://i.shgcdn.com/c7540760-50d5-4a7d-834a-2a546c801d4a/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The timeout bit sets a timer when it recieves an ON signal, and changes its output once the timer has run out. The screwdriver dial is used to adjust the length of the timer. The switch can change the mode from on-off (will send an ON signal until timer runs out) to off-on (will send an OFF singal until timer runs out), and vice versa.

## Toggle Switch

![Toggle Switch Bit](https://i.shgcdn.com/6802cdb0-d85d-4346-925a-14a22ce864ca/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The toggle switch works like the [slide switch](#slide-switch), but uses a lever instead of a slider.