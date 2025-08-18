# Note
Migrating site to React. Check it out: [https://alanbao.org](https://alanbao.org)

# About   [![linkedin](img/linkedin.png)](http://linkedin.com/in/alan-bao/)  <a href="mailto:alanb@berkeley.edu">![email](img/email.png)</a>
Hello! I'm Alan, a student at UC Berkeley studying EECS and Math. I've lived most of my life in San Diego, but have also lived in many other states such as Virginia and Tennessee. My MBTI is *ENFJ-A*.

My technical interests include software engineering, machine learning, computer vision, cybersecurity and hardware. I'm especially passionate about applying computer science, math and statistics to solve various industry and everyday problems. Most recently, in Summer 2025, I interned at Capital One as a Software Engineer, where I helped design the foundations for a new graph-based decisioning system for auto loans.

Outside of computer science, I enjoy a variety of hobbies, such as running, dancing, cooking, fashion, music and puzzle games (i.e. NYT Mini). I love going on adventures, exploring the unknown, and challenging myself. Recently, I decided to start learning German and Cantonese. Above all else, I love talking to and meeting people!

So if you have any questions, or would like to chat, please contact me by clicking on the icons above!


# Projects (Updated January 2025)
- [Computer Vision Projects](#cs-180-intro-to-computer-vision-projects)
- [Coin Dungeon](#coin-dungeon)
- [TaxTools](#taxtools)
- [Terminal Snake](#terminal-snake)
- [SIXT33N Robot](#sixt33n-voice-controlled-robot)
- [CS61CPU](#cs61cpu)
- [UCSD Radiology Research](#ucsd-radiology-research)
- [Arin Igor, Your AI Therapist (Work in Progress)](#arin-igor-ai-therapist-prototype)
- [UC Berkeley Assist.org (Work in Progress)](#uc-berkeley-assist)

---

## *Computer Vision Projects*
![mancampfire](/img/mancampfire.jpg)
**Project Portfolio Link:** [https://abao27.github.io](https://abao27.github.io)

**Skills**: Python, Pytorch, Numpy, Computer Vision

In this class, I explored the various derivations and applications of computer vision, including image generation and manipulation. The image above shows a visual anagram; an image I generated to appear as people around a campfire in one orientation, and an old man in another. More specifics about my process and deliverables are attached in the link above.

___

## *Coin Dungeon*
![coindungeon](/vid/coindungeon.mp4)

**Skills**: Java, Graphic Design

"Coin Dungeon" is a mini-game I coded using Java and the edu.princeton.cs.algs4 package. The goal of the game is simple: to collect all of the coins in the randomly-generated labyrinth. Some key features include:
- WASD navigation
- Toggle light on/off
- Save game state
- Replay

In the demo above, I enter a seed and start the game, which generates a random world. I then toggle dark and light mode with the "I" and "O" keys, and proceed to collect all the coins. After all the coins are collected, a win screen pops up.

___

## *TaxTools*
![PCSTaxTools](/vid/pcstaxtools.mp4)

**Skills**: JavaScript, Data Analysis, Research

TaxTools is a static website designed in a small project team in my club, Political CS @ Berkeley. This website visualizes tax data based on user settings and simulates one's savings and retirement. I mainly had a backend role in this project, where I researched and analyzed US Government financial data to write functions that calculated one's taxes and finances.

In this demo, I play around with different settings (Fiscal Year, Marital Status, Tax Credit) to see how much I would get taxed with an annual income of $50,000. I then visualized the breakdown of my tax spending with the pie chart. Finally, I used the savings and investment simulator to simulate my savings by 2065.

___

## *Terminal Snake*
![Terminal Snake](/vid/snake.mp4)

**Skills**: C

This version of the classic snake is simple and playable in your terminal! For this project, I coded the functions and classes that defined the snake and its movements. I also worked on memory management, which was necessary for efficient updating, saving and loading game states. However, instead of using graphics, unicode characters were used to visualize the game. The notation of characters are defined below:
- *WASD* - The head of the snake corresponding with the direction its facing.
- *wasd* - The tail of the snake corresponding with the direction its facing.
- *^\<v\>* - The body of the snake corresponding with the direction its facing.
- *\** - The apple the snake wants to eat.
- *#* - The borders/walls of the world.

In the short snippet of the game demo above, I use the WASD keys to navigate the snake in the world map and eat the apples. When my snake's head crashed into its body, it dies and the game ends.

___

## *SIXT33N Voice Controlled Robot*
![SIXT33N](/img/SIXT33N.png)

**Skills**: Arduino, Circuit Design and Analysis, Numpy, Linear Algebra

SIXT33N is a voice-controlled car built with breadboarding components and an Ardunio Leonardo. The robot listens to voice commands and drives on a pre-determined path based on the given command. For example, saying "Go" will cause the robot to drive forward.

To read more about how we built SIXT33N, click [here](https://drive.google.com/file/d/1qSTKLlG3OlZxq7_wYcXO00HrnyB-NUdB/view?usp=sharing).

___

## *CS61CPU*
**Skills**: CPU, Assembly (RISC-V), Logic Circuits

In this project for my computer architecture class (CS61C), I built a simple 2-stage pipelined CPU that runs RISC-V instructions in Logisim. This challenged and tested my understanding of the RISC-V Datapath and logic circuits.

Due to course policy, there is no demo, but a list of runnable instructions are enumerated below. Note that all instructions are signed unless specified otherwise.

|Name: ```Instruction```|||||||||
|---|---|---|---|---|---|---|---|---|
|Add: ```add```|Multiply: ```mul```|Subtract: ```sub```|Shift Left Logical: ```sll```|Multiply Upper Half: ```mulh```|Multiply Upper Half (Unsigned): ```mulhu```|Set Less Than: ```slt```|Bitwise XOR: ```xor```|Shift Right Logical: ```srl```|
|Shift Right Arithmetic: ```sra```|Bitwise OR: ```or```|Bitwise AND: ```and```|Load Byte: ```lb```|Load Half-word: ```lh```|Load Word: ```lw```|Add Immediate: ```addi```|Shift Logical Left Immediate: ```slli```|Set Less Than Immediate: ```slti```|
|Bitwise XOR Immediate: ```xori```|Shift Right Logical Immediate: ```srli```|Shift Right Arithmetic Immediate: ```srai```|Bitwise OR Immediate: ```ori```|Bitwise AND Immediate: ```andi```|Store Byte: ```sb```|Store Half-word: ```sh```|Store Word: ```sw```|Branch if Equal: ```beq```|
|Branch if Not Equal: ```bne```|Branch if Less Than: ```blt```|Branch if Greater or Equal: ```bge```|Branch if Less Than (Unsigned): ```bltu```|Branch if Greater or Equal (Unsigned): ```bgeu```|Add Upper Immediate to PC: ```auipc```|Load Upper Immediate: ```lui```|Jump and Link: ```jal```|Jump and Link Register: ```jalr```|

___

## *UCSD Radiology Research*
**Skills**: Statistics, Data Analysis and Visualization, Matlab

As a research intern for UCSD Radiology, I statistically analyzed knee data and visualized it using a pre-written Matlab program. Read more about the research in the links below.

[Link to abstract](https://drive.google.com/file/d/14HTdGWiZePESkoU4TQ5-qmgxxBq_0krJ/view?usp=sharing)  \|  [ISMRM Pitch (#0532)](https://www.ismrm.org/22/program-files/PP-17.htm)


---

## *Arin Igor AI Therapist Prototype*
![Arin Igor Code Demo](/vid/arin_igor.mp4)    ![Arin Igor Website](/img/arin_igor.png)

**Skills**: Python, Machine Learning, Web Design, UI/UX, Research

Birthed at a hackathon, Arin Igor is a therapist with a twist: it's an AI. Currently in its infancy, Arin Igor can only detect emotions in faces and language, but is unable to give therapy. Our team is working on training a chat-bot, similar to ChatGPT, so that the user can simulate chatting with an actual therapist. Credits to Hume AI API for making emotion detection possible.

In the video above, a link to an image of a person's face is input to our code, which outputs the top 3 emotions detected. The photo below the video shows a prototype of the Arin Igor Therapist website, which is intended to be freely accessed on the web.

___

## *UC Berkeley Assist*

**Skills**: Python, Django, Webscraping, Research

"UC Berkeley Assist" is a passion project started by my friends and I to tailor Assist.org for UC Berkeley students to make course research easier. Assist.org is a website that outlines courses transferable from California Community Colleges (CCC) to Californian colleges including UC Berkeley. Currently, the team is in the process of building a web scraper to automate data collection.
