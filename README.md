# SOURCE TITLE H1 - ABCDEfgjilm01234

## SUB TITLE H2 - - ABCDEfgjilm01234

### SUB TITLE H3 - - ABCDEfgjilm01234

Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat [LINK](https://en.wikipedia.org/wiki/Raspberry_Pi) Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat : 
	[LINK NAME](https://www.sunfounder.com/learn/Super_Kit_V2_for_RaspberryPi/lesson-6-buzzer-super-kit-for-raspberrypi.html)
  
Image link:

![Image](https://www.sunfounder.com/media/wysiwyg/swatches/Super_kit_v2_for_raspberrypi/6_Buzzer/5.png)

### SUB TITLE H3 - - ABCDEfgjilm01234
To build this program under blablabla, you fist need to have wiringPi library installed.
To download and install wiringPi library, please follow this link: [WiringPi Library - download and install](http://wiringpi.com/download-and-install/)

To compile and run this program, do:

 `$ gcc pimorse.c -o pimorse -l wiringPi [ -DDEBUG ]`

(DEBUG is optional, just to have more verbosity during execution)

and run with:

 `$ ./pimorse`

### Build program to run in a PC for simulation
You may also want to run this program in a linux PC, out of a 
Raspberry box just to test it and see how it works, even if you don't
have the related hardware and accessories. 
In this case you can compile program by entering:

 `$ gcc pimorse.c -o pimorse -DNOPI -DDEBUG`

( DEBUG is optional here as well, but I suggest you to use it together with -DNOPI parameter, otherwise you can't realize the progress of program, since you don't have any audio output. At least, in this way you may see console output when program converts message to morse, with the same timings as you had buzzer playback. )

**License**
This source is released under the terms of *GNU General Public License V. 3.0.*
Permissions of this strong copyleft license are conditioned on making available complete source code of licensed works and modifications, which include larger works using a licensed work, under the same license.
Copyright and license notices must be preserved. Contributors provide an express grant of patent rights.

This is a unnumbered list:

- item1
- item2
- item3
	- subitem 1
	- subitem 2
	
	
Numbered list:

1. item1
1. item2
1. item3
	1. subitem 1
	1. subitem 2
	
	



