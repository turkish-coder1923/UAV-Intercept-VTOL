# UAV-Intercept-VTOL – SIPAHI-1

## Mission  
Autonomous VTOL UAV for controlled border intercept operations. Primary flow: Depart → Warn → Non-lethal Disable → Return. No strike payloads.

![SIPAHI-1 System Architecture](media/sipahi-1-system-architecture.png)

## System Goals  
- PX4-compatible VTOL platform  
- Non-lethal payload deployment (e.g., RF jammer, spotlight)  
- Environment-adaptive pathfinding  
- Recovery protocol after partial system failure  

## Repository Structure  
- `/docs`: Concept briefs, diagrams, and documentation  
- `/cad`: Frame design files (Fusion 360, STEP, STL)  
- `/code`: Mission logic, PX4 modules, control scripts  
- `/sim`: Simulation configs (Gazebo, PX4 SITL)  
- `/media`: Renders, system architecture visuals  

## Collaboration  
Looking for contributors in:  
- VTOL PID tuning / flight control  
- Jammer/light payload integration  
- Environmental response logic  
- Gazebo and PX4 SITL simulation setup  

This is an early-stage research project. Use the Discussions tab for technical offers or questions.

## Status  
- CAD: Initial frame concept  
- PX4 integration: Not started  
- Logic: Early planning  
- Simulation: Pending setup
