# playground_notebook
Artisanal notebook with a Circuit Playground embedded all over

#### *A project in collaboration with Rebe Montero*

### Description
This is the first in a series of projects to embed electronics, in this case the Adafruit's Circuit Playground, an unexpensive board that includes functionality such as capacitive touch, accelerometer and speaker, all very usable in this project.

In the future I will revisit this project but with an ESP8266 Feather with MycroPython, with an OLED display, and probably with an Adafruit AudioFX Soundboard.

## Materials
- Paper, cartboad, fabric, sewing needle and thread to build the notebook
- A Circuit Playground. Remove the tall JST battery connector
- Conductive cooper tape
- Sewable snaps for the battery switch
- Solder station

## Instructions

1. Base of the cover:
You need to cut the cardboard that will be the base for the cover, to include the electronics, plus paths for the battery and optionally cables. To embed the Playground I recommend to 3D print a soft bumper. This bumper may be glued to the notebook, allowing you to re-use the Playground for other projects.
Also print the same piece but with a solid material such as PLA, so you can use it as a mold to trace the cuts on the cardboard that is the base for the cover.
We used this particular bumper, [for a Circuit Playground wearable project](https://www.thingiverse.com/thing:1682293), but you can use other designs or even make your own.

2. Battery:
Cut the JST connector on the battey and tin the cables. Solder them to the VBATT and GND pads on the Playground.
Optionally, one of the cables can pass throug a sewable snap, and the other half connected to the Playground, acting as a textile switch to keep the Playground off without draining the battery.

3. In-page capacitive buttons:
Use the copper tape to run the thin strip between the blocks of folded pages, and to the final position on inside any desired page inside the notebook. This can be used to create buttons inside the pages, for future actions.

4. In-cover capacitive buttons:
Also run copper tape from the desired pads on the Playground to the parts on the cover where you would want the buttons placed, and then use a small piece of conductive fabric to create the button. Then stick the tape to the conductive fabric, and cover with regular fabric as in a regular notebook.

5. Upload the software to create the desired effect for the notebook, depending on creativity or on customer's specifications.

### Done
- Embedded Adafruit's Circuit Playground microcontroller
- Embedded battery

### Wishlist/TODO
- Laser cut patterns for the cartboard of the cover
- Sewable snap battery switch
- Page contact detection, for playing sound effects, music or other actions
- Capacitive touch buttons, on the cover, back or other places
- Deep sleep mode for low battery use
- Exposed USB port for charging and loading firmware
- Images to describe the project, maybe move to a separate MD file
