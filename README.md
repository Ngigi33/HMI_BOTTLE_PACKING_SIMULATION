# 🍾 HMI Simulation for Industrial Packaging Process
This project is a fun yet realistic simulation of an industrial packaging process, where bottles move along a conveyor, fill crates, and automatically replace full crates with empty ones. Designed for automation enthusiasts and learners alike, this project combines PLC logic with an interactive HMI visualization to simulate a packaging line you'd find in a modern factory.

Built using a Siemens S7-1200 PLC (CPU 1214), the simulation was brought to life using PLCSIM for virtual PLC programming and WinCC for creating a slick HMI interface.

## 🎮 Project Highlights
* Bottle Movement on a Conveyor:
  Animated bottles race across the HMI conveyor, heading toward their crate destiny.

* Crate Filling Fun:
  Watch crates fill up with bottles in real-time, with satisfying updates on the HMI display.

* Automated Crate Replacement:
  When a crate is full, the system works its magic—replacing it with a fresh crate, ready for more bottle adventures!

* Interactive HMI Controls:
  Take charge with start, stop, and new_box buttons on the HMI to keep things under control—or just have fun watching the automation in action!

## 🛠 Hardware and Tools
* HMI: Siemens KTP700 Basic HMI
* PLC: Siemens S7-1200 (CPU 1214)
* PLC Simulation: Siemens PLCSIM (for virtual PLC execution)
* HMI Simulation: WinCC Basic Runtime (to bring the HMI design to life)

## 🧩 Software & Programming Environment
* TIA Portal: The all-in-one workspace for PLC programming, HMI design, and simulation magic
* Communication Protocol: PROFINET for smooth operator-to-machine (and bottle-to-crate) communication
* 
![Screenshot 2024-12-10 072532](https://github.com/user-attachments/assets/83cd80d5-4428-4b31-a5bc-cd1476e98979)#

## Video Simulation
https://drive.google.com/file/d/10sODLVHH_6RRnM2SXUTCFAtSbP1zv7es/view?usp=drive_link

## 🚀 How the Magic Happens
1. The Simulation Kicks Off:
   Start the process via the HMI, and bottles start moving along the conveyor on the screen.
2. Conveyor in Action:
   Bottles glide toward their crate, which eagerly awaits its turn to be filled.
3. Crate-Filling Frenzy:
   Bottles stack up in the crate one by one, visible in real-time on the HMI.
4. Crate Replacement Dance:
   Once the crate is full, the PLC detects it and the conveyer stops until the new_box button is pressed to reset the system and place a new box. 
6. The system resets and on pressing start the dance continous.

## 💡 Why This Project is Awesome
* Educational Value:
  Learn about PLC programming, HMI design, and industrial automation principles in a hands-on, engaging way.
* Great for Testing:
  PLCSIM and WinCC allow you to simulate industrial processes without the need for physical hardware.
* Fun and Satisfying:
  Who doesn’t love watching bottles on a conveyor and crates being replaced like clockwork?

## 🚀 Future Ideas
* Add sensors to simulate bottle defects and crate errors for more complex automation.
* Create stats on the HMI, such as the number of bottles processed and crates filled.
* Integrate IoT for remote monitoring and control via a mobile app (because why not?).




