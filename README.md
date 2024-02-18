# tools_usb
so, here we are, my first github project. 
i envy the accomplished feeling i will get if this ever succeeds and that's my main driving force for this one
as well as the use i will get out of this tool once made.

# overview 
at the charity i volunteer at, a lot of what i do involves booting into old systems, running diagnostics and installing new operating systems and disk images.
for this, i normally used my trust medicat usb which has a bunch of nice tools and installers that work fine when i can get them to.
my main issues arises when i have to try to get into the bios and boot into the bios version of the medicat for different tools and having to get a working keyboard and monitor set up to navigate these. 
it's tedious so in the spirit of doing things myself, i have this idea for a usb tool that can do anything and everything from emulating a storage device containing only one selected boot iso, to being able to act as a keyboard and perform macros and even maybe pulling hardware information for the system but i feel like that one will be a reach.

# where i'm at
i decided to use a pi zero 2, along with a usb interface, screen and simple buttons. 
on this, i want to have u-boot and a small form of linux running on which i can make a simple interface to select different ,,things that i want it to be doing.
i want to be able to select live isos to boot into, or installers, or diagnostic programs or whatever. all from the usb device itself rather than booting into a usb and selecting from there. 

with the hardware chosen, and subject to change, all i need to do now is create the interface and function i want and set up the device to be able to perform them.
sadly i have little knowledge in software development other than basics of python, c, java, lua as well as an understanding of how an embedded device like this would work technically, 
so this repository will be for documenting and sharing my work so that other people may be able to help fix bugs, implement features or just use it themselves.
