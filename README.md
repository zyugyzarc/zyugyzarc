---
documentclass: extarticle
fontsize: 12pt
colorlinks: true
geometry: margin=50pt
header-includes: |
  \usepackage[dvipsnames]{xcolor}
  \usepackage{tikz,kantlipsum}
  \usetikzlibrary{tikzmark}
  \definecolor{bgcol}{HTML}{20349F}
  \usepackage[none]{hyphenat} 
  \usepackage{paracol}
---

<!--\pagecolor{bgcol}
\color{white}-->

\pagenumbering{gobble}
\begin{paracol}{2}

\huge Sanjay Sankaran\normalsize

Computer Science Student, Univ. of Washington Seattle

\switchcolumn
\begin{flushright}
\href{zyugyzarc@gmail.com}{zyugyzarc@gmail.com}\\
\href{https://ggithub.com/zyugyzarc}{github.com/zyugyzarc}\\
\href{http://linkedin.com/in/sanjay-sankaran}{linkedin.com/in/sanjay-sankaran}\\
\end{flushright}
\end{paracol}

##### 

\tikzmark{here}
\begin{tikzpicture}[overlay, remember picture, inner sep=0pt, outer sep=0pt]
  \fill [white] (current page.west |- {pic cs:here}) rectangle (current page.south east);
\end{tikzpicture}
\color{black}

Highly motivated software developer seeking a challenging role that leverages my expertise in machine learning, data science, and full-stack development to drive innovation and deliver cutting-edge solutions. AAS - Computer science student at Bellevue College.

## Skills
* C/C++ with dynamic memory management, and embedded programming for microcontrollers.
* Python - backend for web, api and desktop applications
* Data Science and Machine Learning with PyTorch.
* Java - Data Structures and Algorithms.
* Arduino - Worked with programmable microcontrollers and electronics to make various devices and autonomous robots.
* Linux - System Administration, Dependency management.
* Vulkan - graphics programming for shaders and compositing.
* Blender - 3d modeling and CAD, Shader Programming, Video Editing, Compositing.

## Projects
* [Ascii-Render](https://github.com/zyugyzarc/ascii-render)
  *  a 3D raster engine that runs in the terminal, displaying images through text made with C++, python and cython.
* [ReRoll](https://zyugyzarc.itch.io/reroll)
  * an isometric top-down maze-crawler game with randomly generated levels made with Blender (UPBGE) and python.
* [Dees](https://github.com/zyugyzarc/dees)
  * a simple dynamic typed compile-to-executable language built with C++ and python
* [D-chat](https://github.com/zyugyzarc/d-chat)
  *  a decentralized peer-to-peer chat application that uses WebRTC, built with python.
* Arduino and Robotics:
  *  Line Following Robots
  *  Bluetooth controlled Robots
  *  6-DOF Robotic Arm
* Machine learning - research:
   * Reinforcement Leaning for self-driving autonomous vehicles.
   * Diffusion based image and audio generation (StableDiffusion with LoRA and ControlNet, Riffusion)
   * Natural Language Processing and inference with Llama, Llama 2, Alpaca, Guanaco and others.

My other projects can be found on [GitHub](https://github.com/zyugyzarc) and [itch.io](https://zyugyzarc.itch.io)
