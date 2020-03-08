# Digital Logic

These bits perform various digital logic functions.

## AND (aka Double AND)
![AND bit](https://i.shgcdn.com/a39f2c15-fcb3-430c-b22a-b3ee61dd9c9f/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

It outputs an ON signal only when input 1 AND input 2 are both receiving an ON signal.

## NAND
![NAND bit](https://i.shgcdn.com/5c06dd06-9a7e-47d2-b33a-457df6012ff2/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

It is the opposite of an [AND gate](#AND), so it sends an OFF when both inputs are sending ON, and ON when an [AND gate](#AND) is normally sending an OFF.

## OR
![OR bit](https://i.shgcdn.com/3d6c8e96-5536-4b28-9327-5c6c7c931972/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

It sends an ON if one or more of the inputs sends an ON.

## NOR
![NOR bit](https://i.shgcdn.com/a2c56447-f6d6-413d-9837-707983489d0a/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

It sends an ON if and only if both inputs are sending OFF.

## XOR
![XOR bit](https://i.shgcdn.com/903bcc83-e704-4ddf-a487-4b160bc6364f/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

It sends an ON if the number of ON inputs is odd.

## Inverter
![Inverter bit](https://cdn.shopify.com/s/files/1/1494/3290/products/NpMJAgpg_1_2048x.jpeg?v=1571439466)

It sends out the opposite of whatever it receives. For example, if it receives an ON signal, it sends an OFF signal.

## Latch
![Latch bit](https://cdn.shopify.com/s/files/1/1494/3290/products/jRupPEw_2048x.jpeg?v=1571439466)

It sends a constant output, like a switch, but when it receives a momentary input, like a button, it will switch its output. It is like a toggle.

### How to Use

Hook it up after a button, turning the button into a switch.

# Wires

Wires are the middle pieces. They have varying functions and can do things in between [inputs](input) and [outputs](output).

## Wire

![Wire bit](https://i.shgcdn.com/554412d0-35cd-4023-97a3-0081190f6281/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

It goes between two bits and provides an extension. It allows you to place bits farther apart from each other, turn corners, and make connections that can twist, turn, and spin. It's just a wire.

## Fork
![Fork bit](https://cdn.shopify.com/s/files/1/1494/3290/products/EggJpbNQ_2048x.jpeg?v=1571439466)

It forks one input signal to three outputs. It can be used to send any type of signal.

## Split
![Split bit](https://i.shgcdn.com/03f5794e-495c-4e62-b068-5ce87686911c/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

Similar to the [fork bit](#fork), it splits one input to two outputs with an extension between each output. It can be used to send any type of signal.

## Makey Makey
![Makey Makey bit](https://i.shgcdn.com/e3448365-77bb-456f-a008-b74966408e47/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

This bit has two functions:
* It sends keystrokes over USB when a signal is sent to it.
* It can send a signal, like a button, when it's contacts are shorted.

### How to Use

* Either send a signal through one of its inputs, or short a key contact and the "Earth" contact by connecting them, to send the corresponding keystroke to a computer hooked up using a [Micro-USB cable](/placeholder).
* Short a contact and the "Earth" contact by connecting them to send an ON signal out tthe corresponding output.

### Other Info

For more info, check out the [Makey Makey website](https://makeymakey.com/pages/how-to).

## Arduino
![Arduino bit](https://i.shgcdn.com/a3d0b79e-fd5a-40eb-b2f3-e99019e9a540/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

It is a tiny computer called a microcontroller. It allows you to add programming to your circuits. It can recieve inputs and send outputs, and you can program any function into it. The code on the bit tells it what to do. There are three inputs, and three outputs, so you can program advanced hardware interactions or communicate with software.

### How to Use

To load code onto the bit, connect it to your computer with a [Micro-USB cable](/placeholder). Once you’ve loaded the code, it will stay on the bit, even if you disconnect it from the computer. If you leave it connected, you can also use it to send messages between your circuit and your computer. 

### Other Info

To learn more about how to use the Arduino Bit, check out our Arduino resources page [here](http://discuss.littlebits.cc/t/getting-started-with-arduino/109).

## CloudBit
![CloudBit](https://cdn.shopify.com/s/files/1/1494/3290/products/Cloud_1LR_720x.jpg?v=1571439465)

**NOTE: As of currently, the CloudBit is discontinued and the CloudBit software service is down for maintenance.**

This bit provides an easy way to create IoT devices, using the Internet of Things. When it recieves an input, it can send it out to the internet. It can also recieve a signal from the internet and output it into your circuit.

### How to Use

There are three ways to interact with the bit:
* The [littleBits Cloud Control](https://control.littlebitscloud.cc)
* [IFTTT (If This Then That)](https://ifttt.com/littlebits)
* The [littleBits API](https://developers.littlebitscloud.cc)

### Other Info

There are a few places to help get started:
* [CloudBit Getting Started Guide](https://auth.littlebits.com/cloudstart)
* [Cloud Control Getting Started Guide](https://discuss.littlebits.cc/t/getting-started-with-the-cloudbit/22483)
* [CloudBit API Guide](https://gist.github.com/daniellevass/67a13943be883e88df39)

## USB I/O
![USB I/O bit](https://i.shgcdn.com/6412f611-418c-4bb3-adba-ef5ebd5d297f/-/format/auto/-/preview/3000x3000/-/quality/lighter/)

This bit allows you send and receive digital audio and control voltages to and from a computer. When used in conjunction with a Digital Audio Workstation (DAW), you can record your sounds directly into a computer. You can also send audio from a computer to the littleBits  to manipulate it.

### How to Use

It connects to a computer using a [Micro-USB cable](/placeholder).
You can use it for:
* Sending and receiving control voltages allows you to use software programs like Max, PD, and CV Toolkit with the bit to control other bits.
* Using bits to create hardware controls for your software.

It will appear to your computer as an audio interface and its input and output routing can be selected as with any other audio interface. The bit can only be selected as either an input or output device at a given time but multiple of these bits can be used at once.
