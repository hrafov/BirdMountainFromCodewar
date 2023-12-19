# BirdMountainFromCodewar
task for 3 points

Background
A high-flying bird can estimate the contours of the ground below.

He sees hills and valleys, he sees plains and mountains.

(But you already know all this because you've solved my Bird Mountain Kata)

But this time our protagonist bird also sees a RIVER.

Not only that, but he sees that the river is rising rapidly, so much so that in a few days it threatens to inundate the surrounding land.

And all this is very important to the bird because he cannot land on water!

Kata Task
The bird quickly calculates how much ground will remain dry as the water rises.

Can you?

Output
A list of how many dry landing spots there are for the next 3 days only (include day 0)
Notes
The ground is always supplied as a rectangular grid
The normal river is at level -0.5. It is rising at 1 unit per day
Sometimes there isn't any river at all, so you better account for those cases too!
Example
The birds-eye view
  ^^^^^^       
^^^^^^^^       ^^^
^^^^^^^  ^^^
^^^^^^^  ^^^
^^^^^^^  ^^^
---------------------
^^^^^        
   ^^^^^^^^  ^^^^^^^
^^^^^^^^     ^     ^
^^^^^        ^^^^^^^
The bird-brain calculations
Day	Prediction	Number of dry landing spots
Day 0	
  111111       
11222221       111
1233321  111
1222221  121
1111111  111
---------------------
11111        
   12111111  1111111
11122111     1     1
11111        1111111
189
Day 1	
  111111-------------
11222221-------111---
1233321--111---------
1222221--121---------
1111111--111---------
---------------------
11111----------------
   12111111--1111111-
11122111-----1     1-
11111--------1111111-
99
Day 2	
---------------------
--22222--------------
-23332---------------
-22222----2----------
---------------------
---------------------
---------------------
----2----------------
---22----------------
---------------------
19
Day 3	
---------------------
---------------------
--333----------------
---------------------
---------------------
---------------------
---------------------
---------------------
---------------------
---------------------
3
Dry ground = [189, 99, 19, 3]

Series
Bird Mountain

