Rui Tao
CSYE 7270
2025-12-8
Download Full UE5 Project
The complete project with Content folder can be downloaded from:
   Releases → TakehomeFinal.zip
Extract and double-click TakehomeFinal.uproject to run.

# Take-Home-Final-Teaching-AI-in-Game-Development (Unreal Engine 5, Blueprint)

This repository contains a teaching-oriented AI system implemented in Unreal Engine 5.5 using Behavior Trees and Blueprints.  

Learning Objectives
After completing this tutorial, students will be able to:

- Understand Behavior Tree and Blackboard fundamentals in UE5
- Set up AI Patrol using Blueprint


AI Behavior Overview
This project features a single NPC character (**BP_NPC**) that:
Patrols within the navigable area


Behavior Tree Structure
Root
└─ Selector
     └─ Sequence (Patrol)
         ├─ BTTask_Patrol   # Find random patrol location
         └─ MoveTo → PatrolLocation

         
