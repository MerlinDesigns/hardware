# Em
The "Em" Controller is a hand-held all-button game controller. It's based around
a Raspberry Pi Pico and running the amazing
[GP2040-CE](https://gp2040-ce.info/) firmware.

![Picture of the Em from the top. It has two buttons on the top
left, two buttons on the top right, a OLED screen in the middle upper section,
and four smaller menu buttons in a cluster on the bottom middle. It is roughly
shaped like an M and is 3D printed in a purple color with black buttons.
A micro USB cable is connected to the controller on the back in the
middle.](pictures/outside-pic-top.jpg "The Em")

The idea is that most of the buttons are on the bottom side of the controller
and you can press them with your different fingers. The design aims to let you
use the same fingers for the same buttons you would use on more traditional
leverless controllers.

![Picture of the Em's bottom. It is 3D printed in purple PLA and is
generally shaped like an M. It has two rounded handles along the edges of the
controller. From the handles it angles topwards. On that surface, there are
eleven black buttons. From this perspective there are seven buttons on the left
and four buttons on the right. The left buttons are clustered similar to
sideways arcade buttons with an additional button on the top. The right buttons are 
shaped like sideways WASD](pictures/outside-pic-bottom.jpg "The business end of
the Em")

You hold it like this:
![Picture of the em being held in two hands](pictures/holding.jpg "Holding the
Em")

I recorded some videos to make it more clear how its used starting with
a top/front view:

[![Video showing how the Em is used, shot from the front. It shows someone holding the controller and Street Fighter 6 in the background. The player does a simple combo with Blanka in training mode.](https://img.youtube.com/vi/O2gVw8NUOoU/0.jpg)](https://youtu.be/O2gVw8NUOoU)

And here is a video from the bottom/back doing the same combo:

[![Video showing how the Em is used, shot from the bottom. Only the controller and two hands wrapping around it are visible. The fingers wiggle around between the different buttons while the player does a simple combo in street fighter 6](https://img.youtube.com/vi/_HlK434uRhY/0.jpg)](https://youtu.be/_HlK434uRhY)

## Why this form factor?
The idea is to have something more like a game pad and the ability to laze
around on the couch while also having the benefits of a leverless controller.
 Like a flatbox without having to have the controller on the lap. While you
could just use a gamepad for this purpose, I have been unhappy with most, if
not all, dpads and wanted to be able to not miss the benefits of more detailed
control of directional input.

## How can I get my own?
**Note:** I'm still working on refining the details of version 1.0. Some
aspects might not be completely final

This repository contains all information you need to print and assemble your
own.

The current version of this controller is handwired, so some soldering
equipment and skill is required.

### What you'll need
- 1x printed top shell
- 1x printed bottom shell
- 1x printed top support plate
- 1x printed bottom support plate
- 15x printed modular button caps 4.75mm high (based on [Stokken's great Kailh
  Choc V1 button
  caps](https://cults3d.com/en/3d-model/gadget/kailh-choc-v1-modular-keycaps))
- 15x printed button cap stems (from [Stokken's great Kailh
  Choc V1 button
  caps](https://cults3d.com/en/3d-model/gadget/kailh-choc-v1-modular-keycaps))
- 2x printed menu button top
- 2x printed menu button bottom
- 1x Raspberry Pi Pico
- 12x m2 heat set inserts (I use Ruthex) (you can use more)
- 4x 20mm m2 screws
- 3x 12mm m2 screws
- 3x 6mm m2 screws
- 2x 4mm m2 screws
- 2x m2 nuts
- 15x Kailh Choc v1 switches (I use
  5x [nocturnal](https://keycapsss.com/switchestester/switches/272/ambients-silent-choc-switches-lowprokb-kailh-choc-v1)
  and 10x
  [Twilight](https://keycapsss.com/switchestester/switches/272/ambients-silent-choc-switches-lowprokb-kailh-choc-v1?number=KC10221_TWI)
  but any others like pink or reds will work)
- 4x Kailh Silent switch for mice (or similarly sized substitutions)
- 1x 0,96 inch OLED SSD1306
- a bunch of wire to connect everything (I use AWG 26 stranded wire but other wire will work the same)

Why "you can use more" than 12 heat set inserts? I've added more standoffs that can hold heat set
inserts in case you want extra security. Mainly, they are there to support the
support plate without screws. I've found screws weren't needed in those
standoffs.

See notes on printing the components in [the printing
instructions](printing.md)

![Inside picture of the Em with the inner support plates being disconnected
from each other. Everything is printed in purple PLA. There is a raspberry pi
pico on the inside. A lot of green cables connected to the pico via soldering.
The green cables connect to the hot swap sockets for the switches. A couple of
black cables daisy chain the ground connection between the
switches.](pictures/inside-pic.jpeg "The assembled controller's insides")

## Planned changes
* improve README (more info, pictures, build information, installation)
* make a proper logo and add it to the top shell
* add OLED-free variant
* improve printability
* USB passthrough

## Future features
* PCB version
* RGB LEDs 
* Wireless?
* Analog sticks?

## Support
If you want to support this project you can [buy me
a coffee](https://ko-fi.com/merlindesigns).

## License
This project is published under [CC BY-NC-SA
4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). If you want to sell
this design, please contact me first.

If you have questions, you can find me (@Merlin) in the [Open Stick Community
Discord Server](https://discord.com/servers/openstickcommunity-1049366310389289001). 
