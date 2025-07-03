---
title: "GigaBoard v1 Chaos Log"
author: "adarshdg"
description: "my first ever custom keyboard, where i learned things the chaotic way"
created_at: "2025-06-19"
---
Total Time Spent So Far: 17 Hours

## **6/19/2025 Log 1: deciding to build a keyboard because why not**

spent like an hour spiraling through mechanical keyboard rabbit holes on reddit.  
people really out here using 40 key boards like it’s a game of tetris  
me? i want a thicc board. full send. named it **GigaBoard v1** because it sounds strong. powerful.  
opened KiCad. stared at the screen for 10 minutes like it had insulted my family.  
finally made a rectangle. celebrated like i just discovered electricity.  
progress is progress, even if it’s one rectangle.
made the schematic

![image](https://github.com/user-attachments/assets/c0b2a086-d88d-46cd-acbf-96c8ab8a776e)


Time Spent: 1 Hour

---

## **6/20/2025 Log 2: matrix moment**

okay so what even *is* a diode matrix.  
spent 2 hours in the youtube trenches learning why keyboards don’t catch fire when multiple keys are pressed.  
respect to every tutorial with crusty mic audio, you taught me more than my formal education ever did  
laid out the switches in KiCad. looked cursed but in a fun way.  
accidentally deleted half the traces. ctrl+z came in like a superhero.  
genuinely felt like i was defusing a bomb.

![image](https://github.com/user-attachments/assets/96671d09-be7a-4555-accb-0e13f99078fc)

Time Spent: 2 Hours

---

## **6/21/2025 Log 3: millimeters vs inches vs my brain**

measurement war day.  
tried placing the USB-C port and realized i don’t know how long 10mm is off the top of my head  
fought the unholy trinity: mm, inches, and DPI scaling  
after a solid 90 minutes of confusion, finally got the USB port in a spot that didn’t break physics  
started thinking about the case. maybe i 3D print it?  
the vibes shifted from “just a keyboard” to “maybe a NASA control panel”

Time Spent: 1.5 Hours

---

## **6/22/2025 Log 4: trace spaghetti simulator**

back to PCB layout  
basically moved traces around for 2 hours like a 3D puzzle  
every time i fixed one connection, three others broke.  
it’s giving whack-a-mole energy  
added labels like “R1” and “C3” everywhere to look like i knew what i was doing  
it now looks legit. don’t ask me what anything does  
confidence: high. competence: unconfirmed.

Time Spent: 2 Hours
![image](https://github.com/user-attachments/assets/17795a43-23c3-481f-b2c7-74257e744f67)

---

## **6/24/2025 Log 5: silkscreen supremacy**

took a break yesterday to touch grass  
came back and decided to make the PCB silkscreen look fancy  
added arrows, random labels, and text that says “ily hack club” 
also maybe added my name on the back. it’s a signature now  
still no soldering done. still vibing

Time Spent: 0.5 Hour
![image](https://github.com/user-attachments/assets/72f197f7-72d5-4c4c-b1af-cbe889595db4)

---

## **6/25/2025 Log 6: firmware actually boots??**

made the firmware using QMK  
lowkey thought it would be impossible but turns out json configurators exist for a reason  
figured out the keymap, added a few macros, even made a shortcut that opens vscode  
tested it with a dev board and the thing actually responded  
if this board ever works physically, the firmware is ready to slap  
might mess with some RGB underglow config next

Time Spent: 1 Hour

---

## **6/27/2025 Log 7: screw placements are a lie**

realized i had no actual mounting points  
revisited the case design to add proper screw holes  
spent 45 minutes trying to align four holes in Fusion 360  
they still don’t line up. i gave up and used the “close enough” method  
case now looks like it’s meant to survive an earthquake

Time Spent: 0.5 Hour
![image](https://github.com/user-attachments/assets/b184f283-79a5-402b-99ef-af96134099c2)

---

## **6/29/2025 Log 8: case redesign chaos (i got roasted)**

turns out my first case design was actual garbage.  
like not even misaligned a little it fully didn’t fit the PCB.  
acon looked at it and basically said “bro what is this.”  
top shell was too tight, mounting holes didn’t match, and the USB cutout? yeah it was aimed at the void.  
i took the L and started from scratch. deleted most of the Fusion timeline out of spite  
made a new case with actual clearance, fixed the standoff placements, realigned everything to the PCB  
also added a fake flex grill just to feel something  
lesson learned: don’t freestyle case design without double-checking PCB dimensions

Time Spent: 1.5 Hours
![image](https://github.com/user-attachments/assets/36e58c37-20c4-490e-bdf1-655fce8fe58d)

---

### 7/1/2025 Log 9: precision? never heard of her  
spent 3 hours playing tetris with standoffs.  
moved one standoff 0.1mm and somehow the whole shell exploded.  
spent 30 minutes yelling at the Fusion timeline and 2 hours fixing sketch constraints that *i definitely did not break*.  
tried adding side vents—looked like cheese grater holes so i gave up.  
realized halfway in that i still hadn’t added clearance for keycaps.  
also tried “filleting for vibes” which made everything worse.  
progress? questionable. stress? yes.

Time Spent: 3 Hours
![image](https://github.com/user-attachments/assets/c8b0002a-19e2-4f76-bf48-85815481593e)

---

### 7/2/2025 Log 10: clearance redemption arc  
finally sat down and measured keycap + switch + plate stack height like a responsible human being.  
redesigned the top shell *again* to stop it from bullying the switches.  
added the space bar key properly (centered it this time 💀), and made sure it didn’t point to Narnia.  
got brave and tried snapping the case together in the render—*it actually fit*.  
the standoffs and holes now line up , and i didn’t break the timeline this time.  
might even add labels to sketches like a real CAD adult.  
3 hours in, confidence restored... for now.

Time Spent: 3 Hours
![image](https://github.com/user-attachments/assets/8e1876b1-ae29-475f-bd37-a0fab427519c)
![image](https://github.com/user-attachments/assets/6d0dd3d1-ef71-4c1a-80bf-582e8bb913b2)


---

**total time spent: 17 hours**  
next chapter: ordering PCBs, actual assembly, maybe setting something on fire by accident  
we keep building.
