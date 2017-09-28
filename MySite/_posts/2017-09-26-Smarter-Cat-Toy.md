---
layout: post
title: "CM Final Project: Smarter Cat Toy"
img: ophelia.jpg # Add image post (optional)
date: 2017-09-27 12:55:00 +0300
description: Final project idea for Critical Making Studio. Will update as project progresses. # Add post description (optional)
tag: [pets, toys, animals]
---



## Final CM Project: A Smarter Cat Toy

### [***Concept***](https://vimeo.com/232763877/2fef149491)


A responsive cat toy that satisfies the house cat's natural need to hunt and
behaves as a prey animal while simultaneously enhancing the relationship between
cat and owner.

### *What does this require?*

- #### *Mobility*

- #### *Sensing*

- #### *Intelligence*

- #### *Realism*

- #### *Interaction*

---

## **Mobility**

The average mouse can run 8 mph(link to stat) and is incredibly agile. The toy
will need to be able to mimic that kind of mobility.

This presents a challenge in how to robotically simulate this movement in a
small, mouse sized container.

***My Initial Thoughts***

My initial thoughts were mouse shaped. (image of my initial design around a mouse)
In trying to keep with that shape I considered a mobility method similar to the
[Hexbug Cat Toy](https://www.hexbug.com/pettoy/hexbug-mouse-robotic-cat-toy-grey.html).

I got one and tore it apart...

![Imgur](https://i.imgur.com/0Ye6qHv.jpg?2)


I got another for my cat.

![Imgur](https://i.imgur.com/pCRKTY1.jpg?1)


To move around, it is just a motor...

![Imgur](https://i.imgur.com/PudGHeO.jpg?2)


That vibrates the little rubber feet of the mouse.

![Imgur](https://i.imgur.com/Cn1EdE4.jpg?1)
![Imgur](https://i.imgur.com/Dd14WdW.jpg?1)

This method is great because it mimics the motion of a mouse as it runs.
But has significant limitations in regards to speed and agility. After a time,
she got bored.

![Imgur](https://i.imgur.com/coBU3hR.jpg?1)

It needed to be faster and quicker...

<br>

***Moving Past Mouse Shaped***

In discussing the issue of mobility with a classmate, he showed me the [Sphero](http://www.sphero.com) toy.

![Sphero](https://cdn.shopify.com/s/files/1/0170/5178/products/SPRK_Plus_Package_Color_Correct_large.png?v=1474556855)

This amazing thing was [durable, fast, and agile](https://www.youtube.com/watch?v=1S5lUDvlu3A).

Maybe the toy doesn't have to be mouse shaped.
*Maybe it could be a sphere.*

<br>
From what I can tell from the image, it appears to basically be a small Segway.

![Spero Cross Section](http://howitworks.wpengine.com/wp-content/uploads/2013/11/Inside-Sphero.jpg)

If it could be miniaturized...

**Next Steps**
1. Aquire a Sphero
2. Contact Sphero *(They are in Boulder!)*
 2. See if they are interested in working with
3. Tear Sphero apart, see if it can be made smaller

---

 ## **Sensing**
 Prey knows when it is being attacked and killed. So the toy will need to as well.


 ***My Initial Thoughts***

 Research into how to do this is...in it's early stages. But I imagine that pressure
 sensors on the inside of the sphere like this pad...
![Pressure Pad](https://cdn.sparkfun.com//assets/parts/6/7/8/1/11207-01.jpg)

or this cloth...

![Pressure Sensing Cloth](https://cdn.sparkfun.com//assets/parts/1/1/9/9/4/14111-01.jpg)


coupled with an accelerometer...

![Accelerometer](https://cdn.sparkfun.com//assets/parts/1/2/1/9/5/MMA8452_Qwiic_Breakout_03.jpg)
could be used toinform the toy when it is in peril.

<br>

**Next Steps**
1. Aquire and experiment with different sensors.

---

 ## **Intelligence**
Prey is crafty in how it evades and escapes. The toy needs to mimic that behavior.

Using a small controller like an [Arduino](https://www.arduino.cc)...

![Arduino Nano](https://store-cdn.arduino.cc/usa/catalog/product/cache/1/image/1040x660/604a3538c15e081937dbfbd20aa60aad/A/0/A000005_featured_2.jpg)

Or a [Raspberry Pi](https://www.raspberrypi.org)...

![Raspberry Pi Zero W](https://www.raspberrypi.org/app/uploads/2017/05/Pi-Zero-W-Tilt-462x322.jpg)

logic can be programmed in to give the toy the necessary behavior.

<br>
***Next Steps***
1. Aquire Arduino and/or Raspberry Pi
2. Learn how to use them
3. Boil down key if-then behaviors

---

## **Realism**
To provide the cat as authentic experience as possible the toy needs to be made
from material that can best simulate a real mouse.

The core of the toy can be a platform that any 'skin' can be applied to. Similar to
the different skins that can be applied to a Sphero.

![Sphero Skin](https://cdn.shopify.com/s/files/1/0170/5178/products/Nubbies_grande_de7deb0b-6b91-43fd-884b-32ae03317f3e_large.jpg?v=1488829345)


The skin for this toy would need to be something tough like leather with a fur housed over it.
It could even have a tail.

<br>
 ***Next Steps***
 1. Design the skin
 2. Determine the material used to make the skin

 ---

 ## **Interaction**
 Part of the purpose of the toy is to enhance the relationship between owner and pet.
 Through a remote control of the toy cat and owner can engage in a unique and fun
 way for both.

Arduino and Raspberry Pi both offer wifi and bluetooth connectivity and through an
app owner can take control.

<br>
***Next Steps***
1. Brainstorm App design
2. Work with Sphero to see how they connect and control

---

## **Project Status**
Still in it's very early stages. My best chance at a prototype is to work backwards
from a Sphero Spark. Try to add behavior and a skin to it, modeling how the toy could
work. Still lots to learn.
