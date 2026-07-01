***Sahasra’s Audio Hackpad***
-------------------------------------
<img width="900" height="1600" alt="image" src="https://github.com/user-attachments/assets/e672c5e5-e0d2-4f68-8f67-0f8c21cab1e1" />

<img width="541" height="408" alt="image" src="https://github.com/user-attachments/assets/affbfab0-f9db-4b2f-b932-21dc96d04e55" />

**Inspiration**
--
One of the biggest problems I always face when audio editing is having the shortcuts and keys that I used far part. This meant that even for repeatative actions, I had to many times take my hand off the mouse and click delete, or move my hand across the whole keyboard. This slowed down my editing process extrmely, and since the keys are so far apart, I often click the wrong buttons (destroying whatever file/rpoject I was wroking on). This hackpad is designed to solve that problem, as I specifically designed it for audio editing, allowing me to quickly cut audio and adjust noise levels (all referencing Adobe Audition). Moreover, I can do all this without risking clicking the wrong button or moving my hand away from my mouse, solving my problem with time constraints and incorrect commands.  

**Challenges**
--
This was my very first time doing anything like this project. That means first-time using PCBs, electrical schematics, GitHub, the whole gist.  It took a lot of googling and asking others for help, but I finally made it after a couple of weeks.  I'm really proud of this finished product and super happy that it'll solve a lot of my audio editing problems now. The most trouble I faced was with the resources, as many times they were extremely vauge, so I had to figure out how to work everything out from the beginning (making me take longer than the average person). 

**Specifications and BOM**
--
**Bill of Materials**
|Material| Count|
| -------- | -------- | 
| Cherry MX Switches | 5 | 
| EC11 Rotary Encoder | 1 | 
| XIAO RP2040 | 1 | 
| Blank DSA Keycaps| 5 | 
| M3x16 Bolt | 4 | 
| M3 Heatset| 4| 
| Custom PCB | 1 | \


\
Others: - KMK Firmware - Top Case.stl  - Bottom Case.stl - Custom PCB
\
*All of these parts I already own, so nothing needed for purchase*

**Schematic**
--
<img width="401" height="303" alt="image" src="https://github.com/user-attachments/assets/ca8a6dac-b0c8-4e83-a587-792cd05e115e" />

**PCB**
--
<img width="386" height="536" alt="image" src="https://github.com/user-attachments/assets/0adc1efe-3aa2-4ab8-a0fa-b5cb579689ad" />


**Case**
--
<img width="194" height="139" alt="image" src="https://github.com/user-attachments/assets/7bf98c0c-704b-4e42-ae30-3be25d26cdb0" />


**Firmware**
--
Firmware was done using the template provided by blueprint using kmk. The changes made to the code included assigning each key to the board and adding in what each key did, heavily refrencing the shortcuts given in the library. 

**Resources Used**
--
Took a lot of inspiration from this guide from Blueprint! However, it was quite vague in terms of the additional features I wanted to add, so I used a lot of youtube videos as well. 
\
Blueprint Guide: https://blueprint.hackclub.com/hackpad/index.md
\
Youtube  KiCAD Starter guide: https://www.youtube.com/watch?v=d9_-lQq8ShE 
\
PCB Design tutorials: https://www.youtube.com/watch?v=zeH3WbMWvdg
\
People from slack + a LOT more Phil's Lab videos
