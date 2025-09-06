# PID-Controller-LTSPICE-simulation
Hardware Implementation of PID controller. Designed and Implemented an analog circuit of PID controller and Mass-Spring-Damper using LM324 opamps.

---


 ## ⚙️ Circuit Overview: **PID Controller:** LM324 op-amps set up as integrator, differentiator, and summer circuits were used in its implementation.  
 In order to simulate second-order dynamics, the Mass-Spring-Damper Model was created as an electrical analog equivalent using RLC/op-amp circuits.  
 The Closed-Loop System:  
   To examine stability and transient response, the Mass-Spring-Damper system receives the output from the PID controller.

 ---

 ## 🚀  How to Apply
 1. To view and operate the analog PID + MSD system, open the LTspice files in `simulations/`.
 2. Look for real implementation diagrams and pictures in `hardware/`.
 3. For a thorough explanation and theoretical background, see `docs/`.

 ---

 Results: Step response comparison of **P**, **PI**, and **PID** configurations.  
 Waveforms from a hardware oscilloscope verify the controller's functionality.  

 For instance:  

 ![Step Response](images/step_response.png)

 ---

 ## 📖 Citations: Ogata, K. *Modern Control Engineering*.  
 Texas Instruments' LM324 Datasheet.  

 ---

 ## 👨‍💻 Author **Rohit Dhamale**, IIT Bhilai, B.Tech in Electrical Engineering
