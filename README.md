# Process for a High Performance Multiple Montior Setup on Windows
I will keep track of my trials and tribulations, but most importantly, results of my proper or ideal multiple monitor setups for Windows using high performance consumer GPUs.

There are many complicated problems you will run into when trying to get multiple monitor setups going on Windows.  I have spent countless hours and spent so much money on cables and adapters in the past decades dealing with this.  I finally decided to keep track of my best conclusions and sort of a guide here for myself and anyone who wants a quick way to understand and deal with this.  It's not very easy googling around and finding everything.

## Equipment
 - A GPU with multiple outputs.  Since I am saying High Performance, I mean a good, modern GPU that gamers would use and that is popularly available at any given moment.  There are specialty cards out there that have like 6 outputs, but you can't game with them and they are like decades old now.  This is not for that kind of commerical applications (signage, etc).  This is for the typical home user who might use his GPU with his working PC as well as a nice 4k TV and other things around the house.  This is where it gets tricky.
  - HDMI Cables
  - DisplayPort Cables
  - Adapters
  - Monitors and Televisions
  
## Software
 - Your GPU's driver software (Nvidia or AMD most likely)
 - (optional) multi-monitor tools like DisplayFusion or Actual Tools
 
## BIOS settings

## "What if... ?"

## Tips & Tricks
This is a very clever solution for those that have Dell monitors.  I tried it and it works very nicely.  


https://www.dell.com/community/Monitors/U2518D-turn-off-without-using-button/td-p/7526668


If you have a Dell monitor, you can switch the input using a command line.  So you can make a bat file and do automation very easily.  It doesn't technically turn the monitor on or off, but you can switch to an unused output port to have it go to sleep, and switch it back to your pc port to turn on.  It works very well.  What does this solve?  Since the monitor never turns off, it is always connected to the pc, so there is no problem with the windows rearranging.  This also removes the need for those MDK adapters I normally use for all monitors.  The MDK adapters do not work with active (fiber optic) HDMI cables (they have not responded to my inquiries, they insist it works with any hdmi situation).

## Glossary of all the freaking terminology and specifications
