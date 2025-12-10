Rui Tao
CSYE 7270
2025-12-8
## Download Full UE5 Project
The complete project with Content folder can be downloaded from:
   Releases → TakehomeFinal.zip
Extract and double-click TakehomeFinal.uproject to run.

OR 

⬇ Click the button below to download the complete Unreal Engine 5.5 project  
(including Content and Config folders):

[![Download Full Project](https://img.shields.io/badge/Download-Full_Project-blue?style=for-the-badge&logo=unrealengine)](https://github.com/kazukismt/Take-Home-Final-Teaching-AI-in-Game-Development/releases/latest)

> After downloading, unzip and open `TakehomeFinal.uproject` to run.

### 🎬 Download Show-and-Tell Video
Available here in GitHub Releases ⬇  
https://github.com/kazukismt/Take-Home-Final-Teaching-AI-in-Game-Development/releases/tag/v1.0-video



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

         
