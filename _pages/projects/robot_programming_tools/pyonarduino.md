---
permalink: /projects/robotics_programming_tools/pyonarduino/
title: "PyOn Arduino"

sidebar:
  nav: "docs"

layout: archive

classes: wide
---



## PyOnArduino: Compiling Python to Arduino language

<i class="fab fa-fw fa-github"></i> [**PyOnArduino GitHub**](https://github.com/JdeRobot/PyOnArduino)
{: .notice--info}


JdeRobot-Kids is an academic framework for teaching robotics to children in a practical way. It is based on Python, the kids have to program typical robot behaviors like follow-line using Python. JdeRobot-Kids is now mostly centered in the mbot robot, from makeblock, both the real robot and the simulated one in Gazebo. Mbot is an Arduino based robot. Currently the student application runs at a regular computer, which is connected to the onboard Arduino. Arduino and PC interact using the Firmata protocol. This approach requires a continuous connection between the robot and the off-board computer. Arduino is limited on computer power so it is not enough to run a Python interpreter. The goal of this project is to "compile" the Python application to Arduino microprocessor. This way the kid program can be fully downloaded on the Mbot robot and run completely autonomous. Another possibility is to translate Python application to C/C++, as gcc/g++ already compiles it to Arduino microprocessor. Some ideas to explore are: [LLVM](https://llvm.org) compiler infrastructure, [cython](https://cython.org)...



<figure class="half">
    <a href=""><iframe src="https://www.youtube.com/embed/k-xIU_cmcac"></iframe></a>
    <a href=""><iframe src="https://www.youtube.com/embed/_k17V5pxrd8"></iframe></a>
    <figcaption>PyOnArduino Projects.</figcaption>
</figure>


### PyOnArduino Projects

- [Sergio Paniego](https://jderobot.org/Club-spaniego).






