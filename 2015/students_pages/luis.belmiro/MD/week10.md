###A quick design

In this week i decided make a board than could be a experiment, and useful to the final project.

 As you can see in my final project proposal i want to make a device than can know the height of the garbage in the trash can's. 

For than i will use IR led's and IR phototransistor's.

Why? Because they are cheaper easy to encapsulate. 

At first i think in design using an attiy44, but if it was an experiment, it well be in all sense.  So i chose attiny45. 

first i go to the internet try to find an eagle example already made. 

Why?! because i master eagle so i think i can skip some stages. 

So i find it [here](http://www.thingiverse.com/thing:188391).

Thank's Anton Sky. :)

I change the ambient light sensor in order to full fill my intent's

because i want to measure distances how much further as possible i will try to use differential gain amplitude in ADC module, as you can read in ADC section of attiny datasheet. 

In fact in attiny45 we have 4 single input adc or one 1 diferential adc. 

I will only need one adc so i chose that. 

And because i have adc3 as already an adc input, i keep it. and adc2 will be ground...
Howw wait a minute...

**ERROR**

I make an error in the design i know it now. 

ADC0 or ADC2 can be used as deferential positive pin. And all ADC pin's can be the negative one's. 

So i must change adc3 to adc2 and vice-versa.

Ok let's begin. That's my first experiment. 

The second experiment is this.  I will need an output to the led. But what i pin i should use? My left over pin's was MISO and MOSI in programmer header. so i chose to use booth and the experiment if with 2 led's in that pin's i can program the board. 

![eagle sch]

[eagle sch]:  https://lh4.googleusercontent.com/-yGfJ3t8PJTA/VS2IbmgGYFI/AAAAAAAAmyY/uzMv03-MK1A/w1118-h571-no/Screen%2BShot%2B2015-04-14%2Bat%2B22.35.41.png "eagle sch" width=620px 

![eagle brd]

[eagle brd]:  https://lh3.googleusercontent.com/-B1Pi_oryNWM/VS2Ib6KGGeI/AAAAAAAAmyc/GK1BthIRKZU/w956-h568-no/Screen%2BShot%2B2015-04-14%2Bat%2B22.35.51.png "eagle brd" width=620px 

So i design what left in the board.

After that i export the board traces and outline to png 500dpi. 
But i make another add on, the Penela logo to the board ;)

![penela brd]

[penela brd]:  https://lh6.googleusercontent.com/-QYQVVdML4l0/VS2JsDahzKI/AAAAAAAAmy4/_lMfSWRzkp8/w853-h460-no/pads.png "board penela" width=620px 

I was ready to mill.

###Milling Time.
It's always challenging, but with fabmodule's i consider it heavenly easy. 

This time, i use fabmodules all way down. Because Luis Carvão make a server in the connect pc.

It's very easy and integrated. as you can see in the photo's. 

![pcb in fabmodules]

[pcb in fabmodules]:  https://lh3.googleusercontent.com/-hZN3_ivUi1M/VS2G2h2UrbI/AAAAAAAAmx4/13Qj1wZTEH0/w949-h568-no/Screen%2BShot%2B2015-04-14%2Bat%2B14.59.53.png "pcb mill" width=620px 

![pcb mill]

[pcb mill]:  https://lh3.googleusercontent.com/-4MfQqm-JWnw/VS2GnHgZ-pI/AAAAAAAAmxk/xhkniqVZ58U/w426-h568-no/IMG_20150414_153003.jpg "pcb mill" width=320px 


###a new way stencil.
Since my first board stencil is a blessing that i carried into the [fablab EDP](www.fablabedp.pt).  [Maria Boavida](http://fabacademy.org/archives/2015/eu/students/boavida.maria/index.html) my colleague in fabacademy love's it every time.

But we struggle in something, we can't in a easy way extract the only pad's from eagle. We need to always go to the gimp or inkscape to kill the traces. 

But can't be...

I search and we found, people use eagle to make board's and we have tcream layer that is exactly what we want, so we use it. 

In order to use it we need to chose another solid color to them, but that's it. 

::)

![eagle pads stencil tcream]

[eagle pads stencil tcream]:  https://lh5.googleusercontent.com/-FcsO8mvX5rY/VS2LMXdfAOI/AAAAAAAAmzI/SOPE1xvAZdw/w815-h568-no/Screen%2BShot%2B2015-04-14%2Bat%2B22.48.16.png "eagle pads stencil tcream" width=620px 


After that is the habitual procedure:

- vinil cutter. 
- vinil on the board
- solder paste on the vinil
- peal the vinil
- place the component's
- apply hot air 320ºC 

And voila a ready tho program board, nice cleaner wonderful.

![pcb peal]

[pcb peal]: https://lh3.googleusercontent.com/-2W_5fwD0HmA/VS2GZivdIbI/AAAAAAAAmxY/IQcCrz-fFdo/w426-h568-no/IMG_20150414_172042.jpg "pcb peal" width=320px 

![pcb with solder]

[pcb with solder]: https://lh6.googleusercontent.com/-QrYXZqR9qkg/VS2GZnBBhjI/AAAAAAAAmzQ/RrBs3t-YBhM/w757-h568-no/IMG_20150414_172100.jpg"pcb with solder" width=620px 






###Programming time

So after all this adventure it's time to test it. 

![board with no power]

[board with no power]:  https://lh6.googleusercontent.com/-_K9VcweMW0I/VS2G2Wm62KI/AAAAAAAAmx0/MxRpg5jwvu8/w732-h578-no/Screen%2BShot%2B2015-04-14%2Bat%2B22.18.10.png "board with no power" width=620px 



Up's it's look's that board have no Power.. i'm on debugging... see you

