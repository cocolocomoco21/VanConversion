# 2. Component selection
(continuing from 1. Capabilities)

### Overview
Now that you have your requirements and capabilities established for your electrical system, you need to determine the devices you'll use to accomplish them. This component selection took me a long time, as there are vast troves of information to sift through and are many ways to skin this metaphorical cat.

The escence of this step is breaking down your plan into specific components to implement it. Specifically, I determined the exact charge source devices (solar panels, alternator, and AC), what each charge component needs to actually charge batteries, what batteries to use, and what to connect to discharge and use the batteries via loads. This sounds like a lot, and it is! These components are the actual guts of your electrical system, so it's imperitive to understand the lingo, research intensively, read tons of spec sheets to ensure proper and safe integration to efficiently and cost-effectively solve your capability problem. It can be daunting, but forums, personal resources, and companies' support emails are your friends - people love to help and share knowledge.


### Approach
I made some shortcuts when selecting components due to my tight 2.5 month build timeline. Ideally, you'd design and review the system and then buy components. In my case, I had to parallelize my process: research, design, purchase, and install different areas of the electrical system all at the same time. I'd be installing one area while researching another and buying another. For instance, I bought solar panels before having an electrical design, since they were one of the first things I needed to install. When researching an inverter, I had already purchased my batteries <-TODO verify>.

Regardless, let's start with the charge sources. The first step here is solar panels.

#### Charge sources - solar panels
Solar panels simply harness the sun to make energy. In their simplicity, they don't provide further regulation of this energy - they just pass it across a wire! You can't guarantee that a solar panel on it's own will deliver electricy in the "form" your system is familiar with. That is, in a 12V system, your solar panels need _something_ to ensure they also talk this same 12V language.

This is where a solar charge controller comes into play. These controllers live up to their name - they control the power coming into the system from the solar panels. They take the raw power introduced into the system by the solar panels, e.g. up to 18V, and regulate it at a nice, constant 12V.

There are two different options, <-TODO->. For any new build, I would recommend MPPT, as they <-TODO-> compared to <-TODO the other one ->.

The size of solar panels determines how much power they can output. For instance, 150W vs 300W <-TODO->

#### Charge sources - alternator
Another potential charge source is from the alternator or van's starter/car battery. Of course, the biggest concern is linking your starter battery into your electrical system and/or house battery. You don't want your loads to discharge your van's battery - this is a sure way to need a jump!

To ensure isolation, one option is hooking up your own isolator to the actual alternator to ensure no backwards current draw. Another is hooking a battery to battery (B2B) controller to the starter battery, which has enough intelligence in it to ensure there is no backwards draw.

BUT WAIT! What if we combine a solar charge controller and a B2B controller and handle them both at the same time? Well, this is the approach I took! It was about the same price as an MPPT solar controller, and I got two in one. I've been incredibly happy with it.


### Specifics

#### Charge sources - solar panels
I chose 300W (two 150W solar panels in series).