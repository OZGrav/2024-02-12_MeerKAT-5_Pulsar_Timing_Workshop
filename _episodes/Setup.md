---
title: "Software setup"
teaching: 10
exercises: 10
questions:
- "What software do I need?"
objectives:
- "Get all the necessary software installed before beginning the lessons"
keypoints:
- "How to install software"
---

## Assumed knowledge

This course assumes that you have basic proficiency with the command line / bash terminal, a text editor and simple Python scripting.
If you are unfamiliar with any of these concepts, we recommend the following tutorials:

- (linux) command line / bash [SWC Lesson](https://swcarpentry.github.io/shell-novice/), [ADACS Lesson](https://adacs.org.au/courses/introduction-to-bash/)
- command line text editor ([emacs](https://www.linuxfordevices.com/tutorials/linux/emacs-editor-tutorial)/[vim](https://www.tutorialspoint.com/vim/index.htm#)/[nano](https://www.linuxfordevices.com/tutorials/linux/nano-editor-in-linux))
- Python scripting [SWC Lesson](http://swcarpentry.github.io/python-novice-gapminder/), [ADACS Lesson](https://adacs.org.au/courses/introduction-to-python/)


## Required software

To make the software installation easier we are going to use a virtual machine (VM) that has all the required software preinstalled.
We will run the VM using VirtualBox which is a tool for managing and running VMs.
To install, follow the instructions in [here](https://www.virtualbox.org/wiki/Downloads) which contains detailed instructions.
The following sections will will summarize how to install on common systems.
If you have an issue refer to the [full instructions](https://www.virtualbox.org/wiki/Downloads) on the website or email Nick (nswainston@swin.edu.au)

### Windows

Download the `.exe` file from [this link](https://download.virtualbox.org/virtualbox/7.0.10/VirtualBox-7.0.10-158379-Win.exe) and follow the setup instructions.

### Linux (Ubuntu 22.04)

How to install is OS dependent so there are more details instructions [here](https://www.virtualbox.org/wiki/Linux_Downloads).
Here is an example of how to install it for Ubuntu 22.04 by downloading the `.deb` and installing it with `apt`:
```
wget https://download.virtualbox.org/virtualbox/7.0.10/virtualbox-7.0_7.0.10-158379~Ubuntu~jammy_amd64.deb
sudo apt install ./virtualbox-7.0_7.0.10-158379~Ubuntu~jammy_amd64.deb
```




### VirtualBox tips and FAQ

VirtualBox can be a bit confusing at first so here are a few tips:

- If you VM fails to start, check the logs (`Ctrl + L`) for clues why.
If you see an error like `HM: HMR3Init: Attempting fall back to NEM: VT-x is disabled in the BIOS for all CPU modes`
you have to change your BIOS settings to enable virtualization technology (e.g. for [ASUS motherboard](https://www.asus.com/us/support/FAQ/1045141/))
- You can use Right Ctrl to use VirtualBox [shortcuts](https://defkey.com/oracle-vm-virtualbox-shortcuts#54716)
- To make use of your full screen resolution open `View` (top left), then `Virtual Screen 1` and click `Scale to 100%`.
Then once you change the window to full screen it should use your full screen resolution

