Taco Browser is probably the world's first internet browser made for the Playstation 1.

#How it gets data from the internet
Taco Browser communicates to a PC which has data connectivity using 2 different mediums: the serial port on the back of every PS1 and using a controller cable.

##Communicating with the PC

The serial port is simple: build a cable that does PC Serial port < -- > PS1 Link cable 

The controller part is a bit more complex. Basically what we do is we take two PS1 controllers, cut the cord on both of them, combine the two, plug one end to the PS1, the other end to a PS1 controller cable -> USB adapter, and then plug the USB into your computer.

###Where to get these things
We got our two controllers from Amazon and a Playstation 2 controller -> USB on Amazon. We haven't tested it but it seels like it'll work for the Playstation 1 as well.

There are guides that teach you how to make your own. We will probably just make my own and probably make a couple and ship them to people for free if they want one.

###Resources for communicating with the PC
We will be listing the resources we used for communicating to the PC and back here:

None yet :) check back soon!

#How it renders the data
Right now, the plan is to just send a bitmap of how the website looks and send "mouse press" x,y values to the computer and simulate a web browser. However, that's super lame and not cool at all so after we get that working, we will write an actual HTML renderer for the Playstation 1.

#Contributing

The most important section of any readme! We would love to receive advice from people about how to implement this but considering it's such a young project it's probably not the best idea to receive development help from people just yet. More is explained about this below. 

Physical items we are in need of (that we (or should I say, wilfriedE) could make ourselves but would take a lot longer):

- Modchip for PS1
- PS1 Link Cable < -- > PC Serial Port < -- > (maybe USB) 

We can test everything in an emulator for now, but eventually we will have to test on an actual device.

For the software side of things, the project is in a super early state so it might not be the best idea to have a ton of collaborators right away. Right now it's just coldsauce and sypherio.  Submitting a few bug fixes, updating the documentation, implementing a feature that we are looking to implement is totally fine and definitely encouraged but working on the more "structural" side to development (an example would be discussing the direction the project is taking) with more than 2-3 people sounds like a bad idea to me. Given that it is in such an early stage, that kind of structural development is something that will occur a lot more often and because of that, it's probably not the best idea to have a ton of collaborators.

However, if you feel really excited about this project and want to work on this, email coldsauce: stefan@stefanaleksic.com

Please don't just fork the repo and then work on something and submit a pull request. Chances are someone is probably working on the same thing and you just wasted so much time for no reason. The other reason for why it's bad to do that is we might never accept your pull request. It might be a feature that is something we are not looking to add. This could be avoided by just asking us
whether a feature is something we're looking to implement or looking at the issues and seeing if the feature was requested.

#You are probably asking youself: "Why?"
The answer is simple: why not? I like making cool things just for the sake of making cool things. I don't care if they will never be used. I'm not making them to be used, I'm making them because I like making them as well as showing and talking to my people about them.

The reasons I am working on this are:

- Techinically challenging. Probably the most difficult thing I will have ever done.
- Really bizare.
- Get to play Ps1 games on my Ps1 and not feel guilty about buying it.
- Get to learn MIPS assembly which I need to know for my class.
- Learning more about writing drivers.
- Get to write an HTML parser in C
- Have fun

You could create a mosaic floor and it would be super useful for people walking on it or you could create a stained glass mosiac window and people could look at it but it wouldn't provide much utility. I feel like this project is the latter. Sure, people could use it, but at the end of the day, I don't expect anyone to. It's just a cool project to read about and possibly learn more about the PS1 from.

#Credit where credit is due

- Coldsauce (Stefan Aleksic) originally came up with the idea. He is working on the software side of things!
- Sypherio (Steven Teplica) is working on the software side of things as well!
- WilfriedE (Wilfried Hounyo) is working on tthe hardware side of things. 

We are all 2nd year students at the Rochester Institute of Technology in Rochester, NY.
