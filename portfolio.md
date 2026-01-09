---
layout: page
title: Portfolio
permalink: /portfolio/
---

<link rel="stylesheet" href="{{ '/assets/css/style.css' | relative_url }}">

{% include project-card.html
  title="TurtleShell"
  role="Project Lead"
  image="/turtleshell_main.png"
  alt="TurtleShell main interface"
  description="
  <p>TurtleShell is a locally hosted encryption manager built to securely store documents, passwords, and other sensitive data without relying on cloud services. Developed primarily in Java, the project uses Java’s cryptography libraries to implement industry standard encryption while prioritizing secure defaults and clear separation of concerns. The user interface is built with JavaFX, with a strong focus on clarity and usability, ensuring that powerful security features remain accessible and easy to use.</p>

  "
  links='
    <a href="https://git.cs.usask.ca/jsd408/cmpt370/-/tree/226c0e1db831835ab5ae241b0c21bb71c985c926/">Repository</a>
  '
%}

{% include project-card.html
  title="Nerobot - Discord Music Bot"
  role="Sole Developer"
  image="nerobot.png"
  description="
  <p>Nerobot is a Discord music bot written in Python that connects to voice channels and plays music on command. It supports playlist generation and basic playback controls, designed for ease of setup and use in small to medium Discord communities. The bot is modular and script-driven, allowing for custom extension of commands and features. Python’s standard libraries and Discord APIs are used to manage connections, track queues, and respond to user interaction. Nerobot provides a lightweight, self-hostable solution for adding music playback to a Discord server.</p>
  "
  links='
    <a href="https://github.com/JorenDryden/nerobot">Repository</a>
  '
%}

{% include project-card.html
  title="Procedural Generation and A* Pathing Demo"
  role="Sole Developer"
  image="demo1.png"
  description="
  <p>This repository contains a Godot Engine game developed for a CMPT 306 assignment, with a primary focus on procedural generation and A* pathfinding. The project implements algorithmic level creation to dynamically generate playable spaces, paired with A* search to enable efficient navigation and movement within those environments. The code emphasizes clear separation between generation logic, pathfinding systems, and game entities, demonstrating practical application of core game AI and procedural content techniques in a small scale game context.</p>
  "
  links='
    <a href="https://github.com/JorenDryden/cmpt306a3">Repository</a>
  '
%}

{% include project-card.html
  title="Harvest 306"
  role="Project Lead"
  image="DEMO2.png"
  description="
  <p>Harvest306 is a Godot project developed for CMPT 306 that implements procedural content generation and core resource management mechanics. The game focuses on algorithmically creating dynamic environments and simulating harvesting systems, allowing entities to interact with and gather resources within generated terrain. Procedural generation techniques produce varied play spaces, while game logic handles movement, collection, and basic environmental responses. The repository demonstrates practical use of Godot’s scene system, GDScript, and generation algorithms to build a modular, scalable prototype that highlights both procedural techniques and resource-driven gameplay.</p>
  "
  links='
    <a href="https://github.com/JorenDryden/harvest306">Repository</a>
    <a href="https://jorend.itch.io/cmpt306-phase-2">Itch.io</a>
    '
%}

