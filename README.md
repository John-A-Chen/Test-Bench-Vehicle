# Test-Bench-Vehicle  
A compact experimental platform developed during my time with the now defunct **UTS Motorsports Autonomous team**.  
This project was designed, modelled and assembled over the **first week of winter break**, with the goal of showcasing a functional autonomous systems testbed at **TechFest 2024**.

---

## Overview  
The Test-Bench Vehicle is a lightweight, quickly-deployable robotics platform used for:

- sensor validation  
- control-system testing  
- autonomous navigation experiments  
- rapid prototyping of perception and actuation modules  

It was designed as a **core development platform** for the team — something small, reliable, and adaptable enough to test software before committing to full-scale vehicles.

The initial concept, CAD work, and assembly were completed rapidly to prepare for TechFest demonstrations.  
This repo documents the entire process.
Note: there are rebuild errors because this was all made on SolidWorks 2021 and I was far less skilled.

---

## Background  
During winter break, I dedicated the first week to building this test platform from scratch, inspired by the team's need for a **modular, extensible, low-risk test vehicle**.  

Two LinkedIn posts describe the original design intent and showcase the project:

- TechFest showcase post:  
  https://www.linkedin.com/feed/update/urn:li:activity:7212804788307025920  
- Build + development post:  
  https://www.linkedin.com/feed/update/urn:li:activity:7212802896566919169

These posts reflect the project’s purpose:  
a fast, functional, cleanly designed robotics platform to support autonomous motorsports research.

---

## Design Goals  
- Create a **stable, compact platform** for autonomous algorithm testing  
- Support sensors like LiDAR, cameras, IMUs and GPS  
- Provide an accessible workspace for wiring and electronics  
- Allow quick swapping of components for experimentation  
- Use 3D-printed and laser-cut parts to keep development rapid  
- Make the mechanical structure reliable enough for repeated testing  
- Showcase engineering capability during TechFest  

---

## Features  
### Mechanical  
- Custom chassis designed for rigidity and sensor mounting  
- Modular top deck for easy reconfiguration  
- 3D-printed housings and brackets  
- Low CG layout for stability during autonomous runs  

### Electronics  
- Space for microcontrollers, SBCs, ESCs, power distribution  
- Mount points for LiDAR, stereo cameras, GPS, etc  
- Clean cable routing and accessible layout  
- Designed with debugging in mind (open structure, tool clearance)  

### Software Integration (Team-Level)  
- Intended for autonomous stack testing  
- Suitable for perception, localisation and basic control  
- Precursor platform for larger vehicle integration  

---

## What’s In This Repo  
Depending on current progress, this repository may include:

- CAD files (Fusion/SolidWorks)  
- STL parts for printing  
- Mechanical drawings and fit tests  
- Wiring notes and layout images  
- Photos used for TechFest presentation  
- Build logs from the initial sprint week  
- Revision notes and future iteration ideas  

---

## Repository Structure  
```

/cad            Main chassis + mounts + brackets
/docs           Build notes, images, slides
README.md       Documentation

```

---

## Why This Project Matters  
In autonomous motorsports, development cycles are fast and experimentation is constant.  
You need a reliable, small-scale platform to test algorithms **before risking the actual car**.

This test-bench vehicle was built exactly for that reason — to give the team:  
- a safe playground for autonomy code  
- a hardware foundation for experimenting with perception  
- a hands-on platform to demonstrate capability at TechFest  
- a rapid prototype that others could iterate on  

It represents early-stage engineering momentum, team contribution, and a strong understanding of rapid design-to-prototype workflows.

---

## Future Plans  
- Improved chassis rigidity  
- Revised sensor mounts  
- Proper documentation for future team members  
- Integration examples (LiDAR + camera + controller)  
- Video demos of autonomous tests  
- A “build your own” guide for new recruits  

---

