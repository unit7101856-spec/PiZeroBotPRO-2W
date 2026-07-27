Everything in GitHub will allow you to re-create the code and PCB needed to be combined with a Raspberry Pi Zero 2W!

You will need to download and print the shell and wheels:
https://www.thingiverse.com/thing:7388207

You can also find the "ready-to-order" board on PCBWAY:
https://www.pcbway.com/project/shareproject/ZeroBotPRO_2W_b3dcc9ae.html

You will need all the parts shown in Documentation\NON-PROD Parts List.xlsx (The PiZero2W, battery, ect...)
With the PCBA in hand, and after you have soldered in the through hole components and the PiZero2W, follow the instructions at \Documentation\Robot_Controller_Instructions_FromFreshInstall.pdf
Once you are satisfied with the hardware interpretation of the software, you can move onto assembling the board, camera, and motors into the shell using the Documentation\ZeroBot Fastener Guide.pdf as your guide. Attach the wheels once you are done. The code and where it needs to be placed in the base installation of PI-OS is found at CODE-robot-controller. Some... unpacking is required XD
You will need to build the starup scripts (shown in the documentation) or you can connect to the robot each time and manually start the app.js if you have future plans for the hardware platform.

Here are a few more details ;)
I built a web-controlled robot from scratch — and instead of
hot-gluing a bunch of dev boards together, I designed a custom
all-in-one PCBA to keep things clean and repeatable.

The robot streams live video to a browser-based controller,
reads battery voltage, monitors CPU temperature, and drives
two motors with a virtual joystick. All controlled over WiFi
from any device with a browser — no app required.

And because the Pi Zero 2W sits at the heart of it, there's
nothing stopping someone from plugging an AI model into this
thing and letting it drive itself.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🛒 PARTS USED
━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Raspberry Pi Zero 2W: Sourced on Digi-Key
Raspberry Pi Camera Module: Sourced on Digi-Key
Micro SD card: https://amzn.to/4hj9epc
18650 Battery: https://www.18650batterystore.com/products/samsung-25r-18650
Motors: https://amzn.to/3SR7GJf
Buzzer: https://amzn.to/4fhQyUw
Standoffs: https://amzn.to/44yzHaX
Screws: https://amzn.to/4wOhlyR
Portable Router: https://amzn.to/4f49yHc
*See Github BOM for all parts needed for the PCB
*See Alternate BOM for development boards


-Thanks Ill-Informed Human
