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
