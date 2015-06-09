###Interface and Application Programming
Eeny, meeny, miny, moe.
What language should i know.

Well this week is a nice one. 
I want to choose one language that could be meaningful in the future, easy and powerful. 
So my choice is between python that I already know. 
Or Nodejs that i have made my incursions but it's not my domination.

So the winner is....
NODEJS of course. 
why because with the websockets or the socket.io have an appetite application, control hardware via webrowser, how awesome is that? 

So I begin this week re-making the input week. 
I do it again making the board just an IR light measure board.

So first o use the [hello magnet test for attiny 45 hello.mag.45](http://academy.cba.mit.edu/classes/input_devices/index.html) of the Neil.
So first I began to figure out why nodejs not work as good as python, as you can see in my input devices week.
The reason is that serial communication comes in burst, and I must take the data out of the array.

### Going deep no Node
I document and try to explain all the hello.mag.45.js
I fact I rename it to be more like this week.

That said, let's understand Nodejs. 
Node is awesome because with on call we have a server. Could be a webserver, socket server, etc.
Another magic of node is that an event language, means that only act's on base of event's on it. 
And this is the magic of we could se a look like on real time data on browser.
See data on browser is awesome, but we can interact as easily send command's to the hardware is beautiful to. 

Node is easy to install

after that we can use npm a package manager for node. 

for this i install to packages
*npm install ws*
*npm install serialport*

After here you must inside my files [.js](https://www.dropbox.com/s/e3tzkkrr8tckk6y/serial_in_out_socket.js?dl=0) and [.html](https://www.dropbox.com/s/2kerhoghz35exic/serial_in_out_socket.html?dl=0) in order to understand what's going on. 
I must say many many thank's to [Rui Pedro](https://www.linkedin.com/pub/rui-pedro-fernandes/79/745/ab7?trk=pub-pbmap) form [Crossing Answers](http://crossinganswers.com/) a big master in nodejs. Crossing Answers have plenty of beautiful project's on this and 3D stuff, like virtual reality, mobile apps, etc.

###Interface in action. 
Here you can see the choosing the port, make the connection, and data visualization on browser, for this I use the input week board.


Here you can see the interface turning an Fabkit led on and off. I do it in this board because the theme for this week is interfacing and it's more easy to put fabkit to work.
 