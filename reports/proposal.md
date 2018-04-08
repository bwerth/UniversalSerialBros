# Project Two Proposal
## Universal Serial Bros.

### Learning Goals

Primarily, we want to learn the basics of firmware development in C by implementing an existing technology that we are interested, but not well-versed in.

### Goals for Project

We are going to write firmware for a microcontroller so that when plugged into a computer it will move the mouse and type keys as random intervals to make the user of the computer think that they’re going crazy. Towards this, we are going to adapt a generalized USB HID implementation to the specific development board that we are using as well as the computer we are communicating with. Following this, we are going to spend the majority of the project working towards an unprompted interaction between the chosen peripheral and the computer.

### What We Need To Get Started

We have a generic USB HID implementation (https://www.silabs.com/documents/public/application-notes/AN249.pdf) along with a wealth of resources to help us in the comprehension of the implementation as it stands (https://www.embedded.com/design/prototyping-and-development/4404116/HIDs-Up, https://www.edn.com/design/communications-networking/4336292/Using-the-HID-class-eases-the-job-of-writing-USB-device-drivers). We also have an STM32 development board that we’ll use for this project. This is most of what we’ll need early in the project, but we are considering purchasing a second development board, considering the size of our group. It’s also possible that we have additional needs later in the project.

### First Steps

The first thing we need to do is install the STM toolchain for use with the development board. Once we have this, we’ll spend time understanding how our USB HID implementation works and establish an initial plan of attack for adapting the implementation to the computer and microcontroller that we are using. Following this, we will establish a more in depth plan for how the autonomous interaction between the peripheral and the computer will work and split up tasks towards that goal.
