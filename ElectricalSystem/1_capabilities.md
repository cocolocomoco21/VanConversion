# 1. Capabilities

### Overview
The first step in completing an electrical system is understanding what you're trying to get out of it. This step requires a lot of thinking and planning! For me, luckily this step has a reasonably straightforward answer: I wanted to be able to live, work, and play out of the van and be able to be self-sufficient for up to ~3 days without a charge.

To figure out how to build my system, let's look at what these mean for me. "Living" for me means being comfortable in moderation. For example, lights are required, but running water is a nice-to-have. I needed heat for winter and a fan for summer. A fridge could be nice, but a cooler with ice could also work. A van is a weird line between a home and camping, and refining these comfort vs. camping requirements for your own case naturally leads to a list of ideal vs. real capabilities, which helps create a capabilities list for your van.

"Working" for me means working as a software engineer remotely, potentially for an afternoon or for a month. I need to charge up to two laptops, two phones, a hotspot, potentially power an antenna, and have reliable internet for 8+ hours a day. Pretty straightforward.

"Play" means I want to get out and do things! I may be with or without service. It may be 100 degrees or -20, with incessant or non-existent sun. I want to climb, ski, bike, and hike wherever, and handle nearly anything I throw at myself.

By asking yourself what you want, as I did above, you determine your worst-case, or most extreme, requirements. In my worst case, I would be somewhere with no sun (spoilers, I have solar panels to charge ;) ) and still post up and function without having to leave. An example would be winter skiing and working. If I were to stay in one spot for three days and it were to be cloudy (and ideally snowing!), and therefore providing no solar charge, but I was skiing + working, I'd still need to plan for multiple device charging for three days, heat for three days, refrigeration, lights, running water, etc.

After assessing your needs, you can develop a capabilities list and determine how to accomplish your goals from there!


### Approach
There are many ways to realize your capabilities, but they largely break down on the fundamental structure of an electrical system: charge sources, storage, and loads.

Fundamentally, the center of the system is the storage. You hold all of the energy that you consume. If that storage goes to 0%, you have no power! Oh no. This is the purpose for batteries. There are some different battery approaches, which I'll touch on in a later post.

Charge sources, well, charge the batteries. This can be accomplished through various means. Solar panels are common in van communities, but you can also charge off the alternator while you drive the car, from AC power like RVs, or from a hamster ball (though this is rarely seen in vans).

Loads are the fun part! They are the components which use the energy you work to store. For example, heater/fan, fridge, lights, water pump, antenna, any AC  loads you'd use at home, phones, battery monitors, inverters, etc. They also take a lot of upfront work to design your system around, because knowing your max potential load draw determines your battery capacity, which determines your charge sources.

Lastly, I'd be remiss to omit what type of electricity the electrical system functions on. You generally want the system to use DC power as much as possible, as AC requires an inverter which operates at 80-95% efficiency. This means even in the best case, you waste power when using AC! Phones, heaters, fans, lights, and many of the things that you might associate with plugging into your wall at home can run/charge off of DC! Nearly all of these devices use DC, and as a matter of fact, the brick or adapter you plug into your home outlet actually converts it from AC to DC! You can therefore skip this conversion step and save power. I use 12V DC, but some builds use 24V DC as well.

### Specifics
By combining all of this planning together, I was able to define the requirements for my system. This looks like:

#### Storage
- 200Ah (amp-hour) battery capacity. I have two 100Ah lithium batteries in parallel

#### Charge source
- Two 150W solar panels, providing a max <-TODO->W/<-TODO->A of charge per hour
- Alternator/starter battery charging, up to 50A
- AC charging (15A) into inverter. Not really required or used for me, but is a loose nice to have

#### Loads
I'll save the specifics of each load for separate posts, but I went with DC:
- Webasto gasoline heater 
- MaxxAir fan
- Dometic fridge
- <-TODO-> water pump
- 12V DC charging ports (3) (USB fast charge + "cigarette lighter" inputs)
- Puck lights (12), on dimmable 12V switches
- Inverter (converts to AC loads, but runs off of DC)
- Victron battery monitor
- LED light strips for garage

and AC:
- Laptop
- Magic bullet?
- Router?
- Misc appliances/gadgets from a house 