**Portable Pi Power System**

<img width="4032" height="3024" alt="IMG_9776" src="https://github.com/user-attachments/assets/634f2c98-f8f8-48a3-8328-f45f9174030a" />
<img width="5712" height="4284" alt="IMG_9779" src="https://github.com/user-attachments/assets/835069cd-f5b5-448f-b1e1-2afe09204661" />

============================================================================

I wanted to have a way to power my Raspberry Pi 5 portably so that it could be used almost anywhere to remotely access my computer sitting at home. Through design ups and downs, I settled on an external power source to do the job. It includes a Battery Management System (BMS) to provide cell protection and balancing. It also has a USB-C Power Delivery module to allow charging using USB-C. My system lastly includes a UBEC to convert the battery voltage to a regulated 5V output. It has a capacity of 38.5Wh, which is comparable to a small laptop or the Steam Deck. It features two switches to fully isolate the battery, ensuring theres no unwanted power draw during storage. I also designed a custom enclosure using Solidworks to house and organize all components. 

------------------------------------------------------------------------
Features

• USB-C PD charging
• 2S LiPo battery
• BMS
• 5V UBEC
• 3D printed enclosure

------------------------------------------------------------------------

Project Photos 

<img width="4032" height="3024" alt="IMG_9780" src="https://github.com/user-attachments/assets/4bd46ba0-ecd3-4d13-be19-5813fc7cb6db" />
<img width="4032" height="3024" alt="IMG_9782" src="https://github.com/user-attachments/assets/f396651d-efbb-4530-b815-ed916e4b4aa9" />
<img width="5712" height="4284" alt="IMG_9787" src="https://github.com/user-attachments/assets/7eac8f15-5433-48bc-9084-1ca61680e59c" />
<img width="5712" height="4284" alt="IMG_9786" src="https://github.com/user-attachments/assets/f3533acc-ee50-456f-94c6-b7a79eb70f52" />
<img width="4032" height="3024" alt="IMG_9792" src="https://github.com/user-attachments/assets/d4166fbb-7899-49e4-bf16-b8a8e3775159" />

------------------------------------------------------------------------

Wiring Diagram

<img width="3024" height="4032" alt="unnamed (2)" src="https://github.com/user-attachments/assets/b4d38c5b-1501-4150-82db-2a1562456b95" />

------------------------------------------------------------------------

Challenges

• Selecting a suitable battery
• Understanding and wiring 2S Battery Management System 
• Effectively soldering without shorting other electronics
• Debugging unexpected battery discharge
• Redesigning the power architecture after identifying current draw issue 
• Designing and reiterations of custom enclosure using Solidworks and 3D printer

<img width="5712" height="4284" alt="IMG_9790" src="https://github.com/user-attachments/assets/2a33a9a0-6862-4d06-bf4d-2d5eea14edf7" />

------------------------------------------------------------------------

Lessons Learned

• Lithium battery safety
• Hardware debugging
• Multimeter based troubleshooting
• Soldering and wiring
• CAD design
• 3D printing functional enclosures

------------------------------------------------------------------------

Future Improvements 

• Custom PCB integrating all power electronics
• Battery fuel gauge
• Internal fuse
• Enclosure for Raspberry Pi that works with power delivery




