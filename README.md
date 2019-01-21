# Arduino-Laser-Harp
Using an arduino to recreate a harp using a laser. (THIS REPORT WAS CREATED BEFORE I STARTED, FINAL REPORT CAN FOUND AT THE BOTTOM)

Using a laser, I will project a “harp” using a mirror and make it so that if a person breaks a laser, then a harp like sound or a piezo buzzer will be played. A stepper motor rotating very quickly will make it look like the lasers are not moving. A stepper motor will be constantly sweeping and if an interruption between angles (i.e. 0 < x < 30) then that corresponding sound will be made.


How Does It Work?:
A laser beam is shone. A stepper motor with a mirror divides it into nine beams. When one or more of the beams are cut, the light sensor (Light Detecting Resistor, LDR) detects it. According to the corresponding motor positions, it sends signals to the Arduino, which in turn produces the respective notes through a computer or keyboard.


Parts List and Cost:
- Laser	($10 - $20)
- Mirror	($5 - $10)
- 12V Stepper Motor	($35 - $40)
- Arduino Uno ($13.95)
- LDR (Photoresistor)	($1 - $3)
- SD Card Module ($3 - $5)
- SD Card ($1 - $2)
- ULN2003 ($1 - $2)
- Resistor 220 Ohm ($0.3)
- 5K Trimpot (Trimming Potentiometer) ($1 - $2)
- NPN Transistor (<$1)

Total Cost:
$79.95 - $104.95


Design:
- Will not include a frame
- Laser will be supported by a small piece of wood
- Small mirror for reflecting the laser, supported by small piece of wood
- 9 Laser (Strings) coming from the mirror
- Synth noises when produced when hand is covering laser (Reading from SD Card)


Final Report:
https://docs.google.com/document/d/1ie_FF2NZWcKDU94B0S_8_2DN_NAJ92Xz1j6L2p1hra4/edit?usp=sharing
