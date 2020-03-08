# Output Bits (Movement and Display)

These are the bits that output something, whether it be a light, some type of signal, a sound, or something else.

These bits actually do the work, as with just [input](/input-so) and [logic](/wire-dl) bits, nothing will happen, so you need an output bit for your device to function.

All of these bits also pass electricity along, so connecting another bit to the end of an output will continue your device. This means you can have as many [buzzers](/output-ls/#buzzer), [speakers](/output-ls/#speaker), and other noise making bits as you want! (Though we advise against this.)

This section is all about the bits that have moving parts or display data.

## DC Motor

![DC Motor Bit](https://cdn.shopify.com/s/files/1/1494/3290/products/DC_Motor_d_top_1512x.jpg?v=1571439468)

The DC motor is a simple motor that can be controlled to run either clockwise, counter-clockwise, or vary in speed and direction by the amount of power given.

### How to Use

The DC motor has three different settings, cw (clockwise), ccw (counter-clockwise), and var (variable). While the clockwise and counter-clockwise settings are self-explanitory, the variable setting can be a bit tricky. The variable setting is controlled via the amount of power going through. Try it out by using a [dimmer](/input-sw/#dimmer) or [slide dimmer](/input-sw/#slide-dimmer) with this bit.

The wheel included with some kits can be attached to the motor to create an electric-powered wheel.

## Vibration Motor

![Vibration Motor Bit](https://i.shgcdn.com/9a0f7dbb-b884-40a3-93c0-ab3685f9435d/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The vibration motor is very simple, just like most other output bits. When power is recieved, the metal disc connected to the main bit via the wire will begin to vibrate.

## Fan

![Fan Bit](https://i.shgcdn.com/ef1a70fd-e06a-4fd2-b89b-babc0a3548d1/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

When the fan bit recieves power, the fan connected to the bit will begin to spin.

## Servo

![Servo Bit](https://i.shgcdn.com/26dca3cf-b741-44dc-9851-d0b6f8ab8020/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The servo bit is similar to the [DC motor](#dc-motor) bit, though is much more specialized and controllable.

### How to Use

The servo bit has two different settings. the TURN mode adjusts the position of the servo based on the signal it's recieving. In simpler terms, when in TURN mode, the servo can be controlled via a [dimmer](/#input-sw/#dimmer), [slide dimmer](/input-sw/#slide-dimmer), or any other bit that controls the amount of power.

The SWING setting will have the servo move back and forth on its own. The speed of the servo in this mode can be slowed by lowering the power with a [dimmer](/input-sw/#dimmer).

## Number

![Number Bit](https://i.shgcdn.com/6fdac1e9-13ca-4869-b089-e70ae159ba33/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The number bit has two seven-segment number displays that display different numbers based on four different settings.

### How to Use

This bit has four different settings for counting. Those settings are up, down, voltage, and value. Up and down are in the couny category, while voltage and value are in the read category.

For the count category, both up and down count up and down respectively when they recieve a signal. This bit will **NOT** count up or down continuously if there is continuous power delivered, it will only occur when a new signal is recieved.
For example, attaching a [button](/input-sw/#button) before this bit will increase the count every time the button is pressed, because the bit is recieving a new signal. If this sounds confusing, play with it a little bit, and you'll get it eventually.

For the read category, the bit will, no surprise, read the voltage and value of the current signal. If you attach this bit directly to the power on a read mode, it will read 5.0 on voltage mode, and 99 on value mode.
You can use a [dimmer](/input-sw/#dimmer) to control the voltage and value. Both scale similarly to each other. The voltage ranges from 0 (no power) to 5.0 (full power), and the value ranges from 0 (no power) to 99 (full power).

## Bargraph

![Bargraph Bit](https://i.shgcdn.com/8a84cbad-787b-4535-8acc-14e7575455fc/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The bargraph bit is similar to the [number](#number) bit's voltage read mode, but displays the information in a different way.

### How to Use

The bit only has one setting, and that is to read the voltage of the current signal. Since the normal power is 5V, if this bit is plugged directly into the power, it will read all the way up to 5. However, using something like a [dimmer](/input-sw/#dimmer) to control power, you can lower the voltage of the current signal. At 1V, the bit will read to 1, at 2V, the bit will read to 2, and that continues up to 5.
