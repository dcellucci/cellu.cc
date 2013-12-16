3D Printing (otherwise known by it's infinitely cooler technical name: Solid Freeform Fabrication) is something of a specialty of my lab. We've 3D printed a dinner, a speaker, and even 3D printed robots that then (once assembled) can walk around.

But current methods in 3D printing have some problems. First of all, 3D printing is an essentially analog process. That means it makes things by fusing a bunch of drops of some continuous source material together. Whether these drops are dry or wet or metal or plastic doesn't matter- once they are together they are together, and aside from a chemical bath or heating them up, they are going to stay that way.

An alternative to 3D printing is a method known as _digital manufacturing_. Instead of depositing lots of blobs of a continuous material to build a structure, a digital manufacturing system takes discrete, uniform elements, sometimes called voxels, and puts them together to make a structure. 

One important thing to consider, then, is that digital manufacturing is about **assembly** rather than **construction**. The elements that compose a digital structure are prefabricated- they just get moved around by the 'printer' into a configuration that's useful. 

This confers a few advantages, one of which is really key right now: digital structures are almost perfectly recyclable. You build a thing out of lots of digital elements, you use that thing, then you disassemble it, and use the elements to build something else. Like Legos. Super fancy Legos.

![Perhaps an animated ribosome](http://upload.wikimedia.org/wikipedia/commons/9/94/Protein_translation.gif)

I'm building a manufacturing system that embodies this notion to create fully-actuated robotic organisms with no human input. Instead of Legos, however, I have a different inspiration: molecular biology. Specifically, the ribosome. 

Ribosomes are the machinery that makes life possible. With just 23 basic building blocks, called amino acids, they can assemble the whole myriad of proteins that do pretty much everything a cell needs to do to grow and thrive. They do this by assembling long chains of amino acids together, and letting this chain fold into a configuration that is useful. By changing the order and number of the amino acids that compose the chain, the ribosome can make structures with wildly different sizes, shapes, and chemical properties.

I am using the idea of Ribosomes to make robots that can walk immediately after being printed. To do this, I start with a long strand of dumb material such as aluminum or acrylic, and embed motors and other bits of intelligence at various points in the structure. I then use a 'printer' I've built to bend the dumb parts, skipping the sections that have the smart augmentation. 

The result: a walking creature.

![Sort of looks like the batmobile](@path/walker.png)

Even better is that the material that composes the robot can then be flattened out and folded differently to form a different structure. So if a walker is no longer needed, the robot can just go into the printer and come out a swimmer, or a climber, or a jumper. Really, just about anything.

![Reduce, reuse, recycle](@path/recycle.png)
 
Now the question is, where are you going to be that you can't just make a robot for each task? One place where this could be useful is on deep-space missions. Imagine you're, say, as far from the Earth as Saturn is, or about 68 light-minutes (or 1.22 x 10^9 km). Chances are, everything you chose to take with you, all of your food, equipment, and even the environment that transports you, was given alot of thought before you left. After all, if you need anything, it's not like you can just go out and find it. 

The recyclability of digital manufacturing makes it ideal for this environment. Instead of shipping up a different object for each task, we just ship up all of the little building blocks you'll need, and make the object for each task. For each individual object, you lose a little on the weight- after all, you can make a specialized device that can perform each task better than the one built out of a bunch of little blocks- but overall you end up saving, since each block can be reused again and again and again for a variety of different devices.

Ribosomal Robotics could be the first step towards an self-contained maintenance/exploration platform built for these kinds of extreme conditions. Perhaps our little ribosome folds out a cleaning robot that slithers along the ground, but then it needs a super-compact robot that can fit into a maintenance shaft and fix an electrical short. Instead of having one robot that does everything, a la R2-D2, instead the 'printer' reconfigures the 'cleaner' to become a 'welder', and the newly folded robot. 

![Reduce, reuse, recycle](@path/R2_repair.png)

