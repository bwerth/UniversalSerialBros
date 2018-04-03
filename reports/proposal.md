# Project Two Proposal
## Universal Serial Bros.

### Learning Goals

Primarily, we want to learn the basics of firmware development in C by implementing an existing technology that we are interested, but not well-versed in.

### Goals for Project

We are going to reimplement the USB Human Interface Device (HID) protocol using an STM32 development board. As a first pass, we will write the firmware necessary for establishing and maintaining a connection between a peripheral mouse or keyboard and host by building off of existing generic USB HID protocol firmware. As an extension, we would want to experiment with sending data to the firmware via a different type of USB endpoint.

### What We Need To Get Started

We have a generic USB HID implementation (http://janaxelson.com/hidpage.htm) along with a wealth of resources to help us in the comprehension of the implementation as it stands (https://www.embedded.com/design/prototyping-and-development/4404116/HIDs-Up, https://www.edn.com/design/communications-networking/4336292/Using-the-HID-class-eases-the-job-of-writing-USB-device-drivers). We also have an STM32 development board that we’ll use for this project. This is most of what we’ll need early in the project, but it’s possible what we need later in the project might change once we have a more solidified idea of what our system looks like.

### First Steps

The first thing we need to do is install the STM toolchain for use with the development board. Once we have this, we’ll spend time understanding how our USB HID implementation works and we’ll establish a more in depth plan of attack for how we’ll modify the implementation for a specific peripheral. We believe the first modifications will involve adapting the code for use with our development board. 
