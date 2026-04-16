This GitHub is an overview of my 2026 sophomore project, a Digital Logic clock.

The clock functions with a combination of 7400 and 4000 series ICs, allowing it to take a signal produced via a crystal oscillator and turn it into an incremental clock.
This video demonstrates the circuit redesigned inside a simulation software named MultiSim.
https://youtu.be/zJlIENAns2U

https://github.com/user-attachments/assets/27e7ca1e-bdd5-4b90-bd54-3bdaebd04c41

(Disclaimer) - Due to the simulation software being slowed down by computational calculations, the time it takes to increment by 1 second is longer than in reality.


This project started with brainstorming; in my case, I decided to ask Reddit, where I was suggested this exact idea among others. 
As for what followed, the next course of action was to start the schematic process and design the rough outline of my circuit.
For this project, I went with a free online software named EasyEDA for both my schematic and PCB needs, as well as DigiKey for my parts distributor.

I looked at several reference images of similar creations to what I wanted to make, using some of them for reference for my project.

I took a great deal of time to decide on what components I wanted to use for my specific needs, thoughout the design project I had to tackle a multitude of issues. One of which is the issue of how I plan to power the circuit to begin with. When I started designing, I wanted to use a USB-C to power the board, but ended up having to go with a standard "barrel-jack" plug to supply my board's 5V input. Along with some simple protective measures to prevent voltage overruns and current spikes, as my components are quite sensitive to malfunction.
<img width="3201" height="3201" alt="Project Schematic" src="https://github.com/user-attachments/assets/94af95d1-a18f-449f-b8c1-5ff85c540c70" />
This is an image of my finished schematic, which then became my PCB.

<img width="1342" height="1553" alt="Project PCB" src="https://github.com/user-attachments/assets/4593c091-b985-4989-9001-d43345aa6f27" />
And this is the finished PCB board I sent for manufacturing. 

Having my own personalizations, of course.



And as I explained previously, I did my troubleshooting through simulation software, and here's a whole image of that circuit.
<img width="1852" height="1877" alt="Multisim Project File" src="https://github.com/user-attachments/assets/97a0003b-8954-47c9-a724-c77f5e0f8c5a" />

As this was my first large solo project along my electronics journey, there were many problems and lessons learned.
I struggled with mistakes and time management, and this experience has allowed me to improve in many areas almost overnight.

Additionally, this is a 3D representation of my finished PCB along with its added components.
<img width="638" height="728" alt="image" src="https://github.com/user-attachments/assets/8b40a5a6-a88a-4e7a-a85c-e01d94915bdd" />

It compares to the final assembly of the PCB:
<img width="3330" height="3948" alt="Project Photo" src="https://github.com/user-attachments/assets/64ca292c-04ff-4ca6-b6ad-0eb00fff5f19" />


