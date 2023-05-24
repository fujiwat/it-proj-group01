### IT Project1 - Group work
# "Reference worthy Web Calculator"
<img src="https://github.com/fujiwat/it-proj-group01/assets/16160120/aac3c3e0-2aa7-4ce5-8f5a-3b742e9bfa5e" width="200" />


## Overview
This is a group work at the university.
We, 5 members created a Web Calculator as "Worth of Reference" Calculator.

## Summary
Five Ingenuity Points
- Button layout and Coloring
- Notification by Sound
- Key and Screen, dual input
- Support Web Accessibility
- Web Font for Multi-Devices
Got perfect rating from 2 objective tests.

## Usage
Just Click the buttons as same as the physical regular calculator. If you want to get the result of 1 + 2 * 3 then that means 1 + (2 * 3) = 7 therefore you need to click following order:
[2] [*] [3] [+] [1] [=]
When you click the buttons for * / - + then the calculation is immediately occurred. Therefore, if you click buttons by the following order then the result is ( 1 + 2 ) * 3 = 9:
[1] [+] [2] [*] [3] [=]

## Features
### Point 1.  Button Layout and Coloring
Darker color placed outside.  Easy to find number buttons at center area.
You can use touch typing easily.
<img src="https://github.com/fujiwat/it-proj-group01/assets/16160120/6029698d-2194-4090-9d21-2de71cb98798" width="300" />

### Point 2. Notification by Sound
5 types of Sound:  0-9.   +-÷×   AC   C    BS
Found a suitable sound from a license-free website and made it shorter (https://soundeffect-lab.info/sound/button/)

<img src="https://github.com/fujiwat/it-proj-group01/assets/16160120/591a96a1-32f3-4824-889c-0f516978487b" width="300" />

<img src="https://github.com/fujiwat/it-proj-group01/assets/16160120/a2b560d7-7a1a-462f-8a55-f0256c3ca426" width="300" />

### Point 3. Dual Input Methods, From Keyboard and Click/Tap
It is better to have key input for realistic calculator program.
We can input faster using hardware keyboard.
https://github.com/fujiwat/it-proj-group01/assets/16160120/1739aa2d-2aca-4a57-b40d-fde3e8e42d56
![image](https://github.com/fujiwat/it-proj-group01/assets/16160120/42e49d3e-6182-433a-8f9c-618e966c8cda)

### Point 4. Web Accessibility for Visual Disabilities
- Contrast between Text and Background needs 3:1
Several Color sets are tested.
![image](https://github.com/fujiwat/it-proj-group01/assets/16160120/3e7ddd93-4fe6-4e02-bf60-12f92af01c5e)
- Consideration for People With Color Blindness
Every buttons, text is able to recognize clearly
![image](https://github.com/fujiwat/it-proj-group01/assets/16160120/9e540607-faee-439a-a26e-5fa0fcc185e0)

### Point 5.  Uniform Display Using Web Fonts
![image](https://github.com/fujiwat/it-proj-group01/assets/16160120/385077db-100e-4fa9-969c-df054a338df6)
![image](https://github.com/fujiwat/it-proj-group01/assets/16160120/96f4f133-f3ca-483d-a73e-e0d1d583be4c)

### Succeeded to Improve in Objective Tests
- Lighthousr -- Google Web Accessibility Check
First version:
![image](https://github.com/fujiwat/it-proj-group01/assets/16160120/f4be05b9-a2e2-4695-b5a6-4410a1c87e51)
Second version:
![image](https://github.com/fujiwat/it-proj-group01/assets/16160120/2c336f19-09c2-49dd-9f5c-2ca0e885201b)
Final version:
![image](https://github.com/fujiwat/it-proj-group01/assets/16160120/5aa1b949-9c74-41a3-9911-716c94c4aab4)
- Google Mobile Friendly Test
![image](https://github.com/fujiwat/it-proj-group01/assets/16160120/3a3216ee-3a45-4d48-bb67-d92e1b1461ae)

## Restrictions
The calculation values are using double which means 64bit IEEE floating-point number type. Sometimes it causes a margin of error therefore this program round to the 10th decimal place.

## Reference
This program is derived from the following source code and modified the color and added functions "1/x", "Sin", "Cos", "Tan", and decimal point.
https://try.websharper.com/snippet/adam.granicz/00002I
Web-font 'DSEG' is used from the following web site:
https://github.com/keshikan/DSEG
### Font License:  
Copyright (c) 2020, keshikan (https://www.keshikan.net),  with Reserved Font Name "DSEG".
This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is copied below, and is also available with a FAQ at: http://scripts.sil.org/OFL
