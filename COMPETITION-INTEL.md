🏁 AI Grand Prix — Competition Intel
Last Updated: March 15, 2026 | Full tech specs release: March 19, 2026

This document is the single source of truth for everything we know about the AI Grand Prix competition. Updated as new info drops.


📋 What We're Building
The Task: Develop an autonomous system that navigates a drone through a sequence of gates inside a virtual environment, as fast as possible.
Your code must handle three things:
ComponentWhat It MeansWhy It MattersGate RecognitionDetect and locate gates using a visual camera feedYou can't fly through what you can't seeDrone ControlCommand throttle, roll, pitch, and yawSpeed vs. accuracy — find the balancePath PlanningPlot an efficient route through all gates in orderThe fastest path wins
The goal is simple: complete all gates in the correct order, in the shortest time possible.
No manual control. No hardware advantages. Code quality alone determines performance.

📅 Competition Timeline
MilestoneWhenWhat HappensTech specs releaseMarch 19, 2026Full interface documentation, environment parametersVirtual Qualifier 1Opens May 2026Submit Python code to race in virtual simulatorVirtual Qualifier 2Opens June 2026Harder environment, more distractions, no visual aidsPhysical QualifierSeptember 2026Top teams go to Southern California for real dronesAI Grand Prix FinalsNovember 2026Championship race in Columbus, Ohio

🖥 What The Simulator Provides (Your Inputs)
DataDescriptionStarting positionWhere your drone beginsVelocityCurrent speed and directionOrientationWhich way the drone is facingForward-facing cameraVisual data stream (this is your "eyes")Drone controlsThrottle, Roll, Pitch, Yaw (this is your "hands")
Virtual Qualifier 1 vs. Virtual Qualifier 2
VQ1 (May)VQ2 (June)EnvironmentDesaturated, lower complexityMore complex, lighting distractionsGatesHighlighted, visual guidance aids ONVisual guidance aids OFFDifficultyEasier — high signal-to-noise ratioHarder — low signal-to-noise ratio

🚫 What The Simulator Does NOT Provide

❌ No depth information (no lidar, no depth camera — just the forward camera)
❌ No engine RPMs (you can't read motor speeds directly)
❌ No battery state of charge (but battery won't be a limiting factor)
❌ No manual steering — even for training. Your code drives everything.


💻 Technical Requirements
Software

Python 3.14.2 confirmed (other versions may work, but this is tested)
External libraries allowed — NumPy, OpenCV, TensorFlow, PyTorch, etc.
AI coding tools allowed — GitHub Copilot, Claude, etc.
Python API interface — your code talks to the simulator through a Python API

Hardware (Students Must Have)
The simulator runs via a Windows-based downloadable application. Minimum specs:
ComponentMinimum RequirementOSWindowsCPUIntel Core i5-10400F or AMD Ryzen 5 3600GPUNVIDIA RTX 2060 Super or AMD RX 9060 XTRAM16 GBStorage60 GB free space
⚠️ Chromebooks will NOT work. MacBooks will NOT work natively (would need Boot Camp or Parallels). Most budget laptops without a dedicated GPU will NOT work.
If your computer can run Fortnite or Minecraft with shaders smoothly, it can probably run this simulator.

📜 Rules & Fair Play

✅ Teams retain full ownership of their code and IP
✅ No entry fee
✅ AI coding tools (Copilot, Claude) are allowed
✅ External libraries and frameworks are allowed
✅ Out-of-the-box thinking is explicitly encouraged
❌ No human interaction during runs
❌ No rewriting or altering game files
❌ No color changes, screen tricks, or disabling collision detection
❌ No manual steering, even for training


🏆 What's At Stake

$500,000 prize pool — top 10 teams in Ohio guaranteed at least $5,000
Job at Anduril — winning team member can bypass standard recruiting
Internship screening — top university performers screened at physical qualifier
Worldwide media coverage


🔗 Links

theaigrandprix.com — Registration & updates
Official Rules
Anduril Industries
Drone Champions League


📌 What We're Waiting For (March 19)
The full tech specs release on March 19 will include:

Finalized interface description
Environment parameters
Detailed simulator documentation
This doc will be updated immediately when they drop.


Peninsula AIGP — Peninsula Baptist Church, Mooresville, NC
"Whatever you do, work at it with all your heart, as working for the Lord." — Colossians 3:23
