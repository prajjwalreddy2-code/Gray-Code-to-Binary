<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project converts a Gray Code input into its equivalent Binary Code output using XOR gates. The most significant bit (MSB) of the binary output equals the Gray Code MSB, and each subsequent binary bit is obtained by XORing the previous binary bit with the next Gray Code bit.

## How to test

Provide Gray Code inputs using the switches; the circuit will convert them to binary, which is displayed on the colored LEDs. Verify the output LEDs to confirm the binary equivalent of the Gray Code inputs.

## External hardware
Switches (for Gray Code input)

XOR gates (for Gray to Binary conversion)

LEDs (Green, Red, Blue, Yellow to display binary output)

Pull-down resistors (connected to switches) for signal stability
