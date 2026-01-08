---
title: Experimental Aquaponics Automation Project
date: 2026-01-07
categories: [PROJECTS, IOT]
tags: [aquaponics, iot, sensors]     
author: Kian
---

## The Idea

Humans have been trying to make food production easier for millennia. Starting with relatively simple methods, such as moving away from hunter-gatherer lifestyles towards stationary crop farming, and then to more advanced ones like the use of tools and animals. We have been on a never-ending search for higher yields and easier harvests. 

I have always been fascinated with the combination of biology and technology. There is a certain satisfaction in making the two work together symbiotically to create something even more efficient and low effort, and I know many others do too. 

This is where the practice of aquaponics comes in. For those who have never heard of it, here is a simple breakdown. It is the combination of fish keeping (typically for consumption) and growing edible crops. You feed the fish, the fish create waste, the plants consume that waste while cleaning the water, the water is returned to the fish, and the cycle continues. The purpose of it is little input or maintenance and a high yield. Below is a diagram showing the basic mechanics.

![Aquaponics Diagram](/assets/images/aquaponicsdiagram.jpg)

Of course real life is never this simple, and it can actually get quite complicated. Fish and plants require carefully balanced water chemistry, lighting, temperature, and nutrients. Getting all of this right can be tricky, especially in new systems.

I decided to create my own small-scale system to learn the basics and implement some automation and data-gathering techniques. This will be a test bed, and I can expand the complexity over time and eventually move to a more production-level system. I have already created the base system, and this blog will be more to track progress and document the automation side. 

So without further ado, here is my current setup.

## The Setup 

First of all, credit where credit is due. The main design for my setup came from this article by David Cline, with some minor tweaks to fit my needs better: https://www.aces.edu/blog/topics/aquaculture/building-a-tabletop-aquaponics-system-as-a-platform-for-stem-education/

It was exactly the kind of setup I needed for the space I had in my office and the amount I wanted to spend. Of course this is an extremely simple design and at this scale cannot grow fish for consumption (unless you like goldfish); however, it provides everything needed to build and learn some automation techniques. 

Here is my version!


![Aquaponics Diagram](/assets/images/_1010064.JPG)
![Aquaponics Diagram](/assets/images/_1010066.JPG)
*Entire setup*

![Aquaponics Diagram](/assets/images/_1010063.JPG)
*Grow bed with bell siphon*

![Aquaponics Diagram](/assets/images/_1010065.JPG)
*Mechanical filter, dirty (nutrient filled) water is brought from fish tank to the filter*

![Aquaponics Diagram](/assets/images/_1010067.JPG)
*Pump, and fish!*

![Aquaponics Diagram](/assets/images/_1010070.JPG)
*Return pipe*

The main differences between my version and the one in David's article are that I used a larger grow bed and a more powerful pump, and I have tried to make the fish tank more suitable for fish. As many people pointed out, he was keeping multiple koi fish in only a 20-gallon tank with no substrate or anything really. Koi really need a much larger tank size; even just keeping one in a 20-gallon tank could be considered cruel. For this reason I opted to go with goldfish, as they still produce a lot of waste, and I am only keeping three for now. I will be monitoring their size and moving them to a pond if they outgrow this tank. 

As you can see, there are already plants growing. Currently I have basil, lettuce, spinach, and one rosemary plant. The larger basil plants were already established and then transplanted (hence their size in comparison), but they have already grown quite significantly. The other seedlings were planted in rockwool and have also been coming up nicely. I will be monitoring their growth closely to see if there are any deficiencies. 

The growing medium is lava rock; it has lots of surface area for bacteria to grow, it's cheap, and it allows for good water flow. 

Of course, since this is indoors, and it's not advisable to have direct sunlight on a fish tank, I am using an LED grow light for my lighting needs. 

## Future of this project

Now that I have the basics up and running, and there have been no issues with the purely mechanical base setup, I will be implementing some cool technological aspects to this. This is not needed whatsoever and is really only to learn more about collecting sensor data to gain insights, automating some of the components, and building an internal application to monitor everything. 

If this sounds interesting, stick around for the next post, where I will share some of my plans!
