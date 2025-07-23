---
title: "NFC Business Card"
author: "DynamicWhiteHat"
description: "A Simple NFC Business Card For HackClub Highway"
created_at: "2025-07-23"
---

# Total Time Spent: 1 Hour 30 Minutes

# July 23: Did it all

Today I started the project and finished it, since it was a relatively easy design and there was a tutorial on the Onboard website. I just followed the tutorial and finished my card. I did have a little
bit of trouble at first getting used to the easyEDA controls since I use KiCad. First, I created my schematic, which is basically a copy of Maggie's:

<img width="764" height="515" alt="image" src="https://github.com/user-attachments/assets/112c768d-2ae7-453a-82c5-451856675cb8" />

It has a single LED, which I placed near my contact information. After I finished the schematic, I updated the PCB and started designing my card. I once again followed Maggie's tutorial and placed my components on the PCB,
ran the autorouter, and connected the unfinished nets. Then, I added some contact information, such as my Github repo and my personal website. I placed the LED on top of my contact information. While moving the LED,
I played around with different sizes, even trying 0201 to try to fit it on the i in my name. However, in the end, I settled on a larger 0805 size LED. I also added a QR code that goes to my instagram account. This is 
what it looks like:

<img width="730" height="490" alt="image" src="https://github.com/user-attachments/assets/dd417907-2ba1-4775-8b3b-aa68fdf3b939" />


However, one final change I made that Maggie didn't was resize the card to fit CR80 dimensions, that way it would fit in a real wallet. This required me to move the antenna and the silkscreen components to fit the new size.
Once I moved and rerouted everything, this is what it looked like:
<img width="1029" height="605" alt="image" src="https://github.com/user-attachments/assets/8e3b90c0-3ce6-41f7-9305-739184f89054" />

And this is the final 3D rendition:

<img width="781" height="499" alt="image" src="https://github.com/user-attachments/assets/b42c3f5d-10e2-42b1-9657-acfc03bba9c4" />

<img width="767" height="525" alt="image" src="https://github.com/user-attachments/assets/dffedead-f3b1-48e0-9953-87e3cd025a34" />

# Time spent: 1 hour 30 minutes
