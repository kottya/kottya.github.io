# Innovator Journal 03

## 3D scanner project


### Question: 

How can we create a 3D scanner?

-----------------------------------------------------------------------------------
### Materials:

- breadboard
- Arduino
- wires
- sensor
- computer (Macbook Air)
- adapter
- stepper mortor
- Arduino sheild
- screw & nut
- laser cutter & board
  
-------------------------------------------------------------------------------------

Please check [Innovator Journal 01](projects/innovatorJournal) and [Innovator Journal 02](projects/innovatorJournal02) for my journey and my process before class 6.

------------------
### Process:

1. Adding microstepping

We added three jumper wires to connect three pair of pins based on the following chart on [CNC sheild guide](https://www.makerstore.com.au/wp-content/uploads/filebase/publications/CNC-Shield-Guide-v1.0.pdf)
<img width="500" alt="Screenshot 2025-12-18 at 17 12 40" src="https://github.com/user-attachments/assets/470c0af9-a2ca-41c5-bb7a-0119fe0b86e9" />

-----------------------

2. Coding in Python to turn sensor detected results into coordinates and plot them. (Class 6)
<img width="500" alt="Screenshot 2025-12-18 at 17 01 12" src="https://github.com/user-attachments/assets/e51c4907-2447-42db-a906-2a51f58b31fb" />

<img width="500" alt="Screenshot 2025-12-18 at 17 01 32" src="https://github.com/user-attachments/assets/ab70ceab-22a2-4271-8514-00b960f699ae" />

<img width="500" alt="Screenshot 2025-12-18 at 17 01 32" src="https://github.com/user-attachments/assets/bd08e9a4-1e96-4c69-a0e5-4274c809828c" />

---------------------------------------------------------------------

3. Laser cutting parts to assemble the two stepper motors together

   
I was is charge of refining the designs (mainly measurements) made by my classmates.
<img width="500" alt="Screenshot 2025-12-18 at 14 39 58" src="https://github.com/user-attachments/assets/ee91e000-b1bc-40d1-bd97-4dda4f980d76" />
<img width="500" alt="Screenshot 2025-12-18 at 14 42 08" src="https://github.com/user-attachments/assets/46b5d96e-6c44-4e46-8d19-d3e154121404" />
<img width="500" alt="Screenshot 2025-12-18 at 14 42 29" src="https://github.com/user-attachments/assets/b2cca9b3-b869-4e17-a767-1d466791b2cd" />
<img width="500" alt="Screenshot 2025-12-18 at 14 44 00" src="https://github.com/user-attachments/assets/4bd9614e-3e09-4d91-ac2c-9cdc101b9b80" />
<img width="500" alt="Screenshot 2025-12-18 at 14 44 35" src="https://github.com/user-attachments/assets/6774cf57-730b-41e2-9d70-e36b527ff66f" />

<img width="800" alt="Screenshot 2025-12-18 at 17 22 32" src="https://github.com/user-attachments/assets/7a913a65-92cc-40ff-a95c-ed7d9e74e59b" />


------------------
4. Testing


We assempled the pieces together and ran the code.
<img width="500" alt="Screenshot 2025-12-18 at 17 22 20" src="https://github.com/user-attachments/assets/75b6c767-e9a3-4628-a80e-4e6542dd2dee" />


 Here is the graph we got;
<img width="500" alt="Screenshot 2025-12-18 at 17 16 31" src="https://github.com/user-attachments/assets/72265598-eaa4-4796-a8b9-5a599c96bcbe" />

------------------------

### Progress & Problems:

My partner and I didn't have a lot of knowledge required for these process, so we recieved a lot of help from Mr. Raus and classmates initiating new steps that were unfamiliar to us.

The first microstepping procedures went smoothly, and solved the vibration problems of the stepper motor. We got a lot of help during the coding process in Python, since it was a new language for both of us. During this process, we had a lot of small bugs, which we solved by repeating trial and error one by one. Since our team was mainly focused on coding, we utilized the model of parts provided by other teams in the class when assembling. However, we encountered small problems such as missing some screw sizes and small design errors. There were some parts that were dimentioned wrong and lead to contact of screws and other parts, so I fixed the dimension and laser cutted it again. We are still in the process of trial and error for accurate 2D graphing of the coordinates measured with the sensor. When we come back from break, we will have to refine the codes for the 2D mapping we have right now, then turn them into 3D scan. I also want to try adding more extentions, such as adding a status LED.

-------------------------

### What I learned from this process:

- Prototyping using different devices (3D printer prototypes vs. laser cutting prototypes)
- How to set dimensions in design when it is based on an existing object (sensor, stepper motor etc)
- Python coding
- Process of debugging (in general NOT how to debug)
- How to set microstepping
- Diffrent screws & nuts
- How to get coordinates using angles and triganometry
- Graphing coordinates

---------------------------------

### Emotional Journey:

This process felt overwhelming but also motivating and meaningful to me. I was flooded with new information and concepts every classes, which I tried my best to keep up. Each concept is very broad and there were a lot to learn about each field. For example, the process with Python and graphing coordinates was completely new to me, and I sometimes felt lost. However, this process definetely help me learn a LOT about coding, hardwares, and prototyping process in general, which was something I have never done before. Now that I went through this process, it makes me feel more comfortable around different tech devices, especially laser cutters. It was my first time helping the design and operating the cutting with laser cutters, and I realized how fun it was to use it. I will definetely learn and do more with it, and I look forward to refining our 2D scanner into a 3D scanner with extensions when we come back from break!!!

----------------------------------

### Sources:

(https://www.makerstore.com.au/wp-content/uploads/filebase/publications/CNC-Shield-Guide-v1.0.pdf)[https://www.makerstore.com.au/wp-content/uploads/filebase/publications/CNC-Shield-Guide-v1.0.pdf]

Website of my partner, Kaylee Zhu:

[https://jialin-kaylee.github.io/3D_Printer_Journal](https://jialin-kaylee.github.io/3D_Printer_Journal)
