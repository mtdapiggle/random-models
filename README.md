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
