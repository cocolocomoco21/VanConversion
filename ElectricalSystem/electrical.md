# Electrical System

## Chapters
1) Capabilities (approach and accomplishing it)
2) Component selection (charge sources, storage, loads)
- Solar panels
- Battleborn batteries
- Kisae DMT 1250
- Kisae 2000W Inverter
- Distribution panel and breakers
3) Layout in physical van
4) Design and safety (walk through diagram)
5) Install (Either component by component or summary)
- Battleborn batteries
- Kisae DMT 1250
- Kisae 2000W Inverter
- Distribution panel, breakers, and fuses
- Bus bars
6) Wiring (general wiring how-to)
7) Protecting wires and prewiring



## Overview
The electrical system of the van is by far the most complex and time consuming. It is the underpinnning for enabling capabilities that seem merely aspirational. Who would, upon first seeing a completely empty and hollow cargo van, think "yep, it's definitely possible" to have a full light system, temperature control, refrigerator, water system, and plumbing? Even more, let's make it fully off-the-grid and self sufficient, so that you can have these capabilities without relying on plugging in and entirely self-contained within the van's walls? That magic is what the hard work of the electrical system enables.

For the next posts, I will be starting a series outlining my entire electrical system. This will cover the full process: from defining what I want my electrical system to capable of, the components to get there, their layout, design and install, and everything in between. I'll walk through my electrical diagram, what each main component is and why I chose it, how I physically installed them, and much more. I'm excited for this knowledge sharing and hope you apprecaite the information!

To start this process, I had very little electrical-specific experience. When seeing me working on the van, people always ask "you built this van yourself, did you have prior experience?" I always answer "sort of." Growing up, I would work around the house with my dad on DIY projects. I took wood shop in high school and like working with my hands. I actively participated in robotics in high school and college, but only have transient knowledge of electrical (I did some mechanical and mostly software). However, I've always loved engineering, designing, and building. I have general aptitude, but very little expertise in any one specific area.

 All of this to say, the electrical system and these posts represent my learned and shared knowledge. I couldn't fall back to any one person's expert experience in van electrical systems. I was able to accomplish everything with the joined help of many people, so thank you very much to those who helped along the way. I wouldn't have been able to do it (safely, at least) without the oversight of some more knowledgeable folks :).


## 1. Capabilities
### Background
The first step in completing an electrical system is understanding what you're trying to get out of it. For me, this is a reasonably straightforward answer: I wanted to be able to live, work, and play out of the van and be able to be self-sufficient for up to ~3 days without a charge.

Let's look at what these mean. "Living" for me means being comfortable in moderation. For example, lights are required, but running water is a nice-to-have. I needed heat for winter and a fan for summer. A fridge could be nice compared to a cooler with ice. A van is a weird line between a home and camping, and refining these comfort vs. camping requirements for your own case naturally leads to a list of ideal vs. real capabilities, which helps create a capabilities list for your van.

"Working" means working as a software engineer remotely, potentially for an afternoon or for a month. I need to charge up to two laptops, two phones, a hotspot, for 8+ hours a day. Pretty straightforward.

"Play" means I want to get out and do things! I may be with or without service. It may be 100 degrees or -20, with incessant or non-existent sun. I want to climb, ski, bike, and hike wherever, and handle nearly anything I throw at myself.

By asking yourself what you want, as I did, you determine your worst-case requirements. In my worst case, I would be somewhere with no sun (spoilers, I have solar panels to charge ;) ) and still post up and function without having to leave. An example would be winter skiing and working. If it were to by cloudy (and ideally snowing!) for three days and therefore providing no solar charge, but I was skiing + working, I'd still need to plan for multiple device charging for three days, heat for three days, refrigeration, lights, running water, etc.

After assessing your needs, you can develop a capabilities list and determine how to accomplish your goals from there!

### Approach
There are many ways to realize your capabilities, but they largely break down on the fundamental structure of an electrical system: charge sources, storage, and loads.

Fundamentally, the center of the system is the storage. You hold all of the energy that you consume. If that storage goes to 0%, you have no power! Oh no. This is the purpose for batteries. There are some different battery approaches, which I'll touch on in a later post.

Charge sources, well, charge the batteries. This can be accomplished through various means. Solar panels are common in van communities, but you can also charge off the alternator while you drive the car, from AC power like RVs, or from a hamster ball (rarely seen in vans).

Loads are the fun part! They are the components which use the energy you work to store. For example, heater/fan, fridge, lights, water pump, antenna, any AC  loads you'd use at home, phones, battery monitors, inverters, etc. They also take a lot of upfront work to design your system around, because knowing your max potential load draw determines your battery capacity, which determines your charge sources. 

### Specifics
