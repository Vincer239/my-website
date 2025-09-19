---
title: Projects, Hobbies and Interests
description: My projects

projects:
  - title: "ADMIRE"
    technologies:
      - "C"
      - "VHDL"
      - "Microkit/seL4"
      - "ARMv8a ISA"
      - "Vitis IDE"
    timeline: "01/2024 - 12/2026"
    content:
      - "ADMIRE - *Advancing Miniaturized Radar* - is an DLR internal project, maturing radar systems particularly for space applications. Within the scope of ADMIRE, one goal is to mature on-satellite signal processing in order to preserve bandwidth on the downlink. Here, the intention is to use FPGA based accelerators, which efficiently process radar signal. My role in ADMIRE is to develop a hypervisor concept which can manage hardware accelerators as well as handle all software tasks. In the wake of this, I am developing a *'hardware hypervisor'*, designing the interface between a classically software based one and the hardware accelerators. Focus is laid on performance and safety."
  
  - title: "XANDAR"
    technologies:
      - "SysML"
      - "C"
      - "Rust"
      - "XtratuM"
      - "Makefile"
    website: "https://xandar-project.eu/"
    timeline: "01/2021 - 12/2023"
    content:
      - "XANDAR (_X-by-Construction Design framework for Engineering Autonomous & Distributed Real-time Embedded Software Systems_) is an EU project comprised by industry and academic partners within the automotive, aviation and software tooling domains. The project delivered a mature software toolchain, enabling fast and robust prototyping from capturing requirements to systems modelling all the way up to code generation and Verification and Validation (V&V) on the target hardware platform. By integrating advanced safety patterns, runtime monitoring and modern code generation into the toolchain, multiple attributes (safety, security, reliability, etc.) are fulfilled, realizing the X-by-Construction paradigm. Particular focus is laid on non-deterministic AI/ML artifacts, which are primarily used for autonomy functions within the automotive and aviation domain."
      - "Within the project, my role was to develop an avionic demonstrator to further mature and test the toolchain. The demonstrator contains an instance of an ADS-B based Collision Avoidance System ([OpenCAS](https://github.com/aeronautical-informatics/opencas)) and a Terrain Awareness and Warning System ([OpenTAWS](https://github.com/aeronautical-informatics/opentaws)) executed within a partitioned environment within the XNG hypervisor, simulating the functionality of an avionic computer.Thanks to this project, I was able to hone my skills in `C` and `Rust` as well as learn how aviation-grade hypervisors operate. On a more meta level, I got to experience the role as a high- and low-level system engineer, both designing high-level architectures (from its requirements to its structure) as well as its low-level implementation on the hardware."

  - title: "Energy Storage System of SeeSat Satellite"
    technologies:
      - "Electronic Design"
      - "Power Electronics"
    timeline: "06/2021 - 03/2022" 
    content: 
      - "Within a student research program, I got to develop the Energy Storage System concept and most parts of its electronic design for a cubesat satellite: SeeSat. Sadly, due to the aftermath of the COVID pandemic, it was not possible to actually produce the results. However, especially the power management systems have been matured a lot and are in use in other student cubesat programs **(need to put prove here)**"
  
  - title: "Student Project - Building a bicycle computer"
    technologies:
      - "C"
    timeline: "Semester in 2021"
    content:
      - "This project was a part of my undergrad education and has been literally the first embedded coding project, which I have ever done! Basically nothing special, just playing with an Arduino and writing all the code from scratch to interface with hall sensors, gyroscopes and accelerometers, as well as displays and rudimentary I/O for that. The result worked out *good enough* for the purposes."
      - "Since then, with all the various experiences and skills later, it is back on my hobby table to redo it. This time in bare-metal Rust, with custom circuit boards and custom designed processor IC. This might be the holy grail of over-engineering but I am certain that it will help me learn a lot about all the different aspects within this build."


hobbies:
  - title: "Music"
    technologies: 
      - "Trombone"
      - "Euphonium"
    timeline: "ongoing since 2012"
    content:
      - "Music has always been a part of my life! For more than half of it, I am actively playing in diverse orchestras and band, spanning from traditional bohemian music to jazz and classical concerts all the way to movie soundtracks and pop medleys. I have had times of teaching students and/or conducting bands. Currently, I play in [AkaBlas](https://akablas.de), mostly euphonium and sometimes still a little trombone."
  
  - title: "Traveling and Exploring"
    timeline: "whenever there is time :)"
    technologies:
      - "Hiking"
    content:
      - "Going back as far as my obsession with playing music, I have been on the road. At first, it was a part of my Boyscouts life: a backpack, a tent and a good pair of hiking boots, and off you go with your fellow friends to unknown roads all over Europe. It transitioned into more international travels, both of personal and professional nature, and now it is coming back to its roots, again. It is time to go slower but see more details instead of rushing to see all the places but not managing to actually take a good look."
      - " All these kinds of travels have taken me through the majority of Europe, North America, South East Asia, and North Africa. I want to fill in the last blanks of Europe by either hiking or doing long-distance bicycle tours. The next stop on the list are most likely Scandinavia and Baltics, but who knows where the wind will take me ;)" 
  
  - title: "Climbing, Running and Bicycling"
    technologies:
      - "Climbing"
      - "Cycling"
    timeline: "Mostly since COVID"
    content:
      - "As I have always been more inclined towards music and everything that goes that way, I have lacked a bit on the physical activity side. Funny enough, I was always in pretty good shape to do any of my hiking adventures (or maybe *because* of it). With the COVID pandemic messing with everyone's life a few years back, it also messed with mine and I found back to a forgotten sport: running. From here (albeit doing it really irregularly), the slope continued to climbing and in the end to cycling. I don't really have ambitions to do any of it in a competitive setting, though. It is just for me to unwind and also an opportunity to see the world as it is."
---
