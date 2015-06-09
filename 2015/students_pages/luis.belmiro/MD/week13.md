###Networking
In this week i decide to complete what's missing in my final project, the wireless conection. 
I chouse for this the nRF24L01+ from Nordic to make que simple conection. 

![rf_module]

[rf_module]: https://lh3.googleusercontent.com/-ZxH0aJeSEjo/VUnUQKRmbOI/AAAAAAAAnks/qjYfXrLE9ME/w636-h581-no/nrf.jpg width=620px

RF it's always tricky, but with this chip i expect no problem's.
It's a simple RF module, but have all the power including to stream music. 
But it's a simple module because have, no more layers like wifi, or bluetooth.
Because i want to deliver information from trash can into trash can i suspect this is the right solution.
I need to confirm if 

###FabKit Penela
This week i decided re-make the fabkit. I inspired on [satshakit](http://fabacademy.org/archives/2015/doc/projects/fabkit-0.4.html)

I add to it. ftdi port. 
and the ISP port.

![board_plus_ftdi]

[board_plus_ftdi]: https://lh4.googleusercontent.com/-BAk0HOtzQaA/VUnno2oN0oI/AAAAAAAAnlY/UOnn9iseDqc/w775-h612-no/Screen%2BShot%2B2015-05-06%2Bat%2B11.05.21.png width=620px

Than i make it. 

![board_made]

[board_made]: https://lh5.googleusercontent.com/-k9ttBN8J0Uo/VUnSaW87OYI/AAAAAAAAni4/O_3pP3TtqjI/w459-h612-no/IMG_20150504_140620.jpg width=620px

I have this erros's.

![board_error]

[board_error]: https://lh4.googleusercontent.com/-H_upvb7LePU/VUnSaaDZfzI/AAAAAAAAnmY/sFZZqnfsVus/w816-h612-no/IMG_20150505_142127.jpg width=620px

I resolve them using a higher resoltuion image. 1000dpi

###Vinil cutting. 
On this i make some mistakes, but i think i find the solution. 

- Measure the outline of the board in eagle board
- export pads and outline(dimension) as color png. 
- In Roland Cutstudio import it
- Make outline.
- remove the image
- convert lines to polylines
- remove the outer lines and leave the pads and the true outline of the board. 
- resize to the measure did in eagle.
- Vinil cutter force 150gf.

###soldering is easy
After populate the board i solder it with hot air.
![board_populated]

[board_populated]:  https://lh4.googleusercontent.com/-32yK2yXFLRE/VUnpJrIN6GI/AAAAAAAAnmw/BymjX20bWpo/w816-h612-no/IMG_20150505_174638.jpg width=620px

Another mistake, i not chose the right crystal foot print. 

###programing the board

###123 radio test
I decided use arduino and a library. 
Because it's a non fail solution. 
After than i will gone make my c library. 

So i have gone to the arduino playground find the nRF24l01.
I find this simple library as a second choice.

The test was a success :)
[ ![video_working](https://lh3.googleusercontent.com/-th4d841oXyU/VUnvdw0NtGI/AAAAAAAAnnk/nCt4HchUFog/w426-h757/VID_20150506_112912.mp4)](https://plus.google.com/u/0/photos/116858267463697494571/albums/6145674513987069889/6145709429673913298?pid=6145709429673913298&oid=116858267463697494571)


