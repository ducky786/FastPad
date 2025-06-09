---
title: "Macropad"
author: "ReRe"
description: "Creating a macropad to help with productivity and shortcuts"
created_at: "2025-05-25"
---

# May 26th: Finished the circuit schematics and the PCB layout!

I decided to do the starter project as I felt that it would help me with shortcuts as I am often times slow when it comes to navigating around on my computer and also to learn and build a PCB. I started with the cuircuit schematics on Kicad. This was my first time creating a PCB so I kinda felt lost on where to start, So My cousin helped guide me through this proccess. For my macropad, I wanted it to be simple and still have a good amount of controles. So I settled on 4 mx switches, 1 slider (PTL30-15R1-104B2 - Potentiometer), a Rotary Encoder, an oled .96" display and at the core a Xaio 2040. I did orgiginally wanted 5 buttons but did not have enough pins so I settled on the 4 button design instead. After I did add a Rotary incoder that had a button in it so it did make up for the loss.

Most of the time spent was on the schematics because it took me a while to find a propper slider online to import in and also due to trying to wire a clean schematic. After finishing the schematic I moved to the PCB lay out. I wanted a comfortable feel to it so I designed one that I thought would feel the best in my setup. I might change the lay out later though if I think a new layout might look better. I put the oled screen in the middle. I do want the oled screen to be an an angle so it is easier to view at but I am not yet sure How I would tilte the screen on the pcb! 

That was basically the things I worked on today, found the parts I wanted a designed a pcb that was the best. Tomorrow I want to work on the 3d modle of the macropad case!

[Time spent this session: 3hrs]

![image](https://github.com/user-attachments/assets/52b9c4bc-68d9-487f-9b57-53fbf859b3aa)
![image](https://github.com/user-attachments/assets/090341dd-8112-4bfa-9288-63b527d9080d)
![image](https://github.com/user-attachments/assets/88b5668d-ed0c-4fdd-9b68-dfa67733379c)


# May 27 & 28: Started on the macropad case!

On the 27th I started to work on my macropad case in Onshape. I had never cadded in my life and this was a huge challange for me! I spent most of this day looking at tutorials trying to learn how to create scketches, extrutions, holes and other stuff. I was still pretty skeptical on wether I could do the cad but I started anyways by taking measurments of my PCB. I planned to import the 3d PCB modle from Kicad into Onshape, so I could build around it to create the case. However, that did not turn out to work as the .step file did not like being imported into Onshape!!! When I tried to import the modle in it would NOT load. I tried countless number of times importing! I kept downloading the .step file form kicad to import into onshape but the file did not want to be loaded in for some reason. On my last attempt I decided to just wait for it to load in. Maybe I was just impatent and didnt give it enough time. 

While I was waiting for the that, I decided to create the connection lines on the pcb modle. My cousin pointed out that I was missing this. I didnt know I had to do that when making the pcb as I was still very knew to this. After finishing the connections I went back to Onshape. It finall loaded in. But not for long beucae by computer could not handle the complexity of the pcb and just beucase very slow and unworkable. So I just scratched that idea and decied to just take the measurements from kicad instead. 

[Time spent this session: 4hrs]

![image](https://github.com/user-attachments/assets/55f5f211-256e-48d7-9f3b-411b358f1ac9)


On the 28th I finally started to make progress on the cad after a whole day of learning and technical difficulties. Today I started by taking in the measuments form Kicad. The PCB is roughly 77mm x 77mm. I took these dementions and added an extra 5.8mm for the complete base demention. The base turned out to be 88.9mm x 88.9mm. After extruding it I  took out the portion for the pcb and added screw holes in the corners with a diameter of 3.2mm. I didnt yet settle on an exact hight for the pcb beucase I could not get the 3d modle to be imported in. After that I started on the top plate. I use ai03 to create the plate. This plate part took a while as I was still struggling to do somethings. When building the top plate, I kept running into  problem where I was not able to change the distance between the button and the edge of the plate. I manged to get it at the end by just using the transform tool rather then trying to change the demention between two diffrent sketches. I still need to add a couple for holes for the rodary incoder, slider and the oled screen. During this whole cadding prossess I also created the dementions on a piece of papper for me to better visualize the macropad.

[Time spent this session: 4hrs]

![image](https://github.com/user-attachments/assets/f4ba7f72-b1ed-4eb1-988f-897ea2a38c58)
![image](https://github.com/user-attachments/assets/5c7b74db-5bff-4c99-9893-bc498f8ceadc)

# June 1: Almost done with the case!!!

Yesterday My cousin suggested that I move my progress to fustion 360 as it might be easier and faster. Working on Onshape kinda felt like a nightmare! Everythnig was so slow as it was running on the webrowser and somethings refused to load. So I desideded to move what I had so far to Fustion. I downloaded and imported the base into fution. I decided to start the top plate from scratch again beucase the measurments felt off. But before I started on that I went in and added some tollerence in where the pcb would be. Before it was exactly to size which would most likly not be great when inserting it into the case later on. I added .6mm extra on the inside pcb area. After, I imported my DXF file for the key holes and the 3d modle of the pcb which this time loaded perfectly. Using the pcb as a guide I built the key holes to top plate. As I did this I refrensed to kicad to get the correct measurments and also added in some tollerence. At the end of this I had finsihed most of the holes on for the keys and the potentiometers. Only things that remained were was the USB-C port hole in the back and to clean up the modle and add some cool details maybe. There is one thing that I need to find some way to fix though. For the two potentiometers, they stick up a lot, and this feels very ugly and would show easily. I need to find a way to cover up the base of these potentiometers and make it look a bit more slicker!!

[Time spent this session: 4hrs]

![image](https://github.com/user-attachments/assets/a06c6b78-6158-4a09-baa0-9d8836c448dc)


# June 8th and 7th: Finished the CAD and the code!!!

After much struggle and delay I finally finished the macropad case on the 5th!. From the last case update and now, most the changes were just cleaning up the edges here and there. My cousin helped me through this last detailing prosses where I started to get the hang of cading! Deffenetly not the best but I was able to do somthing. In this final vertion I raised the top plate higher and left the button plates at the same hight. Doing this allowed me to cover up the slider, encoder and also the screen which all were showing visibly. At the end, the macropad looked very slick. I was using the 3d pcb for refrence to build around which was mostly going well. But the xiao 2040 did not load into the cad modle so I tried finding why it would not load. Turned out that the 3d modle was was not selected properly in Kicad. So after fixing that I reimported the new pcb modle. With the xiao now in place, I was able to cut out the hole for the USB-C. This part I strougled due to the xiao sitting a good way in the case. I was afraid the the hole prevented the cable from going in so I extended the edges a good amount. I used my usb-c as a refrence, where I cut out the perfect amount, hopefully. After finishing all that I noticed the case was looking a bit too thick! so i cut it in have and took out a good chunk so now it looks very thin. This design turned out be a very nice design that stuck out which was gonna go super well with my set up!!!

[Time spent this session: 3hrs]

![image](https://github.com/user-attachments/assets/a94d6763-3f13-436a-ae34-1ebe420b812d)

The next day on 8th I finished the theoretical code where I mapped buttons on my macropad. The top row of buttons I chose to take a screen shot and open VScode. The rotery incoder I decided would be nice to change tabs. I felt this would be the most important funtion becuase I struggle to change my tabs using hotkeys like those people who literaly know all the button functions and change tabs to fast!! The rest of the keys, I changed to copy and past while the slider was set to volume controle. These are not entierly the macros I plan to have. I am thinking for future projects to be able to controle them wiht this macropad which would be very useful as a controler. I still dont know what to display on oled screen so I plan to do it when I hopefully get the macropad. While mapping these functions I refured back to github of from the macropad turoial to help me through the kmk coding! 

For now I feel that I am finally done with the design and the coding part!!! Only thing left now is looking for the PARTSSS!!!

![image](https://github.com/user-attachments/assets/3c5daa86-7c0d-4ffe-9e4b-a7940b4e6b8c)


[Time spent this session: 45mins]




