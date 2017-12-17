# Mitsubishi_AC_IR_Research
In this project, I will be attempting to take the Arduino's IRremote library to create part of the program for the CXHomeSmart project. Because I haven't got it to work before, I do not want to lump it together with the actual project.

# Research Notes - 17 Dec 17

As I am working on the research for the IR remote codes, I have discovered that the Mitsubishi Electric Inverter in my room has some kind of proprietary coding. When I press the ON or OFF buttons, the combinations of code seems to always be changing. Some of the codes look like they are repeating, but because they have 2 separate codes, it seems like there is a random, yet not so random sequence. Let's just call it different combinations for now.

My goal tonight, or over the next few days would be to attempt to decode and compile those combinations, maybe produce a chart for it to see where the combinations usually land. It might seem random at first, but I do notice some sort of pattern as well.

I will be tabulating the combinations in the following manner:

						Code One				Code Two
					----------------		----------------
Combination #1		{...,...,...,...}		{...,...,...,...}
Combination #2		{...,...,...,...}		{...,...,...,...}
Combination #3		{...,...,...,...}		{...,...,...,...}
