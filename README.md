# Waithax-Calculator
A Calculator to use your current hex value to determine time remaining while using Waithax

Website: http://waithaxcalc.spencers.website/

Github: [https://github.com/Suspence00/Waithax-Calculator](https://github.com/Suspence00/Waithax-Calculator)

Jscalc.io Source: [https://jscalc.io/calc/G1dRS9waejau9dcF](https://jscalc.io/calc/G1dRS9waejau9dcF)


**Latest v1.96**

* Major rewrite of code using moments.js by @sluther

Latest v1.95:

* Fixed bugs in time display (Thanks /u/Neechnach2002) and made the code far more stable

* Added testing values in the source code

* Cleaned up a majority of the code, scrapping a bunch of it for easier implementation

* Minor text fixes

v1.9
*  Should be completely working now, you only need to enter your current hex into the first input box and it will automatically calculate (praying_emoji.png)

* Added "Percentage Complete" and "Time Elapsed" outputs in addition to "Time Remaining (HH:MM:SS)"

* 0x1010101 is set as the default starting hex, 0x10000 is the default drop rate and 16 Seconds is the default time. This seems to be standard for all 2ds/o3ds/n3ds but is still modifiable for experimental purposes.

v1.85:
* Starting Hex and Drop rate are now modifiable (though, not recommend except for experimental purposes as the default values are the same across all 3ds devices surveyed so far
* To-do: Implement percentage left and amount of time passed)

v1.8:
* Fixed issues with time increasing instead of decreasing (but actually this time)
* Now only hex needed is the current one as 0x1010101 has been confirmed as the starting hex and 0x10000 as the hex drop rate. These are * * both still editable (though now at the bottom of the input list) in case you decide to mess with it.
* Note: Changing the starting hex currently has no effect, TBA
* New Source code pasted here: https://github.com/Suspence00/Waithax-Calculator

v1.5:
* Fixed issues with time increasing instead of decreasing
* Commented and edited the Spaghetti code

v1.1:
* Added default values and commented source code for future implementations

v1: Initial

I programmed a calculator for figuring out how much time is remaining while using Waithax https://3ds.guide/dsiware-downgrade-\(save-injection\). This probably isn't perfect, I'm open to any and all suggestions (I'm a novice coder at best). 

I've gotten so much from the 3ds homebrew community, hopefully this helps someone out! 

Credit goes to /u/Onoitsu2 for posting a "formula" here https://www.reddit.com/r/3dshacks/comments/5i1lk8/full_arm9loaderhax_cfw_guide_update_waithax/db4ptrj/ and to /u/neenach2002 for additional information.

 Created with [Jscalc.io](http://www.Jscalc.io/), Source code can be found here: https://jscalc.io/calc/G1dRS9waejau9dcF
