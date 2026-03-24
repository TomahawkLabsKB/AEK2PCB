This is a work in progress.

This project intends to replace the orignal PCB of the Apple M3501 (Apple Extended Keyboard 2, AEK2) with a PCB powered by a Pimoroni PGA2040, which is an RP2040 breakboard board. The PGA2040 is no longer in production and not readily available for purchase.

Backstory:
I have always enjoyed the Apple M3501 and been a fan of Alps SKCM/L switches and wanted a functional way to have an AEK2 with every flavor of Alps SKCM/L I could collect. I wanted to manufacture and design as much of this project as I can. 

The main objectives of this project as as follows:

#1. Replace the original PCB with a new PCB with the following features:

  1. Native USB support
  2. Fit the M3501 case
  3. Connect to the original ADB port daughter board for USB passthrough
  4. Retain indicator LEDS and locking Capslock switch
  5. Easy access to the BOOTSEL and RESET switches for easy flashing
  

#2. Replace the original plate with a new aluminum plate with the following features:
  1. Fit the M3501 case using the original rubber "gaskets" on the bottom and the locking tab on top
  2. Fit original stabilizers
  3. Allow access for left and right USB breakout locations
  4. Include mounting holes on the top of the plate for future custom case mounting


Bill of Material:



| Part | Spec | Ref Numbers | Amount |
| :--- | :--- | :--- | :--- |
| Diode | 1N4148 | D1-104 | 104 |
| LED | 5mm Diffused | LED1-3 | 3 |
| LED Resistor | 1/4w 220R | R1-3 | 3 |
| USB breakout | JST XH 2.54mm 4-Pin | J1-2 | 2 |
| Polyfuse | 60R050XU | F1 | 1 |
| USB Protection | USBLC6-2SC6 | U2 | 1 |
| Reset/bootsel button | 6mm Momentary | S106-107 | 2 |
| Keyswitch | Alps SKCM\L | S1-105 | 105 |


Untested changes:
1. Num and Scroll Lock LEDs were moved, but placement not confirmed
