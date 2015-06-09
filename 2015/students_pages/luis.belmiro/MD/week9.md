Early in my career i work for the mould industry, but i never try or think in be a mould maker. 

But here i am. 

In the beginning i try to think something to my final project, but because the case of the Trashcan Tracker will be changed in the next few week's i think in something different.

Mould for chocolate's for my fablab inauguration :)

This solution is good for a beginner because is simpler and allow's a more step by step approach to this new concept.

So i begin for redesign the mould around the Fablab Penela Logo.

![Penela fablab logo]

[Penela fablab logo]:  ./images/fablab_logo.png "Fablab Penela Logo" width=320px 

The modelling software i chose is again Rhino because i want to master it. 

As always i began the 3D design from the 2D curve's, Rhino is made for do this so i follow the line of Rhino.

So as many technic's that Luis Carvão teach me i highlight this:

- Extrudecrv - in order to make a 3D shape. 
- Boolean diference - to extract the mould and contra mould.
- Bounding box, to make a box around my 3D shape
- Showedges - Make an edges analysis. It is useful for look for naked edge's
![Edge Analysis]

[Edge Analysis]:  https://lh4.googleusercontent.com/-MjINNs7MwJ4/VSQIbtm00BI/AAAAAAAAl6c/9M2mTFON2dQ/w283-h209-no/Screen%2BShot%2B2015-03-31%2Bat%2B19.35.12.png "show edges command" width=320px 

So after i play with this i finally have my mould, after that i can cast my silicone, and from silicone i can cast my cookie. 
as you can see.

![Mold and cast in Rhino]

[Mold and cast in Rhino]:  https://lh5.googleusercontent.com/-kHqjutm9l9E/VSQIcBDcOJI/AAAAAAAAl6I/wPS6kq3QkPQ/w848-h612-no/Screen%2BShot%2B2015-04-01%2Bat%2B16.27.03.png "Mold and cast in Rhino" with=620px

<script src="https://embed.github.com/view/3d/miroluis/FabMiroOnGit/master/mold%20and%20cast%20in%20rhino.stl"></script>

##Milling time

After i design that it's to milling machine it :)

I pick up the STL from the first block, the *madre* or in my design the *"cera"*

I use it in modela, Vplayer.  On it i import the STL file, and prepare 6 process with several milling cutter's

![6 process]

[6 process]:  https://lh4.googleusercontent.com/7hSx1YOGm3crlPgaZOoHggUbGj4vd5Lb35b6zFvFKV25=w817-h557 "6 milling process's" with=620px

So the first process will be the Roughing1 where we gone remove the biggest part of the material.

I use 2mm square milling cutter.

the cutting parameter's are the follow

![cutting parameters roughing_1]

[cutting parameters roughing_1]: https://lh6.googleusercontent.com/-TkLNTRFYYRU/VST8kvK7X5I/AAAAAAAAl8U/GgecL0F8lYg/w632-h339-no/Screen%2BShot%2B2015-04-08%2Bat%2B11.01.14.png "cutting parameters roughing 1" with=620px

Because our bigger and smaller tool are very different in size 2mm versus 0,1mm. I decide to rough again with 1mm tool. 

![cutting parameters roughing_1](https://lh4.googleusercontent.com/-T1sRmHkoBgs/VST_Sh2STlI/AAAAAAAAl9A/BYHxXSA7tF8/w619-h352-no/Screen%2BShot%2B2015-04-08%2Bat%2B11.10.39.png)

So after this we can make a first finishing, with the same tool.

![cutting parameters finishing 1](https://lh4.googleusercontent.com/-dN2hWnLMnP8/VST-62VdDlI/AAAAAAAAl8s/9e4H49MBd7w/w964-h474-no/Screen%2BShot%2B2015-04-08%2Bat%2B11.11.25.png)

After this i found a flow in my design, *Penela* letter's have 2mm height, and my finest tool have the same height, so i need to create a surfacing to cut out 0,5mm so i can safely use the tool. 

![surfacing](https://lh3.googleusercontent.com/-faimTB5elBY/VSUCr77O3WI/AAAAAAAAl9Q/SiqVx191LJc/w621-h343-no/Screen%2BShot%2B2015-04-08%2Bat%2B11.27.30.png)

And now here we go to use the finest tool ever :)

![roughing_3](https://lh4.googleusercontent.com/-07JkAJKkR3k/VSUETF3znsI/AAAAAAAAl94/kzVdzBOLuv8/w637-h345-no/Screen%2BShot%2B2015-04-08%2Bat%2B11.30.19.png)

Here i first another mistake, i have chose cutting amount of 0.1mm and that amount is the exact size of the tool so it is to much to the tool and a broke one :(

But after i put another i could finish the work. 

Another thing i find is, machining time varies a lot with the milling strategies. so for this i chose the contour strategy and the time drop 3 time. Uau 3 times faster incredible. 

In modela Vplayer we could estimate the milling time with virtual modela, it helps to control fabrication time.

![contour lines](https://lh6.googleusercontent.com/-LRUoh1vaTHg/VSUETr4xxZI/AAAAAAAAl-E/0LrVxZrKsFY/w751-h483-no/Screen%2BShot%2B2015-04-08%2Bat%2B11.34.37.png)

Final piece :)
![final piece](https://lh4.googleusercontent.com/-gD02SLwaO8c/VRxqBZW0TfI/AAAAAAAAl-U/dss8ufQGGZc/w816-h612-no/IMG_20150401_161827.jpg)

##Silicone time

So after milling my challenging machinable wax, is time to make the mould in silicone. 
So first i need to chose the silicone. A food safe one :)

Datasheet of the material
http://www.interfareba.com/images/stories/demo/siliconas/ELASTOSIL_M_4601-en-03.pdf

And it's a great one because offers a moulding manual. Great!
Manual molde making
http://www.wacker.com/cms/media/publications/downloads/6007_EN.pdf

So i will need to know how much silicone i gonna need and how much catalyst i will need. 

So in for begin i need to make another great command in Rhino. *volume*.

With this, i peak up the volume of my silicone mould.

After that i made [this google sheet](https://docs.google.com/spreadsheets/d/1BroghYjqKVYl8Oh5KDIjILEPzLACnsd8NXssqc4hY-w/edit?usp=sharing) in for calculation of the correspondent weight of the silicone and catalyst. 
 
 So after this it was very easy. i follow this steps:
 
 - Tare the scale
 - weight the compound A
 - tare the scale
 - weight the compound B
 
 After that stir stir stir...
 
 After stiring, and not scooping ;) i drop the mix into the mould. The mould should be a little bit tilted to not create to much air bubbles.

After this we need the remove the air bubbles left in the mix. So we use the laser machine air compressor in reverse mode to vacuum the remain air. 

Luis Carvão and Ferdi have made a kitchen plank and a pirex cup to make the vacuum chamber. :)

After 10 minutes the air bubbles are totally removed

We leave the mix to rest 90min. After that i could take the silicone mould from the wax mould. 
But i will need to wait more 12h in order to use it with chocolate. 
as you can see in the silicone datasheet.


##CHOCOLATE time :)

And finally i can test the mould with the chocolate. Uau time. 
At first test i melted the chocolate, from easter eggs of my child's ;), in the microwave.
The i dumped it in the silicone mould. 
I wait an hour i refrigerator. I want that chocolate will be stiff.

![final chocolate](https://lh6.googleusercontent.com/-mP_HH2Iba-U/VR8LJKZL2UI/AAAAAAAAl-4/pMbix5um92Q/w816-h612-no/IMG_20150403_221853.jpg)

##Lesson's learned.

What i design in 3D in rhino it will become real, and that will affect, material height, configuration of the 3d shape, etc.

When i machine the piece, i must be very aware of the tool height, and the expected tool path.

Silicone is easy, but i need to follow the datasheet.

Chocolate is tricky, and need's space to flow.
If i do it again i will leave some holes in the bottom of the letter's in the mould to the air escape.

Relief figures is always easy to mould in chocolate inside. I have chose relief for outside but i pay the price, it was more difficult to unmould.

