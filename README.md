<h3>🧠 AI Combat Simulation – Unreal Engine 5</h3>

An experimental third-person action game built in Unreal Engine 5, focused on implementing adaptive AI agents that use perception-based decision-making, navigation meshes, and dynamic combat interactions.
This project demonstrates both gameplay design and research potential in autonomous game AI, combining technical AI systems with smooth player interaction and feedback.

🎮 Overview

In this game, the player faces off against multiple AI-controlled bots powered by Unreal Engine’s:

Navigation Mesh (NavMesh) for intelligent movement and obstacle avoidance.

AI Perception System for realistic sight and hearing detection.

Behavioral logic for attacking, chasing, and reacting to player actions.

Damage and death mechanics, including ragdoll physics and animation-driven responses.

The goal is to simulate believable combat AI that can adapt dynamically to player behavior and environmental changes.

⚙️ Features
🧭 AI Systems

Dynamic Navigation:
Bots use NavMesh to move through the world, dynamically avoiding obstacles.

Perception-Driven Awareness:
AI uses Unreal’s Perception system (Sight & Hearing) to detect players and react intelligently.

Behavioral Control:
Modular decision logic based on sensory inputs and internal states (alerted, chasing, attacking, dead).

💥 Combat & Gameplay

Damage System:
Event-driven damage handling with real-time health tracking.

Death Handling:
Ragdoll physics for natural character collapse and optional delayed destruction.

Player HUD:
Real-time display of player and AI stats using a custom Widget Blueprint.

Game Mode Integration:
Centralized game logic handled by BP_ThirdPersonGameMode, managing score, bot states, and overall flow.

🧩 Technical Highlights

Modular Blueprint-based AI design.

Integration of AIController, Blackboard, and Behavior Tree logic.

Physics-based death effects (ragdoll).

Configurable perception radius and team-based detection tuning.
