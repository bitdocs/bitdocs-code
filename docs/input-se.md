# Sensor Bits

These are the bits that modify the signal passing through your circuit. This changes the output of [output](/output-ls) bits.

This set of bits can really make your device unique, and helps to define the purpose of what you're building.

Many of these bits may sound confusing at first, but if you try them out for a little bit, we're sure you'll get the hang of them.

These bits go output a range of power based on how much of a certain thing they sense.

## Light Sensor

![Light Sensor Bit](https://cdn.shopify.com/s/files/1/1494/3290/products/0G5dBlAQ_2048x.jpeg?v=1580401388)

This bit will gradually increase power as it is exposed to more and more light, or the reverse in dark mode. Its function is similar to the [button](/input-sw/#button), though it activates gradually with light rather than instantly with a press.

### How to Use

While the [button](/input-sw/#button) jumps instantly to 5V when pressed, the light sensor gradually works up to 5V as the light shined on it increases. The speed at which the light sensor gets to full power can be changed with the sensitivity slider.

The light/dark mode switch will change in what ways the light sensor releases power. On light mode, the sensor will release power as light level goes up, but on dark mode, the sensor will release power as the light level goes down.

**NOTE: Some older models may use a screwdriver dial instead of a slide for sensitivity. This works the same, however, you'll need to use the purple screwdriver to change the sensitivity setting**

## Motion Trigger

![Motion Trigger Bit](https://i.shgcdn.com/6a256fe4-0415-4c81-ba84-10b830aa2cfc/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The motion trigger bit works similarly to the [button](/input-sw/#button), though instead of sending a signal on a click, it sends a signal when it detects movement.

### Other Info

The range of this bit is around 10ft x 10ft, and is very sensitive, so don't feel like it's not working if it's constantly sending an on signal while you're working on it.

## Pressure Sensor

![Pressure Sensor Bit](https://i.shgcdn.com/bd5b3ece-239b-479a-841b-a6c6e11bee6b/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The pressure sensor works similarly to the [light sensor](#light-sensor), but sends power based on the pressure put on the black circle.

## Proximity Sensor

![Proximity Sensor Bit](https://i.shgcdn.com/3917d9d1-2892-4519-ad5a-b9c847ae50b5/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

This bit works similarly to the [light sensor](#light-sensor), but sends power based on how close an object is to the sensor.

## Remote Trigger

![Remote Trigger Bit](https://i.shgcdn.com/09e71eb2-5187-4f93-a007-12b6ca6fc3e1/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The remote trigger bit will send a signal when it recieves an IR signal. Things that can trigger this include your TV remote or the [IR LED](/output-ls/#ir-led).

## Sound Trigger

![Sound Trigger Bit](https://i.shgcdn.com/1cd8f2b6-6710-4a94-b523-d211c69beb15/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The sound trigger will send an ON signal when the sound in the room reaches a certain threshold. This threshold can be changed with the sensitivity slider.

## Temperature Sensor

![Temperature Sensor Bit](https://i.shgcdn.com/413e5535-025a-4c7a-b4fb-3eba9bfb71e4/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The temperature sensor works similarly to the [light sensor](#light-sensor), but reads the temperature instead of light. The bit also outputs the temperature read as a value, so you can attach a [number](/output-md/#number) bit to read the value. The mode switch on the side is used to change the value sent into Celsius or Farenheit.

## Threshold

![Threshold Bit](https://i.shgcdn.com/acf7e36a-7c7c-416c-a9a3-ca02477b1ee8/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

The threshold bit doesn't let a signal pass unless it reaches a certain threshold. This is is best suited to be used with sensor bits that have a range of voltage they can produce.
