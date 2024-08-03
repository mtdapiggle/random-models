# random-models
# session 1:
so i just found out that by putting a hashtag in front of some text, it makes it larger and bold. in this repositry i kinda wanted to make some small models of stuff that you can put on your desk for fun. or maybe paper weights uh ya.
i also did this in fusion 360 because i heard that fusion 360 is used by a lot of people and is popular, because this is my first time going into fusion 360, i'll leave my view on fusion 360 and see if i like it 
i also did a fusion 360 tutorial before this to sort of see how fusion 360 is like.
i wanted to start with a container ship and maybe also make some small containers that you may? be able to store things in them and maybe be stackable.
i started off by making a rectangle that would note how much space that the ship would take up. then i started making the bow of the ship or the front by using a 3 point arc, then a straight line and then a fillet. then i mirrored it across a construction line so i didn't have to do it all again. whilst i was doing this, i found out that there aren't as many keybinds as there are in onshape. when i tried to make a fillet i instinctively hit shift + f which is the keybind to fillet on onshape. 
![image](https://github.com/user-attachments/assets/cdb20683-a065-4629-8818-d0b9ead9bca6)
then to make the bottom of the ship, i copy and pasted the bow. one thing i did notice about fusion 360 when copy and pasting, is that it pastes it on where the stuff that you were copying is, compared to onshape (which is what i usually use) which pastes it on your mouse cursor. 
i then sketched the back of the ship (btw the bottom is going to be flat, since it'll be a pain to print with supports (i've had bad experiences with supports) and it can't really balance by itself)
![image](https://github.com/user-attachments/assets/b8651252-9b45-4628-9277-18469f3a4411)
i then extruded the top of the ship out and offsetted it so that i can use a loft to connect the top and the bottom together. i used the loft and it didn't really turn out how i wanted it to turn out.
![image](https://github.com/user-attachments/assets/131d8c17-cde7-4da1-b9b3-f7102ae9d4e7)
i kinda wanted the bow to curve a little bit, and some of the edges to be tangent with the top of the ship. i decided to make the offset lower and make a guiding line for the bow. 
![image](https://github.com/user-attachments/assets/cd356153-97dc-42f2-9c19-95f8a20e4fa8)
i wasn't really sure how to make the edges tangent, so i put that off for now
![image](https://github.com/user-attachments/assets/4d014983-0a34-4373-8794-af39600b4d67)
i put the loft in and holy... the result was what i wanted, the rest of the edges on the bow were curved as well, so i wanted to see if making the guiding line tangent to the top of the ship would make the rest of the edges tangented.
![image](https://github.com/user-attachments/assets/2b48187b-b9d3-49a5-9b21-de7549b781f5)
honestly, it wasn't too bad, but i didn't entirely like how the bottom of the ship was slowly arcing away (even though that's how it is on real container ships) so i wanted to make a compromise between the tangent and the non tangented curve. 
i zoomed out and saw this. 
![image](https://github.com/user-attachments/assets/5d13095b-7a73-4974-a92b-9dd68ba4503a)
i guess this was a byproduct of making the guiding line for the bow, so i had to make a guiding line for the back end of the ship.
**session end**
(also hakkuun broke right after the session ended) (when i say broke, it got stuck at 15 minutes left and didn't go down anymore D:)
![image](https://github.com/user-attachments/assets/e3c10ef4-b1c0-427e-a863-14f895dd0030)
# session 2:
i made a guiding  line for the back end, it didn't really work. 
![image](https://github.com/user-attachments/assets/e51b0d0b-b797-4d7b-9e0c-ba9776b48037)
i was confused on why it didn't work and i wondered if i made an arc that went in the opposite direction, would it make it flat? i kinda had to try because i had no other option.
![image](https://github.com/user-attachments/assets/c23e73ea-be78-4425-a654-65b5880ffd48)
yeah it kinda worked, it'd be really hard for me to make it completely flat but this was close enough and i was happy with it.
the next thing i wanted to do was add on some containers onto the top of the ship
i was about to start sketching on the top, but i saw this.
![image](https://github.com/user-attachments/assets/1e5c6d8d-b7ca-47eb-bd7f-d928f230f033)
well.. not much i can do. i wasn't really sure how to fix this, and i didn't like how it looked this way, so i wondered if i extruded out a line and used it as a guide rail, would it work??
the loft broke when i made the rectangle that i was about to extrude, but that wasn't my current problem.
for some reason the rectangle/the entire sketch didn't show up when i tried to extrude it
![image](https://github.com/user-attachments/assets/45f4e803-e7a9-4ee5-b992-118a2d5a6c64)
where sketch ???
the sketch shows up when i edit it 
![image](https://github.com/user-attachments/assets/ec1e1753-fd9e-475f-ad62-900eb9bd5dc8)
i had to search up why it wasn't visible, and it was because the sketch was set on non visible. i have no idea how that happened, but it did
but then for some reason when i tried to extrude it, nothing happened? i right clicked on the sketch and realised that i had to show the profile of the sketch. i love fusion 360.
i extruded the rectangle out, but realised that i couldn't add the edges of the rectangles as guides, although it probably wouldn't have ended well. also, unlike onshape whenever you set the extrude setting to new part, it makes an entirely separate part. in fusion 360 it makes a new body? which seems to just merge it from what i can see, although there is a join setting, so idk what it does.
i looked for a way to make a new plane so the rectangle wouldn't be visible in the end. 
i made a new plane through the construct tab, and i had to delete the extrude which also deleted the loft at the same time
**session end**

# session 3:
i sketched onto the new plane 2 lines to be used as rails, but it didn't work when i tried to use loft.
![image](https://github.com/user-attachments/assets/8ed4d0a7-b7c6-4ed5-8adf-c14916e32df5)
i had no idea how to fix it, so i looked back to the old solution and wondered if i could use more lines to define the path of the loft.
then i had another idea, what if i separated the part where it has a curve and the part where it's flat, so then the rail wouldn't impact on the other part and then i could simply just join them together.
![image](https://github.com/user-attachments/assets/bbccaf16-8600-4cf2-96b1-ca367a18a726)
the first part was a bit wacky, so i decided that instead of using loft to connect the 2 parts, i would have to use extrude instead.
i attempted to use loft to connect the bottom part of the ship to the top part, but it didn't work. 
![image](https://github.com/user-attachments/assets/6f686440-869f-4045-8e55-3fabe5a463c7)
i thought that maybe it was because the curve from the first part was intefering, so i cut that part out by using extrude and the cut operation. 
![image](https://github.com/user-attachments/assets/8b54c4fb-19dd-46b7-8fbb-98cc7d790285)
yippee
i also felt that it was kinda tall now, considering i haven't even added any containers or the tower where the captain controls everything, so i decided to make it shorter.
![image](https://github.com/user-attachments/assets/5579cfe8-9d21-4e34-b8a9-768807a02bbe)
that's not good.
i realised that it must've been from the extrude and cut operation that i did earlier, since i forgot to change the height of that after making it shorter.
![image](https://github.com/user-attachments/assets/47fb4244-71dd-4906-b38f-e0d764c4084b)
epic.
i wanted to add a fillet so i went back to sketch 1 and tried to add a fillet
![image](https://github.com/user-attachments/assets/d9279a29-78aa-4b7e-a159-142dcffc0985)
honestly it might not be what i want (it's definitely not what i want), i couldn't find a way to get this to work, so i tried to use the 3d fillet, the 3d fillet was a bit annoying, since i had to do it one by one until i realised that you can shift click to select multiple edges at once. i filleted all of the edges that i could/the edges that i wanted to fillet.
![image](https://github.com/user-attachments/assets/51e29d3a-384b-4656-832c-47e91dfdcd54)
for the containers, i started out by sketching the space that i would use for containers.
![image](https://github.com/user-attachments/assets/3bdf7995-0073-4bc5-a88a-4243d43ed03e)
it also gave me around 10 mm by 14 mm of space to place the conning tower (i searched up what the tower on a container ship is called, and i thought that conning towers only applied to submarines but apparently not)
i also wanted to make the amount of containers varying on each column, so i would have to manually make each column or at least extrude multiple times.
**session end**
i kinda wanted to see what the cargo ship looked like in a slicer, so i tried to put it into anycubic slicer and it said that the weight was 0 and that the object had been removed from the model. i had no idea why this was happening, maybe i wasn't exporting it correctly, so i looked around and realised that i could've exported it in .stl instead of a step file. maybe it was because i selected a face and thought that it was like onshape, where it would just select the entire part for exporting.

# session 4:
i made the container to be 1mm by 2.5mm, and used a rectangular pattern to make the containers. one thing that i do like about fusion 360's rectangular pattern is that you only specify the end point of the pattern and then input how many instances you want, compared to onshape's linear patterning, where you specify the distance between each instance and you have to calculate how much space you have between the first instance and the second to make it fit.
for example:
![image](https://github.com/user-attachments/assets/708d637d-4de3-480d-bb0a-5368e6af5394)
i spent some time playing around with the amount of containers that i wanted to put and did some calculating to see the gap between each instances (although yeah i did say that calculating distance between the first and second instance is the downside of onshape and i am calculating the distance between each instance but uh... i just kinda like it)
one thing that was kinda emphasised to me about cadding is scale, it looks big in cad but could be really small in real life, which is why i always keep a ruler next to me just to refer to real life measurements. i originally wanted to have 10-11 containers per row, but then i realised that the gap would be absolutely tiny between each container.
![image](https://github.com/user-attachments/assets/20a533e4-32d4-41fa-96ba-dcd576225723)
i made it 10 by 8, but i kinda realised that i wanted it to be 10 by 7 but i didn't know how to change the amount. onshape has the amount clearly shown whilst fusion 360 didn't really have it displayed anywhere. i had to click the rectangular pattern symbol on the sketch to change it. then i realised that the containers were too small in width, since they were literally smaller in width than the distance between each container. then i realised that i had to change a bunch of different dimensions so that the containers could be actually seeable. then i realised that the ship is small. 
i wanted a few more containers so i added 3 at the front. but then i realised that it was kinda too much and even then, i wanted to reduce the amount of containers again.
i spent a lot of this time trying to decide how many containers i wanted without making it look too tall. i also wanted to make the containers look a bit chaotic with the height of each column.
![image](https://github.com/user-attachments/assets/9c5cf26f-3bfa-4684-995d-e25101b97b58)
i like this sort of chaotic but orderly feel of the containers, they're all in strict rows and columns but the height of each column feels random and chaotic.
i also started work on the conning tower or bridge, i've got the rough shape down and going to add some small details like windows and stuff like that. 

# session 5:
at the end of each session (from session 4) i check the .stl file in a slicer and i kinda realised that the ship was too tall (yeah i know that i've changed the height like 5 different times, but this time, SURELY it'll stay at 15mmm tall. what i realised about the height when looking at pictures of container ships is that the height of the containers usually are taller than the height of the hull, so it'll stay at 15 mm tall) 
i started by making the structural ribs on the side of the bridge/conning tower
![image](https://github.com/user-attachments/assets/6f41d493-3bdb-4ca1-8dcb-d0c92550c7ad)
ribs highlighted in red
![image](https://github.com/user-attachments/assets/1d912906-e350-438d-96b7-d286115df331)
then i attempted to use draft to make the bridge look a bit better
![image](https://github.com/user-attachments/assets/7a40608c-a12a-4ef2-8f7b-e7a1ddd07395)
but whenever i tried to select the faces, it'll end up really weird and selecting a bunch of other faces that i don't wnat to select, so i had to find another way.
![image](https://github.com/user-attachments/assets/e11d88a0-4ee2-4038-87c8-37d30bed3f35)
i just sketched the cross-section and extruded it because i didn't want to deal with any other weird things that could happen.
then i added some cylinders and spheres on the top of the bridge, this was one of the hardest things to do, since the points were being really wacky and not going in places where i wanted them to go.
the finished product:

![image](https://github.com/user-attachments/assets/3c474444-ae64-4f2a-bfc4-4ebfefa58c94)
it was only after this, at 11 pm (way past my bedtime) that i realised i hadn't done /hack and this entire session is pretty much kinda voided, so i'll submit this the day after somehow, some way.
**session end**
some extra comments, i did the windows and stuff and filleted a bunch of edges.

# making an aircraft carrier
# session 1
at the start of the session, i copied the container ship into a new file so i didn't have to make an entirely new hull. for some reason it didn't show up for like 2 minutes after i copied it. i tried to open it but it said that i had to update fusion 360 because i had used a different computer to do the original container ship, which had updated to the newest version of fusion 360. i also jarred 2 of my fingers on my left hand, which although isn't my dominant hand, it's harder for me to type fast/hit keybinds for things. the update bar is currently stuck at 98%. and it finally finished. 
![image](https://github.com/user-attachments/assets/fe2b1904-6121-42ab-8ca8-bbc7e6e69901)
i attempted to extend the size of the hull, which didn't end well, not only did the guiding lines/rails at the back broke, but the bottom of the ship broke. really badly.
![image](https://github.com/user-attachments/assets/65170204-f662-4eae-a56c-3e4e6b7d0032)
i tried to click the cube to go back to the middle after deleting all of the messed up stuff, but it didn't work so i had to search it up. 
now i had some big problems, the entire sketch was now undefined and things were being wonky. it probably would've been better to just make a new hull. 
![image](https://github.com/user-attachments/assets/2a973eaf-ddbf-4eb6-b64e-a2a3b9e101f8)
i also had to fix the front bow of the ship and it wasn't entirely fun. 
![image](https://github.com/user-attachments/assets/c6f4f2b0-a817-4320-a645-5f24bee463ac)
the front bow is slowly making me lose braincells, so i decided to just make a new hull entirely, even though i copied the hull just to save some time, it probably would've been better to just make a new hull. 
whilst trying to lock down the point of the spline, i found out that you can use the fix/unfix tool to lock the position of the point. this is another upside of fusion 360, which also comes from the fact that fusion 360 uses a grid and allows you to lock points on the grid.
![image](https://github.com/user-attachments/assets/f6d28157-c1d2-44f2-a74a-31a2dde14d84)
i looked at my reference image and realised that the front bow isn't really accurate, so i had to do it again. i also felt like that the aircraft carrier would be too short and even too thin, so i extended the hull again (and hoped for nothing weird happening.)
![image](https://github.com/user-attachments/assets/ff7c86a1-38d3-437e-b57c-29a90b8f81fb)
i was confused on what went wrong, then i noticed that the line on the left was green, meaning that i had used the fix tool on it. so i had to unfix it.
![image](https://github.com/user-attachments/assets/83aaa069-e61d-4fde-8110-bc53ed0d3a2f)
well that's not good.

# session 2
the hardest bit is trying to model the back, since there are rarely any pictures of the back of aircraft carriers, which is kinda fair since aircraft carriers look better from the front.
![image](https://github.com/user-attachments/assets/c0dc7000-8df8-4dba-8ea5-be241029d88f)
i found this image which seemed to just be a render of the USS Gerald R Ford, not a real picture, and i think the render is accurate, but i wanted a picture. 
i eventually found a video and some more resources, and i got started.
![image](https://github.com/user-attachments/assets/3d0fcf61-9f89-4aa0-9bf0-724d8e2b1d67)
i was able to finish the back after checking the reference images and adjusting some things.
i also realised that i needed to model the carrier deck and use some loft shenanigans to somehow connect it all up. another big hurdle i'd have to overcome is this thing.
![image](https://github.com/user-attachments/assets/67e38445-1ace-40af-b05e-d6be04344419)
how.
when i was looking at a top down view of the carrier deck, i kinda realised that i made the bow wrong again. hopefully i don't need to remake it again. 
i made a start on the carrier deck and even started measuring the picture with a ruler to get a ratio of the length of the sides.
![image](https://github.com/user-attachments/assets/50cae0a2-1fc3-4acc-972d-dff5efffdd06)
there was a major problem, the lines highlighted in red are meant to be the same line, and in my sketch, the hull would be showing if i were to extrude it out from this point. i probably would have to somehow make the hull thinner.

# session 3:
i decided that i shouldn't make the hull thinner, as it's already kinda the perfect size, so i decided to scale up each side/line by 1 mm. 
![image](https://github.com/user-attachments/assets/57899852-fcbb-4dca-99bc-99d1ff018750)
i also made the front line to not be symmetrical to make sure it'd work. then when i was watching a video of the USS Gerald R Ford, i realised that there  is a signifcant overhang from the carrier deck, and that i needed to make the hull thinner to accomodate the carrier deck. 
![image](https://github.com/user-attachments/assets/117292f5-b785-4b4b-a3cb-dba481200dc0)
i made it 20mm and it looks much better now
![image](https://github.com/user-attachments/assets/6a1b3691-62a5-42fe-81b9-ec91ab917d7d)
after tweaking some dimensions, it looks fine to me. although i checked the distance between the carrier deck and the hull and realised that it was still too low, i wanted around 7-8 mm of space, but i can only get around 4 mm without it becoming weird. this was a major problem and i couldn't move ahead without fixing it, and i really am getting bogged down, with no idea how on how to fix it. it also doesn't help that the overhang needs to be the same on both sides. then i realised i made a big mistake. i checked the wikipedia page of the USS Gerald R Ford, and found out that the width of the hull is only 1/8th of the length, so it only needed to be around 10 mm. AHKFLKJFJLJKJGAHLG;HLGLJJAGJ;LKGAJLKGAJJ;LKG;LKJKAJ;LGKJLKJ;LOIJ[QOIQIOUQPOIUTPIUOTUYP 

# session 4:
i tried to get in some small details like this:
![image](https://github.com/user-attachments/assets/c393fc50-12e0-4953-8927-ccf3ac536f1d)
although, i should probably get started on the hull of the ship. 
i had some problems with guide rails where they didn't show up at all, and i had to look into the folders to make them visible (even when i configured them to be visible)
![image](https://github.com/user-attachments/assets/8185fbc8-3186-454a-945b-b030de6121e8)
it also said something about not liking profile edges being nearly coincident, although when i was doing the container ship, some of the edges were coincident and it was fine ???
it was fine without the guide rail, but with the guide rail it broke. i thought it could be somehthing with the guide rail not being coincident with some of the edges of the top and bottom profile, but i had used the coincident constraint on them already. 
in the end, i just decided to cut out the curve, i have no idea how to fix it. but, something pulled me back (i wanted it to be perfect), so i thought that it could be that the gap between the two profiles is too little. 
![image](https://github.com/user-attachments/assets/f4940b7e-b749-433f-a826-016c9b83962c)
i probably needed to expand the distance (arrows in red) so that it would work. i expanded the distance to how far i was willing to expand it, and...
![image](https://github.com/user-attachments/assets/815f9fa1-676a-4b4e-bb31-db60fe44d0ff)
it didn't work. yippee. 
![image](https://github.com/user-attachments/assets/eff51b87-78cf-48c9-b329-38f86907b2c7)
it's alright, but something just feels wrong about it, i'm not sure, but i probably need to make it even lower and add some more things on the sides so that it doesn't look like just a loft.

# session 5:
i felt like the thing that made it feel wrong was the height, so i lowered the carrier deck closer to the ground and lowered the different loft planes. 
![image](https://github.com/user-attachments/assets/18bcd3d9-8e61-4568-b6c6-2e5aa1660ab9)
i added some little platforms at the back, although they look a bit out of place so i moved them up. i didn't know how to connect the platforms to the loft, i attempted to use a loft to connect it, but there were some gaps
![image](https://github.com/user-attachments/assets/65769130-c9e6-498e-8835-b0a76a8132d2)
i attempted to use another loft to fix it
![image](https://github.com/user-attachments/assets/35c78977-9293-486a-a443-9aecdab75aac)
i mean, i am already using several lofts so... other than this, i wasn't sure on how to fix it. i thought of trying to do this loft (the loft for the platforms) and then the main loft. i attempted to move the loft features on the history marker, but it didn't work, so i had to redo the loft. 
![image](https://github.com/user-attachments/assets/720f87ea-d995-414d-9b2c-f3bbc24a34c1)
it didn't work and messed up the 2nd loft that i was trying to do. so, i thought that if i do the loft normally then get the cross-section of the loft and just extruded it, it could maybe work (maybe).
![image](https://github.com/user-attachments/assets/7929a566-cd86-4cd6-8088-db8f314378b5)
i sketched out the cross section of the loft and attempted it again.
![image](https://github.com/user-attachments/assets/946aaa74-64d7-42c5-97dd-7c36136f0ecc)
it didn't really work. i then quickly realised that i sketched the wrong cross-section and would've resulted in the same thing as the loft. so, i had to change the sketch
![image](https://github.com/user-attachments/assets/783058ca-ea40-4615-831f-fd5e0ecb239c)
it works, but the platform still sticks out like a sore thumb, i attempted to use a loft on the entire side of the hull and the platform, which didn't work, then i tried to use loft on the gap between the platform and the hull, which worked, even though it failed before. it kinda confused me on why it worked this time.
![image](https://github.com/user-attachments/assets/93cdc27e-23d5-4838-8ec8-3c66abca9ded)
this time when i did it, i couldn't do the loft, i guess because the extrude filled up the hole, so i had to alter the sketch to add in an extra area to extrude.
![image](https://github.com/user-attachments/assets/4a86e2c1-47f8-4800-aa73-c7e2c3dbed61)
i don't really like how it looks, so i thought of maybe using the extrude and cut operation, and it worked, i like it now.
whilst i was getting a screenshot of it to put here, i noticed something.
![image](https://github.com/user-attachments/assets/c0d7e342-8dc4-4a8d-9ebf-ddc470908765)
oh my god. IT'S SO SMALL YET IT ANNOYS ME SO MUCH, HOW CAN THIS HAPPPPENENNNNFJLKJFLK;ASDJFS;KALJFSA;LKFDJAFDLK;SJFA;FDJKASDJF;ALSDFJAS;LKFJASLD;F
![image](https://github.com/user-attachments/assets/666cc967-d637-4591-b812-41fbbd7da208)
well i attempted to use loft to fix it, it didn't work. now it's even smaller and makes me go insane. i attempted to use extrude which didn't work either. then i realised that the problem was most likely the extrude and cut operation cutting too deep into the hull. 
![image](https://github.com/user-attachments/assets/966c832a-1203-4c45-a95a-6433426574a4)
it's gone. yiiiiiipppppppppeeeeeeee !!!
**session end**

# session 6:
so one "little" thing i noticed after checking some reference images, is that the platforms aren't like what my cad is
![image](https://github.com/user-attachments/assets/41bf0573-687c-499d-b8aa-b1bdcb025b66)
it's quite different. i also realised that it's fine if it sticks out, since that's what it looks like on the real aircraft carrier. i also have to cut out some parts in the hull and change some things. but first, to make sure i don't mess up again, i had to keep on checking the photos. i actually had to make the platforms thicker
![image](https://github.com/user-attachments/assets/54267074-5704-465a-8c25-ee91549abdec)
i cut out a little section by sketching on the carrier deck and using the cut operation to cut the section out, i also had to offset it so that it won't cut out some of the carrier deck. i also wanted to do some cleaning up as well. i couldn't do this on the older sketch though, since i wouldn't be able to reference certain parts/edges of the hull. 
![image](https://github.com/user-attachments/assets/157d29fd-0dd6-47f9-b9b0-9cea75030996)
whenever i tried to coincident the point of the line to the edge of the hull, it doesn't work and it puts the line onto the edge. this confuses me. then i realised that the line was actually fine after all, and that i thought that the line was just another edge of the hull. (fun.) after much pain, i was able to complete the sketch. 
![image](https://github.com/user-attachments/assets/0a93d3e2-3a1a-4965-89f6-8d1a9a70c77a)
it looks absolutely CLEAN right now, i'm liking it.
![image](https://github.com/user-attachments/assets/9887f68c-a21e-4157-9e43-cdbaf0433032)
of course, i had to check if i did it right. i kinda did it right, although it isn't really just a straight line from the hull to the platform, but rather 3 different straight lines. (ok wait nevermind it's 2 straight lines)
![image](https://github.com/user-attachments/assets/14f2f756-9dc9-428a-bc34-6fd8a324274a)
i attempted to extrude my sketch, and realised that it didn't create a shape. i didn't know how to fix it because it was fully constrained.  
![image](https://github.com/user-attachments/assets/6171fd96-3a69-4ed7-a15c-9e7f42515630)
apparently creating another shape was perfectly fine, but for some reason the first one just doesn't work ???
![image](https://github.com/user-attachments/assets/d7a530ad-ee8f-4f68-b221-9609f3baca0b)
OK WOW. WHY . JUST WHY DID IT RANDOMLY WORKKKKKK WHY DID IT EVEN FAIL IN THE FIRST PLACE. it was constrainedddddd.
![image](https://github.com/user-attachments/assets/ab570849-e5e2-4a2d-87cf-497a9aedb436)
i managed to finish it.

# session 7:
doing this on the right side is going to be hard, considering there is also a CIWS mount and some extra bits that are sticking out. this is going to be extremely fun to cad. (not.)
![image](https://github.com/user-attachments/assets/709fc7ba-602f-42df-9f2e-4f18da16ea20)
as you can tell, it sticks out, and not just like a straight rectangle. so, i decided to put that off for now and to work on other things that are on the back of the ship. 
![image](https://github.com/user-attachments/assets/14199c08-8a1f-4eb0-a19d-8f00ff614893)
i managed to find this really good image of the back of the ship, and also made me realise that i probably should make the ship shorter (again.)
![image](https://github.com/user-attachments/assets/3b65bad9-a50a-4edd-9685-bdf4a4161e37)
ok what the flip, i can't even make it shorter ??
i eventually realised that i made the extrusion too thin. making it shorter also broke a few things
![image](https://github.com/user-attachments/assets/94907d47-ddbe-4be1-97e1-57edf155103e)
why is there a small gap...
then i realised that the problem was the extrude and cut operation
![image](https://github.com/user-attachments/assets/f06f342d-1fd6-4009-a4ad-4b27b37d443e)
i measured and found out that i needed to reduce the rectangle by 1.153 mm.
![image](https://github.com/user-attachments/assets/bc2ba2ef-7417-41fa-93d8-5e6ad45837a5)
oh god.
i decided to just do a bandaid fix of sketching out the profile of the bit that was missing and then extruding it. 
![image](https://github.com/user-attachments/assets/c929c7b2-b9f9-4287-99d9-c4071d23b1df)
i had no idea on how to reference the edges or the points, then i realised that i could've just put the sketch on the face that has the problem. i also realised that the areas that i could view the sketch weren't very ideal and it gave me a hard time when trying to fix it. then i realised, by trying to dimension the line to the point creates a point on the sketch plane where i would be able to use coincident.
![image](https://github.com/user-attachments/assets/487fe843-bffb-4bde-a810-4e0fb9a5dd8c)
one downside of fusion 360 which isn't really a downside, it's just that i kinda miss it form onshape  is that i can't pick 0 to be a dimension which makes me sad, but it's fine anyways since it can be fixed and other things can be done to mitigate it, like the coincident constraint. but i wasn't able to do the coincident constraint on the point until i used the dimension tool. 
![image](https://github.com/user-attachments/assets/a8b78e4d-95b2-49cc-8975-759006639323)
you have got to be kidding me. it's so small, that i'm not bothered to fix it, and hopefully it isn't that noticeable unlike the other problems that i fix.
![image](https://github.com/user-attachments/assets/088d177c-8ecd-43f7-a9c4-a6e4d2ca7faa)
using fillets and lines, i managed to create some part of the back of the ship, although i do have to create a platform that juts out from the back and the platform and mount for the CIWS.

# session 8:
i realised that there were some things that were misaligned when looking at the aircraft carrier. 
![image](https://github.com/user-attachments/assets/9521b31d-28d6-4b38-957f-e5fa3eab0d50)
i measured the distance between the side of the hanger door and the end of the aircraft carrier. it's 9.663 mm, so i changed the extrude, and there still is an edge line between the two different faces. then i found out that instead of using dimensions, i could use the "To Object" extent type so there wouldn't be an edge line. i also changed the operation to join, so that it would become one body. there wasn't a line anymore which is nice. 
![image](https://github.com/user-attachments/assets/7bb1c034-0ed7-4768-8b7d-2cbe2f64ae29)
i attempted to fix the faces for the side as well, although the difference is so minute, i could probably ignore it, but with the line in the cad still visible it kinda annoys me. although, i kinda have to ignore it since i don't think i can fix it, and even when 3d printing it won't even show up as a different edge/face/thing.
i made the back platform of the ship
![image](https://github.com/user-attachments/assets/61613a53-d30b-4162-b7b5-d005c228f6a8)
![image](https://github.com/user-attachments/assets/1580a05a-74d9-4584-bbfc-35812c32904a)
it was at this point, that i realised that these parts
![image](https://github.com/user-attachments/assets/acb8632a-9b55-4b02-873b-9009b47fdd1c)
are meant to be really small, and the platforms are meant to be much thicker. this meant that i probably needed to lower the height again, and probably cause some problems to some things. 
![image](https://github.com/user-attachments/assets/0ac7de5c-f036-4d10-85e2-1d1f007b7328)
yeah things are going wrong. 
![image](https://github.com/user-attachments/assets/38664fb0-8fbb-4edd-af87-372e9b8e077e)
so i tried to adjust the sketch at the back of the ship, and it's not going very well at all. my god.
![image](https://github.com/user-attachments/assets/f658056c-cc1c-4a66-9b03-edcc5eb68d45)
yeah it's going really badly now. 
![image](https://github.com/user-attachments/assets/d05942c4-8f64-442e-a74e-f88f3d545df8)
ok so i kinda fixed it, but it's not really entirely fixed either.

# session 9: 
i tried to fix the part that wasn't flush with the other edges, i couldn't use the coincident constraint because the line wouldn't show up for some reason, then i did the thing that i did before, where i used dimension, which created a point on the line and allowed me to make the line. 
![image](https://github.com/user-attachments/assets/7c3a6307-cea8-4b1a-95d6-b69167eead75)
what the flip. then i realised that i had put a parallel constraint on the line, because thought that they were going to be parallel, turns out they aren't. the bad part now, is that i can't select the face, so i had to hide the aircraft carrier to click on the face. 
![image](https://github.com/user-attachments/assets/a112e9a1-f85a-49f7-acf8-cd8095be9db4)
when i hid the aircraft carrier i realised that there was a separate body to the main aircraft carrier
![image](https://github.com/user-attachments/assets/33530cd5-4405-4bbc-961b-2e44987ba4ee)
aw hell nah, luckily it was fixable with a loft. 
![image](https://github.com/user-attachments/assets/f69b35c0-1a74-45e6-895e-e23679d3a5d8)
when i went to check on the body that had been created, i realised that it was no longer there, which must've been because i hadn't fixed the faces and the stuff that had gone wrong. 
![image](https://github.com/user-attachments/assets/c016ef61-ffd9-460e-b074-5dc888861fa3)
this bit here looked a bit off, so i checked my reference images and realised that the hanger door is flush with the hull,  meaning i had gone to all the effort to fix up some things, when it wasn't even accurate. yippee.
![image](https://github.com/user-attachments/assets/7b44ad1d-2545-441f-a68e-601999d16d25)
something might just be a little wrong here. i was able to fix it by adjusting the recatangle's dimensions.
![image](https://github.com/user-attachments/assets/8a8c86c4-d217-4904-9c76-fc99965942ea)
ok so i sketched out the CIWS mount and when i exited the sketch, there was a new body. how. 
![image](https://github.com/user-attachments/assets/a91288fb-a365-4c03-b16d-1a1aa52065ed)
bro i thought it got fixed. apparently not. i had to change the operation to a join operation instead of new body.
![image](https://github.com/user-attachments/assets/3ca968b5-1fff-4785-bbd7-badd4b56c2d9)
i was having a couple of problems with this, mainly that the loft doesn't really look right. 
![image](https://github.com/user-attachments/assets/89aafe97-c82b-4473-914b-2ed4a913f90c)
this part didn't really look right, but the session ended right after i did it.

# session 10: 
![image](https://github.com/user-attachments/assets/59404a7e-67ed-4d32-ab0a-eab53cafce6e)
i adjusted the sketch lines and it looks fine now. i got started on the CIWS mount, and maybe making a CIWS? it's a possibility, but i'm not sure how you could 3d print it and get the supports out, because it's going to be tiny, although it would look reallllyyy good with it, so...
![image](https://github.com/user-attachments/assets/704d1cf1-aadd-4c02-bbda-485c294aacc8)
i mean it ain't looking bad right now. there are some things that i don't entirely like, but i don't know how else i can do them, so it's probably going to stay like that also, one thing that i will say is that i could potentially do railings, although they would be super small and really annoying to do everywhere. 
![image](https://github.com/user-attachments/assets/910b678c-fc3d-42ab-9255-5a525959160e)
i sketched a circle and centred it in the rectangle, and quickly realised that, as i thought before, it was going to be extremely small. like very, extremely small. 0.8 mm is a really small length and would take a 3D printer around like 5 lines to print. (assuming each line is 0.15mm thick) so i probably should put some type of disclaimer to set the size to 0.1mm. i decided to make the CIWS anyways, because i don't think anybody is going to really 3D print this. 
![image](https://github.com/user-attachments/assets/d7a5cbf3-d728-4d20-aad3-42d2112b1376)
i managed to get some of the mount down for the CIWS. 

# session 11: 
i revolved some faces to create some parts of the mount for the CIWS
![image](https://github.com/user-attachments/assets/41090512-dafa-4260-a085-d5c3f565e389)
i'm gonna be using this as the reference image for the CIWS. i checked the reference images and realised i didn't need the revolves. 
![image](https://github.com/user-attachments/assets/c365d56f-d946-4344-83bd-fedffab6579f)
i created a box and attempted to put some cylinders on it, although i couldn't really reach the face that needed the cylinder. 
![image](https://github.com/user-attachments/assets/567fcae0-2a8b-4436-bc49-3c9d263ac2a0)
i realised that the rectangle needed to become a square so i can fit a cylinder on top of it.
![image](https://github.com/user-attachments/assets/cf238425-3e9b-4682-92a2-48fa45d1b3a8)
ok so a lot of things broke immediately. 
![image](https://github.com/user-attachments/assets/b38b1061-d2d2-407e-a93d-d80d93ebcaa8)
my dimensions are now in the microns... (0.001 mm)
![image](https://github.com/user-attachments/assets/8e233990-9a10-42a4-84ce-ccc364dfbb6d)
why. 
![image](https://github.com/user-attachments/assets/a6093df9-4d78-4785-be12-24abcf596eda)
the phalnax has been completed (and no i wasn't able to get the fillet at the back of the cylinder done)
i also forgot about my session being completed for 20 minutes straight

# session 12: 
i attempted to make the island of the aircraft carrier 
i started out by sketching the profile of the island.
![image](https://github.com/user-attachments/assets/9a3e84d8-70c4-4e7b-ac0a-0d1a346e2d6e)
i used draft to make the angle. 
i realised that i had to make the island a bit taller and then use the extrude and cut operation to make a part of the island. 
![image](https://github.com/user-attachments/assets/09d63736-1832-4012-a352-b7f6ea040c73)
i also had to make the draft smaller, because it stuck out a bit too much. 
![image](https://github.com/user-attachments/assets/b4a6e05e-8a96-46b2-9228-ab2fa755bd31)
i'm going to try and make these windows, i'm not 100% sure on how i'm going to do it, but i feel like i'm going to try and use sweep to make it, although it may not end too well. 
![image](https://github.com/user-attachments/assets/cd3625ef-de3e-43be-bc3f-961a382d7635)
i made some rough dimensions on where i kinda want it to go, then i'm going to sketch out the sweep path and see if it works. though, i feel like it's gonna say something along the lines of "sweep geometry intersects with each other" or something like that, but that's kinda the only idea i have to do this. 
![image](https://github.com/user-attachments/assets/4e3d8d34-42b0-4daa-a83a-72ab14a1c9fd)
i found this really good image of the island, although there are some things that i'm not entirely sure of. 
![image](https://github.com/user-attachments/assets/e9744392-2af6-4b4a-a2e6-51ecffa65dee)
i also had to use this image as well because i couldn't really see the sides from the first image. 
![image](https://github.com/user-attachments/assets/1ab11abb-798c-4c31-ae95-fd99e5675de9)
so it's not tooooo bad but there are some things that i don't like, especially that large gap. i also made it as a new body so i could mirror it over and not have to do this again. (although i will have to do this at least 2 more times to get the 3 layers.)
![image](https://github.com/user-attachments/assets/0a833cf0-8214-4762-a0a7-f00425defa92)
i prob need to extend it more.
![image](https://github.com/user-attachments/assets/5f40c979-2b4a-484f-9254-8609abfbaabe)
i tied to do this so i can make the viewing platform and then use sweep,  but i realised that it'd be too far into the wall, so the platform wouldn't really show. zz
![image](https://github.com/user-attachments/assets/4c16445b-5233-46ae-b194-bb8688f4c7cd)
i couldn't really click on the path so i had to hide the windows, and making the windows a new body kinda helped here because it'd only hide the windows and not the entire ship. 
![image](https://github.com/user-attachments/assets/d9a3e8d8-6077-4570-80f0-09a004ab8084)
i tried to use sweep but it selected the entire other path and not just the path that i wanted. 
![image](https://github.com/user-attachments/assets/b3793d28-b839-4a9d-95c9-440998a4a7f4)
idk why the sweep does this, but it's not what i really wanted. i played around with the settings and found out that taper angle kinda removes it, but makes the end of the platform thicker, so i set the taper
angle to 0.01
![image](https://github.com/user-attachments/assets/cde254b8-f6fc-4548-98d8-ac53e5e7008b)
i kinda like it right now, uhhhh just don't look at the bottom :D (or the top.) i thought that if i sketched a erctangle or something above the windows, i maybeee could make the top (as long as i don't get hit with the "sweep geometry interescts with each other") then i realised, that it'd make it hollow, so i decided to try use extude and the intersect operation.
![image](https://github.com/user-attachments/assets/fffa9929-4fe2-4f49-a367-34bbd7dfb1fd)
as i was making the rectangle i noticed this small gap, so i had to change the sweep path again.
![image](https://github.com/user-attachments/assets/f14f3cce-0fda-4834-bdcd-3f6baac31a3c)
i realised my critical mistake was that i didn't think properly on how intersect works, must've been the 5 hours of sleep.

# session 13:
i realised something that i probably should've realised earlier, but i could've just extruded the sweep path (the area that the sweep path contains) and then just add a bit on each side. (i probably didn't explain it very well, i'll show some screenshots.)
![image](https://github.com/user-attachments/assets/e8f0a1b2-6207-4282-b606-91e470edeff5)
i used the offset tool in the sketch so i could also fill the area at the bottom, i tried to extrude it and it didn't work, then i realised that i needed to close the ends of the offset so that it would be a shape/profile that i can extrude.
![image](https://github.com/user-attachments/assets/0ee2c8be-8ca3-4e54-8ec7-6864fbbe419c)
the bottom was fully sealed, and now i just needed to use loft on the top areas to finish it.
![image](https://github.com/user-attachments/assets/f07f647d-d645-4f82-a6d4-1c09ac21a8d1)
epic. now i just had to mirror it across a plane, but i realised that it had merged with the main body of the ship. so i looked around in the mirror menu thingy and realised that you could mirror features, so i used that to mirror it over.
![image](https://github.com/user-attachments/assets/71ecc2f1-64c1-4998-a036-a2fc38748cf9)
i think i didn't select some specific features,  but when i select the face again, it still doesn't work. i just used loft to fix it.
![image](https://github.com/user-attachments/assets/0adbc99b-b402-463a-a282-b994c000bd54)
i tried to make the 2nd layer by copy and pasting the first layer's sweep profile, but things are going really badly now. i have no idea how to fix this, what the flip happened. only after like 10 straight minutes i realised that i could undo this. i spammed ctrl + z a bunch and then copy and pasted the sweep profile again, but it's fine ??? i'm so confused.
![image](https://github.com/user-attachments/assets/d2389210-5b11-4eb8-8679-3551d7de8244)
i attempted to make a sweep path but even though the plane that the sketch was on was at the same height as the bottom of the sweep profile, i couldn't do things with it.

# session 14:
i remembered that i could dimension something to the sweep profile so it'd show up as something that i can use constraints on, so i did it.
![image](https://github.com/user-attachments/assets/d6aef58d-bd0f-4851-8fda-f3cd1f14313e)
i made the sweep path and then did the same things that i did before to fill in the massive hole in the middle.
![image](https://github.com/user-attachments/assets/be2a8984-df7d-47dc-a7a9-4dad7dd90054)
something is ever so slightly wrong, i made the draft too tall.
![image](https://github.com/user-attachments/assets/5bf7db29-4bc0-4f62-a184-902de2bad343)
good enough
whilst i was checking the reference images to see where exactly the 3rd layer is, i realised that i didn't need to mirror the first layer across the plane, so that wasn't worth it. also my parents are arguing about food D:
![image](https://github.com/user-attachments/assets/d6300883-5531-43df-8fa5-78a568e859f0)
i tried selecting these lines to copy them, but for some reason my cursor wasn't selecting them, i checked in the top right and realised that somehow the selection tool had changed to a paintbrush. so i changed it to a window selection.
![image](https://github.com/user-attachments/assets/59b40806-113e-40ff-84dc-3047220f9974)
i used the coincident constraint to put the sweep profile onto the edge of the draft. 
whilst i was checking the references, i realised that the 3rd layer looks to be directly on top of the 2nd layer, and not slightly in front.
i adjusted it and made the sweep path. 
![image](https://github.com/user-attachments/assets/0c27c6c6-5a53-44c5-b339-71a6bedc53eb)
i did the offset in advance and was about to mirror it all onto the other side of the island. (yes this layer does go onto the other side.) until i realised i forgot to put the rectangle which turns it into a shape so i can plug the hollow areas after doing the sweep. 
![image](https://github.com/user-attachments/assets/f762126e-d584-4301-ae5f-49ac2d0cfecf)
i tried to do the sweep but i realised that i should've done the offset after, because now it thinks that the entire thing is a sweep path because i connected the offset to the normal sweep path.
![image](https://github.com/user-attachments/assets/a747704c-1454-4778-8500-aff8ec217a8a)
honestly that's kinda fair, (i attempted to instead use sweep so i could save some time, i didn't save any time.)
i did use sweep a bit to do it, but i made the amount that i sweeped less, so i could use less lofts. 
![image](https://github.com/user-attachments/assets/70f431fa-0434-49b3-8fed-e2aa78ce894a)
don't mind all the red
![image](https://github.com/user-attachments/assets/bbc3012e-4a86-42a1-97bb-1f5bea840930)
and then another loft
![image](https://github.com/user-attachments/assets/88449b0a-eb31-4553-953d-d7b3a7e8312a)
now i just had to do this on the other side.
![image](https://github.com/user-attachments/assets/007ec0a6-b0ac-4d9f-8442-ca7a44663e7f)
yippppppeeeeeee
as i was looking at my reference images, i realised that i didn't extend the platform far enough, although i wasn't able to finish it before the session ended.

# session 15:
![image](https://github.com/user-attachments/assets/e989855a-f7b6-4f29-9e4f-49b4268cc636)
whilst i was planning to extend the platforms for the viewing areas, when checking the reference images i realised that i had to change the end of the island (the part where it start sloping away.) before i could work on extending the platforms, to more of a draft instead of just a straight cut downwards. i wasn't really sure how to make the draft go on an angle, it straight up took me 10 minutes to come up with a solution, which i didn't know if it would work or not. 
![image](https://github.com/user-attachments/assets/1928a05c-1830-43a8-b1e1-1935934ad555)
i didn't know how far i wanted to extrude/cut. 
![image](https://github.com/user-attachments/assets/7c1b17ec-0326-4af6-9aaa-9cbb7599d2fd)
i created a sketch to check the dimensions, then i remembered i could've just clicked on the planes and points to check the dimensions, but i was too dumb to remember.
![image](https://github.com/user-attachments/assets/c5298e73-b12f-4703-a06c-6e5887c1fb60)
this was kinda what i wanted, but instead of it being smaller at the top and larger at the bottom, i wanted it to be the other way around.
![image](https://github.com/user-attachments/assets/484a6897-d59f-480c-b171-ac6c4b2cd6f5)
this is what i want to do
![image](https://github.com/user-attachments/assets/eac923d6-1b16-4c4c-8651-4408ec2bbd1c)
and this is how it's going. 
this wasn't really how i wanted it to be done, but i felt like i was heading in the right direction, so i thought that if i extruded a rectangle out and then used the draft, maybe it'll work? hopefully
![image](https://github.com/user-attachments/assets/5c232c06-3237-4b5e-8f75-da4fb9948b49)
i wasn't really sure on what dimensions i wanted to put in, so i just threw in some numbers. 
![image](https://github.com/user-attachments/assets/59f68eef-46cd-46eb-8362-a34fe67cae1a)
judging by this, i don't think that this will work, but i'll experiment with it, 
![image](https://github.com/user-attachments/assets/e8da5fa2-7af9-4bb2-9a88-7cb7feb27356)
one problem that i have is that the draft doesn't affect the island, even though the entire aircraft carrier is one body. so i decided to scrap the idea, because i don't think it can work at all.
![image](https://github.com/user-attachments/assets/9e25fe81-223d-43ba-9810-e8e17f00d302)
i settled on this for now, though i want to revisit it eventually.

# session 16:
i was thinking over the end of the island for a bit, then i realised that i could possibly use loft to solve my problems, but i would have to work on the 4th layer before being able to do that, since the 4th layer has a platform going over the end of the island. 
![image](https://github.com/user-attachments/assets/bed120f7-a999-41a4-902c-4f872075e02e)
i had to change the dimensions of the windows because from the images, i could see that the windows are larger on the 4th layer and some things kinda broke. i managed to fix it by making the top line equal to the bottom line. 
![image](https://github.com/user-attachments/assets/a23448c5-32ae-47ee-bb98-e0422d6f7722)
i definitely will have to tweak some things with the dimensions of the island, because it's not tall enough right now. 
![image](https://github.com/user-attachments/assets/69e799f6-dcb2-4948-8d3a-f68228800e22)
i made the sweep, and as you can see it's stickout out the top a little bit, i'll have to change it soon. 
i also realised that the 4th layer's platform is flush with the top of the 3rd layer, so i had to sketch a line on the top of the third layer and then extrude.
![image](https://github.com/user-attachments/assets/a359603b-ffc9-4cc7-a919-fc20aad4cffe)
looks a bit odd right now, but it'll eventually be fine (i just realised that i didn't need the line, ggs)
![image](https://github.com/user-attachments/assets/d913b2c9-7b7d-4718-971f-21983b72bc9f)
that looks better. 

# session 17:
honestly, when i started this, i didn't expect it to take this long to make an aircraft carrier, but then again i kinda suck at cadding and i guess this is a way that i can improve it. 
anyways, the main problem that i'm having with the 4th layer's platform, is that the platform is longer than the other platforms on the other layers, but i didn't really have good pictures on how far it goes, so i just assumed that it went all the way around the island. (although, i did find a reference image later that showed me that it did indeed extend all the way around the island, but also made me realised that some things were wrong.)
![image](https://github.com/user-attachments/assets/623e25cc-344f-4a7a-ac63-fa9b14fafd95)
i sketched out the sweep path that the platform will take. 
![image](https://github.com/user-attachments/assets/80050ef4-29f5-40ba-b4d4-96e02ad1fd8b)
it kinda looks ok, but it'll look much better after i change a couple of things. (hopefully) but i was't entirely sure how i was going to use loft to connect the faces. 
i eventually came up with an idea to extrude a chunk of area out of the island, sketch a thin rectangle for one of the loft profiles, and then sketch some areas on the bottom of the platform, when i was sketching on the bottom of the platform, i realised that i would have to  use 2 sketches
![image](https://github.com/user-attachments/assets/f0e9a506-5161-4902-bc30-491f9e9920c9)
and this also means that the loft would need 2 profiles. so, i had to extrude the cut first, so that they would become one singular plane/face. 
![image](https://github.com/user-attachments/assets/def78e50-d3ef-49e1-b57e-8adcaf861f60)
ok maybe i should've adjusted the extrude and cut opeation itself. 
![image](https://github.com/user-attachments/assets/4546e1cc-effe-4121-aea1-4f048fd43a6f)
i adjusted it to here, then realised that i probably should just cut it all the way through. 
![image](https://github.com/user-attachments/assets/9e7ba2f1-952d-41cf-832f-40676858806b)
yeah things are kinda off. 
i realised that i needed to make the cut into the island a bit larger, since there wouldn't be enough space to use a loft and have it angled. 
![image](https://github.com/user-attachments/assets/0d4ebfbf-9968-4f6d-be82-ffd7c4569460)
because i constrained the sweep path in a nice way, i don't have to change it now :D. 
![image](https://github.com/user-attachments/assets/9e7a801b-faf2-495f-a22a-d5b345542ff8)
still no enough space, at this rate the cut will take up 50% of the island, or well, it'll remove 50%. 
![image](https://github.com/user-attachments/assets/03840085-4434-4e0e-ae4a-c436f8218508)
![image](https://github.com/user-attachments/assets/4812d8f3-062c-422f-9285-89c893a57f77)
now it's starting to remove too much, and the back of the island and the sides are soon going to have no space.
![image](https://github.com/user-attachments/assets/ee7405da-e587-40bc-8ac6-7cdec9ee44fe)
i decided to make the island larger, although i feel like this will break a lot of things. 
ok well only one thing broke, and it was the sweep path for the 3rd layer.
![image](https://github.com/user-attachments/assets/8d30d20e-7ee6-43e1-8183-d3c8d85ff048)
ok nvm 2 things broke, i looked at the sketch and realised that i had used the dimension tool instead of using the midpoint constraint, which meant that the mirror had shifted. 

# session 18: 
![image](https://github.com/user-attachments/assets/d9c46b3d-f883-4534-a865-539b6543e1f7)
why is it cutting into the sweep now and not the main island??? i eventually was able to fix it
![image](https://github.com/user-attachments/assets/a39fdf7d-1335-4201-8ab9-af5a9685cf55)
the platform wasn't long enough, yet again. so i had to extend the island, yet again. with the platform being long enough, i started to work on the loft. 
![image](https://github.com/user-attachments/assets/df20bc23-92bd-4d43-9d82-49a123a269da)
i decided that 0.5 mm would be long enough. i mirrored the line so that i wouldn't have to create another sketch on the other side. 
![image](https://github.com/user-attachments/assets/43f6c181-15fd-4ec4-9fd1-d8761cf8f061)
a problem i had was the purple line, which must've come from me dimensioning the line from the sketch to the platform. although i then realised that fusion 360 doesn't care if it's all on the same face.
![image](https://github.com/user-attachments/assets/6cac65cf-7009-4fc9-bea5-a84dbc09f2b0)
the lines that i had used to contain the loft didn't work, i think it's because i may have left one of the points to be not coincident with the edge of the platform. 
![image](https://github.com/user-attachments/assets/b70eccf6-0a46-49a2-9297-b0266cec47aa)
they were coincidented, but one point of the line was constrained to a line, not a point, and the other point on the line was constrained to the wrong point. 
![image](https://github.com/user-attachments/assets/147a1652-8c9b-4821-9102-5f718fe121ab)
why did it break even more than last time. what happened ???
![image](https://github.com/user-attachments/assets/054a6c00-783e-4444-98f0-d08fcd9f9add)
the white point was probably the problem, although i thought that the white point didn't really serve a purpose, but apparently it does. 
![image](https://github.com/user-attachments/assets/79a5cc25-af17-46fe-8571-48f929107aac)
hmmm yeah that doesn't look good. i undid the loft, and looked back at my reference images just to double check if i was going in the right direction. (i kinda was, but kinda wasn't), i realised that the loft had some part of it jutting out of the island, and that the loft doesn't go to the areas where the platform turns. 
![image](https://github.com/user-attachments/assets/4888d0b8-a43e-4ee9-9169-14fd2d5c53cf)
i changed the bottom sketch first
![image](https://github.com/user-attachments/assets/5811d877-8c86-492f-ac5d-36c6af102ac5)
i decided to test this out, although i don't think it'll end very well. 
![image](https://github.com/user-attachments/assets/8064a28b-81eb-4c35-9376-ae063976ac43)
well, it didn't really end well, but i think i know how i can fix this up. 
![image](https://github.com/user-attachments/assets/a4f35e78-cebe-4c94-8949-c452dd5a5f9d)
hopefully this works
![image](https://github.com/user-attachments/assets/784c96b5-f8a8-427a-8c44-d049902aced6)
that looks pretty accurate (it doesn't)
![image](https://github.com/user-attachments/assets/f65febcd-7811-4415-a70c-8f3b9f25e9b0)
and apparently if i redo it, it works. this isn't accurate either. i kinda had exhausted all of the options that i could even think of. so i just started trying random things in hope that one of them would work 
![image](https://github.com/user-attachments/assets/2156368b-9b8a-42e6-bd24-be250013aedd)
that dimension is so faded, i can barely see it. 
![image](https://github.com/user-attachments/assets/3d4f1d6c-2dbd-4c97-b4df-913aaaa18489)
it kinda works... but at the same time... it doesn't really. 
![image](https://github.com/user-attachments/assets/2e820416-2616-4ec6-8b42-b77feb295ca4)
i extended the line and now it looks better.
![image](https://github.com/user-attachments/assets/e3185a5d-c36c-460e-9c13-15b02cfa0d33)
i think i have to adjust the back of the loft, but othe than that it should be fine, maybe. 

# session 19: 
![image](https://github.com/user-attachments/assets/4db01493-993f-4d55-a012-5487696a5154)
i extended the sketch for the loft, so it looks better (i think, the reference images i have don't show the back of the island) with that looking ok, i moved onto the platforms again. 
![image](https://github.com/user-attachments/assets/b0e690c1-073c-47bd-bc99-0492cabddd80)
this part was kinda bugging me, so i sketched a line and then used loft to make the face look better. 
![image](https://github.com/user-attachments/assets/b90895ab-01e5-4620-bf5b-29483a45cb7a)
i checked the reference images to see if everything with the platforms was ok before moving onto extending the sweeps to the loft, and i saw that the platform for layer 4 is thicker than the others
![image](https://github.com/user-attachments/assets/00fed27a-9e55-4734-aee2-757df1caa1a4)
it's also thicker on the sides, meaning that i'd have to adjust the sketch for the sweep profile. 
![image](https://github.com/user-attachments/assets/3ecb61f9-f970-4700-b7e9-3b16a5dce766)
it still didn't work, i checked the sketch and realised that i had constrained the sketch lines incorrectly.
![image](https://github.com/user-attachments/assets/c9e99407-84b5-43ce-afd0-e45faa203292)
it looks fine now, i double checked with the reference images and also realised that the 4th layer's windows were a bit too far back, so i had to adjust the sketch.
![image](https://github.com/user-attachments/assets/3b5a2950-06bf-496d-997f-2f787f0e65d0)
i also realised that the 4th layer cuts into the island a bit. i also kinda think that the island might be a bit too thick, but i can't really do anything without it being too thick, so i decided to increase the length of the sweep path.
![image](https://github.com/user-attachments/assets/142c983c-7299-4e7d-a8f4-11784ff21abd)
i attempted to extend the front of the sweep path by 0.4mm, but it broke. 
![image](https://github.com/user-attachments/assets/7b2b6462-1b7d-48a0-9377-a63bd1c2a020)
ok why is everything  breaking when i try to fix it
![image](https://github.com/user-attachments/assets/d79622cb-f9bd-41fe-b2b3-52ec4ee48ff8)
i deleted the giant rectangle 
![image](https://github.com/user-attachments/assets/6a2722b8-e0b3-413e-9723-3f83fa75a33a)
whilst i was trying to fix the lofts, i realised that the back wasn't going into the island. i managed to fix it, but there was one loft that i didn't use. i don't remember what it was used for, so i deleted it. 
![image](https://github.com/user-attachments/assets/4413d69f-7f5a-4078-9354-4e8c54251a3f)
i also had to use a loft here to fix it up. i eventually just made the platform coincident with the windows on platform 3. 

# session 20: 
![image](https://github.com/user-attachments/assets/8bdd2dc2-75c3-4ae1-83e8-b263728b538e)
i extruded out the area that i was going to use to extend the 4th layer's windows and platform. instead of using sweep and making another sweep path, i just decided to use extrude, because i don't want to mess around with the hassle that is sweep. 
whilst i was checking my reference images to make sure that everything is fine, i realised that i extruded it a bit too far out, and that all of the edges of the platforms here; 
![image](https://github.com/user-attachments/assets/f951ae53-28b0-4e19-880d-3d56effa18e7)
are all above each other vertically (yes i know that's kind of obvious, but they're directly vertical to each other (i think))
![image](https://github.com/user-attachments/assets/e60e13c7-392d-4888-aa5e-35af671c54e0)
i decided to tweak the dimensions of the sweep and change some things, so that it is flush with the 3rd layer's windows
![image](https://github.com/user-attachments/assets/e76a580e-9285-4fb2-afd9-d71c12d7897d)
i also wanted to make this side of the windows longer, since it is kind of short at the moment.
![image](https://github.com/user-attachments/assets/46207e8a-0eb8-441c-9f8a-93e832e653f3)
i didn't really know how to do the top part just yet, so i postponed this to work on extending the platforms. 
i didn't really know how far to extend the platforms without seeing the loft either, because i was working with the original sketch path, which didn't have the loft. 
![image](https://github.com/user-attachments/assets/33cc82e1-7bce-47c2-a5ef-c77e48d96e6c)
i eventually finished the platforms (holy heck i didn't realise that i went over the hour by like 35 minutes whaddaflip)

# session 21:
i can feel this dragging on, and i want to be able to finish this before 25 hours, looking at the scrapbook channel and just seeing all the other people making these cool things, whilst i'm struggling to make an aircraft carrier is kinda hitting my morale hard.
fusion asked me if i wanted to update, but i postponed it because i wanted to really optimise my productivity. first thing i realised when i was looking at the reference images, was that the draft extended out too far from the island. 
![image](https://github.com/user-attachments/assets/678ff785-c3f8-4ecb-a839-694aacf5ae65)
i reduced the size of the extrude to 0.5 in the sketch, but it didn't really fix it, so i looked at the draft. 
![image](https://github.com/user-attachments/assets/f64d6c3f-3630-411c-a0a6-b64671768c9a)
i reduced the angle of the draft from 20 degrees down to 10 degrees, but it made it too flat and the draft looks odd now.
![image](https://github.com/user-attachments/assets/3517dd1a-60df-4071-b275-17a83339e870)
i made the sketch size of the extrude to 0.01 mm, and it turned out ok, so i'm bumping it back up to 20 degrees.
![image](https://github.com/user-attachments/assets/561ed5f7-564c-48de-9ddb-b0edea01f15d)
why, just why. i decided to change it to 15 degrees, as kind of like a compromise between 10 and 20. 
![image](https://github.com/user-attachments/assets/e142a352-15a4-4b12-9690-4b977d345976)
it's just barely, slightly misaligned, but when 3d printed, it won't make too much of a difference. i also realised that the bottom of the 3rd layer's platforms aren't right, so i quickly fixed it up. 
then i decided that i wanted to do the top of the 4th layer.
![image](https://github.com/user-attachments/assets/06af5184-882a-4fb6-b275-f27093e5b4a2)
i wasn't really sure how the top of the 4th layer looks like, so i just did something that i thought would be the shape. i also used some dimensions that i wasn't entirely sure if it was correct.
![image](https://github.com/user-attachments/assets/8ea246d8-976c-43cb-82a1-9ad7532847a4)
i realised that it didn't really work that well. i couldn't really think of a good solution to it. 

# session 22:
honestly, i don't really want to type about what i'm doing because i just want to lock in, i might take some screenshots of problems that i have, and how i tried to solve them. 
![image](https://github.com/user-attachments/assets/c3e155cc-ec18-4ae7-bb74-cee4edb00690)
for the 4th layer top part, i just decided to change the sketch and then spam loft everywhere, it might work. 
![image](https://github.com/user-attachments/assets/8feb6159-85af-4052-b64a-43a126816aae)
i can see that the extrude isn't really correct, probably is because i didn't adjust it yet. 
![image](https://github.com/user-attachments/assets/d67d80d9-d65f-4322-9706-4d7d60e5a6af)
i tried to adjust the extrude and realised that i didn't close the sketch (the sketch is still a line so i can't extrude it)
![image](https://github.com/user-attachments/assets/e5223e29-9151-40ad-b1da-ae90e5e06baa)
i had to add lines on the bottom.
![image](https://github.com/user-attachments/assets/eba67e0b-8eeb-40e3-a7fd-c8095553cfe1)
i used a loft to adjust this corner, but i still don't like it, so i decided to adjust the sketch. 
![image](https://github.com/user-attachments/assets/e7e94ee3-cef2-4856-b23a-a384fbb0bf76)
ok, cann't believe i forgot it again. 
![image](https://github.com/user-attachments/assets/4c475df0-01e1-419c-afef-61c153c0536f)
this is "kinda" scuffed
![image](https://github.com/user-attachments/assets/5055ddfc-37fb-4ec4-b8d4-7da85c059099)
ok so it worked, it might've been scuffed but it worked.
![image](https://github.com/user-attachments/assets/580456a6-242e-44e0-9204-e6fd09b245dd)
i spoke too soon. i don't know how to fix the sketch without the extrude being funky in some way. i pondered this for like 7 minutes straight, not knowing what to do. 
![image](https://github.com/user-attachments/assets/c7151183-483d-4bba-b50c-8a0b553cca6f)
i realised that i could adjust the sweep path, so that it becomes perpendicular/flat, so i don't have to do some crazy things to make it look normal. 
![image](https://github.com/user-attachments/assets/1520e2ef-2162-49bb-8d89-e8f027f67c25)
why is this happening. 
![image](https://github.com/user-attachments/assets/e8883d4b-7317-416c-8f0d-ae28f836d91c)
btw, i can extend it to any size i want to, i just can't change the dimension itself. 
i just constrained it using constraints. 
![image](https://github.com/user-attachments/assets/bd5a72b5-e300-44e0-bbcb-9c66aff88681)
and it worked, although... i probably have to hide the window in some way. 

# session 23:
![image](https://github.com/user-attachments/assets/ca0fa01c-7808-4107-a865-8c6663695a4c)
i decided to work on the thingy on the left (might be radar or something idk)
![image](https://github.com/user-attachments/assets/66f21b7f-2eda-43cb-9ea9-a32b25493d72)
i didn't really know how to make the semicircle on the top, then i remembered that the plane offset tool thingy exists. 
![image](https://github.com/user-attachments/assets/82452dad-c727-413e-89b0-57f8c53ffcdd)
also this somehow broke. idk what's wrong with it.
![image](https://github.com/user-attachments/assets/c8475e07-147e-4693-a3b6-804af606b67e)
not much i can do about that. 
![image](https://github.com/user-attachments/assets/4aebe075-8327-49cc-b71b-462f9730061b)
i tried to constrain the center of the circle to the center of the cylinder, but nothing popped up, so i used the same thing that i had done before, by using dimension and then constraining. i then added a line that i could use to revolve around.
![image](https://github.com/user-attachments/assets/05502ede-1979-4bb3-b2a9-d8ee52c35d12)
i cheecked the reference image to make sure that i was getting things right. i probably needed to lower the plane and maybe make the cylinder shorter.
![image](https://github.com/user-attachments/assets/4f5b146b-5abe-42c1-bcb9-f0bbdcd3915c)
this seems better.
![image](https://github.com/user-attachments/assets/0077d041-9014-4313-b31f-7fc06fdea79b)
the one to the left just looks like a sphere.
![image](https://github.com/user-attachments/assets/5daca8b7-92e9-472e-b48f-8b92007ef4f2)
cool.
i can also see from that image, that the loft thingy is on both sides. i also realised that i hadn't found out of the loft jutted out of the back of hte island a bit. 

![image](https://github.com/user-attachments/assets/ce79b06f-727c-4219-91fd-776edb001dd1)
i managed to find this image, which showed me that it didn't.

![image](https://github.com/user-attachments/assets/afa8dd98-dc46-47f8-81b8-1ef0ad78eba3)
i now wanted to do this thing. 

![image](https://github.com/user-attachments/assets/589fa5f5-5a4e-4257-9da1-224e19979bc9)
i mean it kinda works. 

![image](https://github.com/user-attachments/assets/31fc772c-825d-46d1-afd7-2ce94b04d3a7)
i adjusted the sketch and now it looks  better.

# session 24:
i decided to compress 3 of my hours (equal to 30 minutes of somebody else's hours) into 1 session, so that it doesn't overflow into 25 hours. i also may not include every single thing that i do, since i really want to lock in right now. 
![image](https://github.com/user-attachments/assets/9e697389-32d4-4fb8-8857-b6c0c7d418cf)
i made these things on the 4th layer first. 
![image](https://github.com/user-attachments/assets/343c4bee-8071-4d30-853d-154285423523)
i tried making the lofts at the end of the island. 
![image](https://github.com/user-attachments/assets/9695a766-e93a-485e-9703-7a61b7d8f445)
i don't really like this bit, so i had to change some things with the sketch. 
![image](https://github.com/user-attachments/assets/2d526c97-01d0-4d2e-8c40-7f264a75eb67)
i also decided that i wanted to constrain the loft areas
![image](https://github.com/user-attachments/assets/7fc3e78a-d8fc-4643-ae2c-f65b24c10c1a)
it isn't really seamless now, but i want it to be symmetrical on both sides. 
![image](https://github.com/user-attachments/assets/c248dd68-1264-48fb-aef3-15818c25c3be)
i need the 2 lines marked in red to  be parallel, but i'm not sure how i can do it. 
![image](https://github.com/user-attachments/assets/2d182f82-cccf-441a-9c4a-2471804b28e0)
i tried to use the parallel constraint but it looks off. then i realised, that the second line doesn't matter, it's just the first one (the outer one) that does. 
![image](https://github.com/user-attachments/assets/1c049b63-aacb-440f-bd0c-920293fa36b5)
i thought that i could simply just extrude and then all of my problems would vanish, but i didn't realise that the loft won't be fixed. 
![image](https://github.com/user-attachments/assets/d2477755-9f05-4908-9a99-89434cfab208)
i didn't really know  how to fix this, but then i realised that i could sketch and then just extrude. then i realised that it wasn't that simple. i double checked  my reference images so i can see what it's meant to look like. 
![image](https://github.com/user-attachments/assets/e9b23d02-a1f1-47bf-b3c6-0c889d5dbee6)
well ok, looks like that even the height of the loft is wrong. 
![image](https://github.com/user-attachments/assets/b0cb2984-c3ad-4c74-8dd4-d2fdc40b3b0f)
i couldn't find what extrude was associated with it, it had 3 lines above extrude 50, but extrude 50 has  like nothing related to it. 
![image](https://github.com/user-attachments/assets/47fe2158-5115-4872-9857-685e4653e0ad)
so i had to randomly click stuff in the feature tree/history thingy to find when it was made.
![image](https://github.com/user-attachments/assets/4dbbe57d-5151-4383-8c98-938b7fcdec61)
the part in red needs to be flattened out somehow.
![image](https://github.com/user-attachments/assets/c891d75e-5d01-4eee-a3f3-20b5f8a07ed2)
this is what it's meant to look like.

so it turns out that i'm really dumb. 
![image](https://github.com/user-attachments/assets/f0e2b0b1-d816-440b-a15c-3a539648adfa)
i thought that the area highlighted in red is where the loft had to be flattened to. 
![image](https://github.com/user-attachments/assets/9a7f6213-584b-45bf-aef8-3cabdf35bfab)
this is the part which is meant to be flat, it's flush with the edge. i can't believe i'm this oblivious. 
![image](https://github.com/user-attachments/assets/4934ffb9-0918-42b7-a451-e0f3269126cc)
oh and some problems appeared.
![image](https://github.com/user-attachments/assets/61577d86-d638-41fa-9f55-e29a456fbe2a)
ok so i have no clue how to fix this, if i try to delete the referenced things, some things just disappear. i don't even know what i referenced. so i just drew up an entirely new rectangle. 
![image](https://github.com/user-attachments/assets/013a1eb4-988a-4897-a38d-fa3145d75e70)
ahhh right, so things still aren't that simple. 
![image](https://github.com/user-attachments/assets/26432595-1697-4faa-be40-283ff8f40360)
i tried selecting the face to use loft, then realising that it isn't an enclosed shape.
![image](https://github.com/user-attachments/assets/ff10656a-5559-4f17-9581-c045ae523b65)
yippee. (i realised that it's meant to be flat, why did i think of doing a loft ??? (my sanity is slowly dwindling.))
i looked at the shape of the loft and realised something. 
![image](https://github.com/user-attachments/assets/421aada3-cb42-4c3e-93e2-b2336ef0d2e0)
![image](https://github.com/user-attachments/assets/b319f07f-718b-4eac-aa21-dc21793da266)
kajsdf;lksafjsa; dj;j a;ja;fdsjk fda kfdaj; dsa;lkj;lkjdsafjupaqtvnyeurinesrmai9 rueiuoemwiagzdum
i also had to make the thingy flat. 
![image](https://github.com/user-attachments/assets/244ce2b6-8154-451a-85ad-f6750fa00771)
yeah things are going great. really great. 
![image](https://github.com/user-attachments/assets/1d76acaf-3861-404f-b72e-389a92287130)
i then realised that i  needed to extend the blue line somehow. 
![image](https://github.com/user-attachments/assets/bb8a8605-79b8-4642-8fa7-228c3dc28dc3)
hafhioqwjaosdnzvjz so it works now. i also then quickly realised, that if i extended the blue line to the edge, then everything would be fine. i love cad. 
![image](https://github.com/user-attachments/assets/f7ebefd8-0e77-43fa-a55f-32c11c1433b7)
ok maybe i wasn't entirely correct. 
![image](https://github.com/user-attachments/assets/65877b58-af08-4453-ba18-1fd14e345175)
i extended this line to see if it could fix it. didn't work.   
![image](https://github.com/user-attachments/assets/db45e4e3-b1c5-473e-be70-b381787c4bd4)
mmmm yes quite fun.
![image](https://github.com/user-attachments/assets/7c1880fd-bf47-471c-b143-cba55d765713)
i reverted some changes and tried to use loft to put them together. it said something about the loft intersecting itself. 
i didn't want to deal with it right now, so i decided to work on filling the middle in.
![image](https://github.com/user-attachments/assets/9eacbef8-9d09-4c36-b8e0-41a62bae9058)
it only took one loft, why can't things be this simple. 
![image](https://github.com/user-attachments/assets/bde94020-f492-4992-9115-f6832b33d8b9)
quite scuffed, but i don't really care about it anymore, making an aircraft carrier is burning me out and i feel like i don't wanna cad anymore.
![image](https://github.com/user-attachments/assets/90541401-1bac-4bf7-918e-1a5f1990e936)
i then decided to sketch a triangle and then use loft again.
![image](https://github.com/user-attachments/assets/9fc2c2aa-455d-4034-a4a1-afe857b363c5)
well it worked. i know that all the proportions are messed up now, but it's not like anybody's going to 3d print this.
the back also needed to be fixed, so i sketched some lines and hten used loft.
![image](https://github.com/user-attachments/assets/4a5670b8-6ff3-4d65-9d6d-e3424fe3c003)
welll that's not where i want it to go.
![image](https://github.com/user-attachments/assets/0b269fdf-4f00-4f78-870d-c2acba36088a)
everything looks fine and kinda fixed now. 

# session 25: (part one out of ???)
i had to cram many more hours into this session, because this is the last one before it becomes 25 hours, which i don't want.
![image](https://github.com/user-attachments/assets/80b71cce-1013-4ee5-afcf-5c7b95cbe9b1)
i couldn't really get a loft to work here, so i just randomly clicked edges and prayed it'd work
![image](https://github.com/user-attachments/assets/40d5ae58-7431-48a8-828a-66075ad248b4)
WOW OK. (ignore hte self intersection and bad geometry, it's leftovers from previous random clicks)
![image](https://github.com/user-attachments/assets/b67c484f-7ed0-4ed5-b3a0-060feb7d5ff4)
i needed to fix this somehow. the lofts weren't really working.
![image](https://github.com/user-attachments/assets/7b8f715d-5343-436f-b469-b62b0cb6faa0)
also this broke.
![image](https://github.com/user-attachments/assets/b9119d55-5ca6-4541-abf8-1b969703cdcd)
i was so focused on trying to use loft to fix the problem, that i neglected extrude.
![image](https://github.com/user-attachments/assets/5fd3e52e-087b-4110-925d-7636f88f807d)
there was a line here, but it was something that i can't fix/not bothered to fix since it won't show up when you 3d print.
![image](https://github.com/user-attachments/assets/c4edfa5f-9e90-4169-aa59-278bdcec5843)
ok so i forgot that it was meant to be flat. so i had to delete the loft and sketch an area.
![image](https://github.com/user-attachments/assets/966d6865-02a0-4bfe-8696-2d3cac4818fc)
surely nothing goes badly (i can see some weird things behind the cut.)
![image](https://github.com/user-attachments/assets/d4b1fea6-4d70-4897-b84a-fe78c86c5878)
there is a tiny line. 
![image](https://github.com/user-attachments/assets/f63700c3-3fca-498f-a003-651c50bee50a)
yeah that's kinda scuffed. i would highly prefer that it's symmetrical. 
![image](https://github.com/user-attachments/assets/3a362fde-fa42-481d-a184-d97d85aaf23a)
i decided to extend some of the lines.
![image](https://github.com/user-attachments/assets/64d74d05-c938-4644-8683-8c347bbced15)
i also had to extend this square. i remember that at some point, i had reduced the size of the square, and now i have to extend it again. fun.
![image](https://github.com/user-attachments/assets/c39f858e-d7cd-4ec9-b391-0a519b48a658)
it fixes up the sides, but doesn't fix some other things. i prob need to do some sketches and stuff to get rid of it.
![image](https://github.com/user-attachments/assets/66c3e870-91cc-41ae-8e9e-d604fef146ae)
it was just that simple. all i had to do was that. 
![image](https://github.com/user-attachments/assets/bee65e02-4018-4e48-b3f8-1dc246e1015e)
there's a random line and some things aren't parallel, but it's good enough to look at.
![image](https://github.com/user-attachments/assets/7337c0f3-3173-44ab-8fc4-a2e5410fba50)
ever so slightly off.
![image](https://github.com/user-attachments/assets/7b3977f3-7573-4249-b920-1f858e57d82f)
this solution is going to be so scuffed...
![image](https://github.com/user-attachments/assets/48694e90-d06b-44f8-8cb1-120de9bbc54d)
i love overcomplicating things.
