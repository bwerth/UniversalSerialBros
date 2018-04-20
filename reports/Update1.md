# Project Two Proposal
## Universal Serial Bros.

### Learning Goals

Primarily, we want to learn the basics of firmware development in C by implementing an existing technology that we are interested, but not well-versed in.

### Goals for Project

We are going to write firmware for a microcontroller so that when plugged into a computer it will move the mouse and type keys as random intervals to make the user of the computer think that they’re going crazy. Towards this, we are going to adapt a generalized USB HID implementation to the specific development board that we are using as well as the computer we are communicating with. Following this, we are going to spend the majority of the project working towards an unprompted interaction between the chosen peripheral and the computer.

### What We Have Done To Get Started

We currently have a base implementation of USB HID. We found a reference design on github for our microcontroller development board and successfully confirmed that it worked. Following this, we split up and began work on three separate extensions of the reference design towards our goal of having the peripheral autonomously control the computer. 

### What We Are Working On Now?

We are working on three separate extensions of the reference design with the goal of eventually combining them to create one massive autonomous peripheral. Bryan is working on using the mouse to repeatedly click on the start button at the bottom left of the screen. His current task is figuring out how to accurately select the correct location on screen. Toby is working on using the mouse and keyboard to click and type at random intervals to make the user think they’re going crazy. His current task is to figure out how to send keystrokes.  Isa is working on keyboard shortcuts for Linux, Mac, and Windows to do things like open up terminals or open the start menu.  Her current task is seeing if there is a way to identify the connected computer’s operating system.
