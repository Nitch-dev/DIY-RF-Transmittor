# DIY-RF-Transmittor
a simple RF transmitter capable of broadcasting audio signals. The transmitter utilizes an XR-2206 IC to modulate an audio signal onto a carrier wave. The modulated signal is then transmitted through a simple antenna. The receiver can be any AM radio capable of picking up the transmitted frequency. which right now is my old Car.

# Day 1: Diving into the RF World

Today, I took my first steps into the exciting world of RF electronics. I stumbled upon the XR-2206 IC, a versatile chip that can be used to build a simple AM transmitter. My basic idea was first to get a Modulator IC and use something else like  555 timer for the Carrier Wave but then XR-2206 Came into the picture and made it way more easier than I thought, It has both Moduclation and Carrier wave generation just Hookup Pin 1 to audio Signal and your Done (adjust the Knobs for desired Carrier Wave Of course) 

--> **Why not the 555 Timer you may ask**

Well the Reason is that one its not efficient and sounds terrible in addition to that it dosnt modulate the signal and carrier wave but only carrier wave and, its square wave output isn't ideal for radio frequency applications.

*Here is the DataSheet for the XR-2206:*

https://www.sparkfun.com/datasheets/Kits/XR2206_104_020808.pdf

# Day 2: Soldering and Setbacks (and a Tiny Bit of Ranting)

Alright, so I finally got around the XR2206 kit. Man, let me tell you, soldering is not as easy as it looks in those YouTube tutorials. I think I burned myself at least three times. But hey, I got it done!

The real bummer came when I tried to test it out. I did everything I could, cranked up the music, and...crickets. My car radio just wasn't picking up anything. Turns out, car radios aren't exactly the most sensitive receivers for this kind of thing and also I didnt wanna use up a big wire for anteena.

So, I had to order a proper radio receiver. Now I'm waiting for it to arrive, which is killing me! I'm itching to see if this thing actually works. Hopefully, it's not just a pile of expensive electronic junk sitting on my desk.

I'll keep you updated on the next installment. Wish me luck!

P.S. Maybe I should have started with something simpler than an RF transmitter for my first RF electronics project.

*to be continued...*
