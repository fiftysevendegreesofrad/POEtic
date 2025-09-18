# POEtic
Various cool bits from the EU FP6-funded POEtic project I worked on back in 2003. There are some publications in the literature, but these bits didn't get that far and I think they're more interesting.

* ontoroute.avi: a video I made of a waveguide string synthesizer "growing" on POEtic tissue (a biologically inspired FPGA capable of evolution, growth and learning). Every time a note is played, the hardware is reconfigured and a string of the appropriate length grows onto the chip's configurable logic. What you're seeing is (mostly the routing plane of) POEtic's hardware simultor, developed by Yann Thoma at EPFL. Each block of 2x2 routing units represents a cell, and all cells apart from the bottom left are identical. Each cell "decides" to connect to another, and does so until a chain of the requisite length is formed (along with backward connections - each cell downloads it's address to the next to allow this). During the video, the view is changed to show the underlying "molecules" (FPGA cells) for a couple of growth cycles - then switched back again.
* more details on this are given in evaluation_of_poetic.pdf

Related to the waveguide model, here are some sounds made from simulating the acoustics of finite unbounded spaces. Finite but unbounded means like the maze pac-man inhabits: when he leaves one side of the screen, he re-emerges on the other side.

* Sheet.ogg is what Pacman would hear if he clicked his fingers and the maze had no walls. It's not just a click noise because the sound leaves one side of the room and enters the other again... and again...
* Room.ogg is the same thing for a 3-d room.
* A friend asked me what you'd see in a room like that. nice.png is what you'd see if you (the observer) were a black cardboard cutout oval.
* Wormholes.ogg is the sound of a 2d space rapidly being filled up with wormholes which connect otherwise distant spatial points through higher dimensions. 
