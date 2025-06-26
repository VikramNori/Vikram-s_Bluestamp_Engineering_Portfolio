# ISS Tracker
Have you ever thought about the International Space Station? The permanently manned spacecraft in low orbit of the Earth that travels around the Earth at 17,500 miles per hour and is home to many astronauts and cosmonauts? Have you wondered what latitude and longitude it is directly above? Well, the ISS Tracker does exactly that!

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Vikram N | Cal High | Aerospace Engineering | Incoming Sophomore

![Headstone Image](headshot.png)


<!--
# Final Milestone 

**Don't forget to replace the text below with the embedding for your milestone video. Go to YouTube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

-->

# Second Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/8KgjXdQiv_Y?si=oTuHQKYGt_8P7KV_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


# Summary of Second Milestone Build Process
My second milestone was connecting the Adafruit PyPortal to the Internet to find and track the ISS's location. To do that, I had to create a settings.toml file. One would create a settings.toml file to make sure one can share their code without sharing their sensitive network information. The settings.toml file contains the name of the network and its password, while the code.py file imports the variables by importing the os library with "import os" and uses them to connect to the internet. A surprising part of this project so far has been the fact that my first 2 milestones have just been preparations for the third milestone, where I assume the bulk of the work will be.

Some challenges I faced in this milestone were that my code did not work several times. When making my settings.toml file and testing it out with a test variable, the code.py file did not import the test variable and print it. I tried troubleshooting this by putting all the lines in one by one to see which one was faulty. But when I typed them in that way to find out which one was faulty, they all worked. Now, one of the ways I think it didn't work before was because I messed up the quotation marks, changing what were the variable names and what were the actual values of the variables themselves. After I cleared that up, I misread the instructions to create the code that connects the PyPortal to the wifi. The instructions told me to input the code in the code.py file I've been using since the beginning of the project, but I created another file called code.py (which was also created incorrectly), and inputted the code incorrectly. This created a duplicate code.py file, which had faulty code. Whenever I tried to run my settings.toml code, I kept getting errors on code.py. The problems kept persisting until I tracked down and deleted the faulty file. After I did that, the code finally worked.

The next milestone is getting the PyPortal to track the location of the ISS and display it on a map.

# First Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/YfIg-njLHq4?si=V05FRoKpC91G4Krp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# Summary of First Milestone Build Process
The project tracks the position of the International Space Station and tells you the location on Earth that the ISS is directly above using the Internet. The PyPortal displays the location and holds the code. The PyPortal's desktop covers it, and makes it look better, and the USB-A to USB-Micro cable connects it to the computer while coding on the PyPortal.

My first milestone was loading the PyPortal with all the files required to run the program and building the outside shell of the PyPortal. Loading the PyPortal with all the files was easy. Making the shell for the PyPortal also proved to be not much harder. Even without instructions, I was able to put together the shell in about 30 to 45 minutes. I plan to complete this project in the next week or the next 2 weeks.


# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 


# Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Adafruit PyPortal | It displays the location of the ISS, displays the map, and holds all the code for the ISS tracker | $54.95 | <a href="https://www.adafruit.com/product/4116"> Link </a> |
| Adafruit PyPortal Display Stand | A "shell" for the PyPortal, making it sturdier and easier to hold | $9.95 | <a href="https://www.adafruit.com/product/4146"> Link </a> |
| USB-A to USB-Micro cable | Connects the PyPortal to your computer | $4.00 | <a href="https://www.amazon.com/s?k=usb+a+to+usb+micro+cable&crid=2EEH9XWXH5G8H&sprefix=usb+a+to+usb+micro+%2Caps%2C149&ref=nb_sb_ss_p13n-pd-dpltr-ranker_1_19"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

# Starter Project: Retro Arcade Console
<iframe width="500" height="281" src="https://www.youtube.com/embed/i_2Iimyn7tw?si=MvCyhHR4sTnx0RO8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# Summary of Build 
Since it was a starter project, the build process was easy. There were instructions that I had to follow and I followed them with relative ease. The only difficulty I had was that I soldered one of the diplay panels incorrectly and it wasn't straight. the way it was oriented made it awkward to press the top button. Other than that, there weren't any difficulties.
# Picture of Retro Arcade Console
![Headstone Image](Untitled.png)

# Bill of Materials

| **Number** | **Part** | **Quantity** |
|:--:|:--:|:--:|
| 1 | 12mm 5V Passive Buzzer | 1
| 2 | 220uF 16V Electric Capacitor | 1
| 3 | 4-Pin 90° Micro USB |1
| 4 | 50cm Power Cable (For Micro USB) | 1
| 5 | 8x8 mm Self-Switch | 1
| 6 | Red Self-Switch Cap | 1 
| 7 | 3631AS Digitron Display | 1
| 8 | STC8H3K64S2 IC Chip | 1
| 9 | 1088BS 8x8 mm LED dot matrix module | 2
| 10 | A24 12x12x7 .3mm Button | 6
| 11 | A24 12x12x7 .3mm Button Cap | 6
| 12 | 7x9 .8mm PCB | 1
| 13 | M3x5mm Screw | 8
| 14 | M3x8mm Screw | 2
| 15 | Double-Pass M3x9mm | 4
| 16 | Single-Head 5+6mm Hexagonal Column | 4
| 17 | AAA Battery Case | 1
| 18 | Acrylic Shell | 6


