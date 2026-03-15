# HSRGB-enclosure  
  
  
Overview  
I designed HSRGB some time ago. I have these around the house and still use them. I wanted to design an enclosure for them “in my free time.” Without having any, I thought maybe someone would do it for me. It could be a good practice for me to clearly express what I need and test online design services. And that’s exactly what happened. How someone from another part of the world, based on a short description and without any prior knowledge about the project, designed an enclosure for me.  
  
I listed a few enclosure design services found online:  
- [Pcbway.com](https://www.pcbway.com)  
- [Fiverr.com](https://www.fiverr.com)  
- [Freelancer.com](https://www.freelancer.com)  
  
I got a quote from Pcbway - quite pricey. I have no doubt that they would do it well, but it was way over budget for a simple project like this. [Freelancer.com](http://Freelancer.com) required posting a job description and waiting for offers. I liked the [Fiverr.com](http://Fiverr.com) approach more - find freelancers, look through their portfolios, and chat with the ones you like the most. Post the SOW and agree on terms and price. I went with Fiverr.  
  
Fiverr request:  
  
Hello,  
  
I need a simple enclosure for this tiny device. Please send me quote and expected lead time. At this point I need just basic prototype and I’m not expecting it to be perfect by any means 😉  
Step model of existing electronics in the attachment   
  
Requirements:  
	•	Material: plastic (you may choose a suitable type)  
	•	Design: two parts (top + bottom)  
	•	Assembly: latches or screws  
	•	Prototype: 3D printing, FDM preferred  
	•	Manufacturing: overall concept should be compatible with injection molding (no need for this to be injection molding optimized at this point, just keep in mind that at some point it might be manufactured this method)  
	•	Openings/cutouts: USB-C connector, RGB light strip  
	•	Usability: enclosure must allow pressing the on-board button  
	•	IR receiver: must be exposed for infrared reception  
	•	Status LED: visible from outside (located between the IR receiver, USB-C port, and ESP32 module)  
	•	RF: enclosure must not block ISM 2.4 GHz radio waves  
  
Delivery format: STEP (original CAD source file is a plus)  
  
Provided file: HSRGB.step  
  
  
After agreeing on terms and payment the journey begins  
  
  
## Revision 1  
  
![Screenshot 2026-03-11 at 06.07.41.png](Attachments/BEBA92BF-C2B9-48FD-8CAC-DD3BCFD95860.png)  
![Screenshot 2026-03-11 at 06.08.23.png](Attachments/91C73E4D-A07A-45D5-ACAB-147D00F2DCE9.png)  
  
### Feedback   
  
Hi,I’ve reviewed the design on a larger screen. Overall, the concept is good and you understood the assignment well — thank you. There are a few important points that need adjustment:1. The button should be operable without tools. I’d like a flexible (spring-like) element integrated into the top part, with a long pin underneath that presses the PCB button when squeezed.2. The PCB currently lacks proper support. It rests only on bottom edges, with no mounting points on top or sides. There are also collisions with bottom-side components. Please consider SMD placement tolerance (±0.15 mm) and ensure proper clearance.3. The USB-C port sits too deep. Most cables have a 1.5–2.0 mm gap between the receptacle and plug housing after connecting, so the enclosure wall needs to be thinner and likely closer to the PCB.4. The IR receiver opening must allow at least a 120° reception angle. Currently it seems limited to around 60°, which significantly reduces functionality. (wall could be thinner and closer to the receiver)5. The screw connection between halves needs redesign (missing countersinks, missing mating hole, wall likely too thin, screw heads may protrude). We should reconsider the joining method for strength and aesthetics.6. Please remove the antenna cutout and use a thin plastic wall (~0.4 mm) instead.7. The enclosure should cover only the electronics board. The light strip is much longer (up to 3 m) than shown in the 3D model.Let me know if anything needs clarification.  
  
  
  
## Revision 2  
  
![Screenshot 2026-03-11 at 06.11.17.png](Attachments/124D052A-1574-45A4-9379-0D0B52366394.png)  
  
![Screenshot 2026-03-11 at 06.11.31.png](Attachments/71C7D56E-D43B-4D37-82A0-494784B48A89.png)  
  
  
And here some error happen, because my feedback was not posted on the site, and returned 3rd revision is basically 2nd revision.  
  
  
## Revision 3  
  
![Screenshot 2026-03-11 at 06.11.31.png](Attachments/C1BF70D0-946B-4495-BE23-A43F9AAC5624.png)  
  
![Screenshot 2026-03-11 at 06.17.56.png](Attachments/679ADCFE-3C54-4A8D-9BD5-1A41C49D5B2A.png)  
  
### Feedback:  
  
Hi,I’ve just reviewed your recent work. I like it, it looks more like something I imagined. A few corrections:1. There is some glitch around snap mechanism in the top part (the snap is also located in top part, when it should be just in the bottom), but overall I like the proposed mechanism2. Around the antenna - It is better, but the PCB should be covered completely and flexible RGB led strip should be supported from below (be possible to glue it to the bottom part of the enclosure - remove strain from the solder joints). On the image cyan is extension of the top part, red is attached to the bottom part.4. Lack of cutout for status LED - maybe to make it looks right add COTS light pipe to the top part, for ex. FIX-LEMB2-2.5V0-FFIX&FASTEN [https://www.tme.eu/en/details/fix-lemb2-2.5v0-f/lightpipes-for-led/fix-fasten/](https://www.tme.eu/en/details/fix-lemb2-2.5v0-f/lightpipes-for-led/fix-fasten/) 5. As the enclosure is becoming more and more air tight, please add small ventilation holes on the sides (on the walls where latches are located) 6. The separate extension for the push button - I did not yet 3d printed it yet, but I feel it may be unstable. Maybe it will be worth to add some longer guiding for the element to make sure it will move only up and down, but not to the sidesI will 3D print it tomorrow and if I find something more, will get you know. But overall it looks very good and I believe it could be the last correction necessary  
  
![Screenshot 2026-02-22 at 17.32.06.png](Attachments/19474196-58A3-4913-88E3-A2B8947D0585.png)  
  
  
## Revision 4  
  
  
![Screenshot 2026-03-11 at 06.22.56.png](Attachments/958AAFE8-E652-47B5-BCA2-ED461C7F8825.png)  
  
![Screenshot 2026-03-11 at 06.23.14.png](Attachments/FA48AAEE-1142-499F-8E46-D84A04DBFA03.png)  
  
### Feedback:  
  
Hi,I've 3D printed recent revision as well. Overall fit with the device is great! A few minor corrections needed:- please increase the clearance between button extension and the enclosure - it fit really tight, even after some sanding of the 3D print- I've found the cause of the IR sensor and the enclosure - there is slight mistake in the model I've provided. The soldered boards have this IR sensor placed directly on the USB C port with 0 mm gap (attachment) Please correct this and decrease the top part height accordingly - to maintain 0.3 mm gap. - I've found the source of misunderstandings regarding ending wall of the enclosure in the direction of antenna and LED light strip. The 3D model of the light strip in the file I've provided is wrong. Actually mounted light strip is more dense and has more LEDs on the same distance. Attaching photos with annotations. The cut part is exactly 11 mm from the enclosure edge. Please make this part enclosed up to this point as photographed and drawn on the screenshots.- I thought the latches were sufficient, but they are keep breaking. They are too fragile. Please increase its thickness up to full side wall thickness (1.2mm) and maybe change the orientation - make them pointing inwards (attached screenshot). And dd corresponding narrowing in the top part (to make them snap and lock the case). Maybe also increase their width as well (make them wider). I believe that will be it. Please provide solid works files in the final revision  
  
![add closing wall.png](Attachments/265A65AE-93F8-4190-8553-2660023B7766.png)  
![button clearance and IR received gap.png](Attachments/0EC4DBAE-53EA-426B-B923-CD35DDA1C4CE.png)  
![distance to the first gap on the led strip.png](Attachments/F89BB8C9-E25C-429F-9794-4C431B5E9A5A.png)  
![end the enclosure here.png](Attachments/3847F8C7-EE7C-4DAA-8CFC-64E15F11B4A2.png)  
![gap between IR sensor and USB C connector.png](Attachments/98B5C7AC-6C82-4CE9-AE97-4C119FCCB7BD.png)  
![latch reverse.png](Attachments/B88715F2-2669-4729-ACA9-9EF20EE79948.png)  
![HK CODE](Attachments/D2884900-467F-4A7E-A743-1CA8D8B01505.png)  
  
  
## Revision 5  
  
And that's what become final revision.

  
![Screenshot 2026-03-11 at 06.24.01.png](Attachments/FAEE4699-0226-4723-8791-D9FCF2132A55.png)  
  
![Screenshot 2026-03-11 at 06.24.15.png](Attachments/000E8884-2C2D-481E-80A3-98BB1176A6EC.png)  
  
![Screenshot 2026-03-11 at 06.25.47.png](Attachments/8171C073-92EF-4D5A-8C57-BA101157C750.png)  
  
![Screenshot 2026-03-11 at 06.24.51.png](Attachments/4D46DB64-BD40-45B6-A3C5-2104A5BAD0FA.png)  
  
![Screenshot 2026-03-15 at 17.41.41.png](Attachments/CE344654-776B-4D44-BFA6-29FF6FB3EF0B.png)  
  
![Screenshot 2026-03-15 at 17.42.04.png](Attachments/86B85625-9202-42BC-A7AB-B1BE97EE3629.png)  
  
  
## Summary:  
  
The enclosure fits snugly on the device and snaps into place. Overall, it was a smooth experience. I’m definitely going to use the service again in the future.
  
  
