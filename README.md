# Awesome-Unreal-Engine
An awesome list for Unreal Engine, especially for the built-in plugins.

## Legends 🏷️

### License
* ❤️ : Open Source
* 🆓 : Free
* 💸 : Partially Free
* 💰 : Paid

### Ranks of Usefulness⭐
* 🥇 : 1st Place  
* 🥈 : 2nd Place
* 🥉 : 3rd Place
* ❓ : Unknown Place (Not tested)

### Tags
* 🎮 : Game
* 🎥 : Cinema, Virtual Production (Film / Video & Live Events)
* 🏛️ : Architecture
* ⚙️ : Automotive Production Design & Manufacturing
* ✈️ : Simulation
* Others: 💻, 🎲, 💎, 🔥

## Table of Contents
* [Gameplay](#gameplay) 
* [Level Design](#level-design) 
* [Art](#art) 
* [UI](#ui)
* [Audio](#audio) 
* [Extras](#extras) 

## Gameplay
Framework & Gameplay Plugins

* **Gameplay Ability System Plugin** (🥇 🎮)
  * Attribute, Ability, Effect, Cue (Vfx / Sfx), etc.
  * [Unreal Engine Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/gameplay-ability-system-for-unreal-engine) (🆓 🥇)
  * [GASDocumentation by tranek](https://github.com/tranek/GASDocumentation) (❤️ 🆓 🥇)
  * [Lyra](https://www.fab.com/listings/93faede1-4434-47c0-85f1-bf27c0820ad0), [Valley of the Ancient](https://www.fab.com/listings/0c19880e-21bd-42ba-8287-1caccc3951b1), [Action RPG (Old)](https://www.fab.com/listings/ef04a196-03c1-4204-998a-c7d5264fade7) Sample Projects (🆓 🥇)
  * Multiplayer: [Gameplay Ability System in Multiplayer Games](https://www.youtube.com/watch?v=WyyUPqdZQfU), [Using the Gameplay Ability System](https://www.youtube.com/watch?v=_713CSOWkTU), [Gameplay Abilities Meet Behavior Trees](https://www.youtube.com/watch?v=1Dm1G6fUuFs), [A Guided Tour of Gameplay Abilities](https://www.youtube.com/watch?v=YvXvWa6vbAA)
* **Targeting System Plugin**
  * Targeting (Actor Selection / Tracing & Filtering) by Data-driven targeting requests (Data Assets)
  * [Unreal Engine Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/gameplay-targeting-system-in-unreal-engine) (🆓 🥇)
* **Game Features Plugin**
  * Create standalone feature plugins
  * [Unreal Engine Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/game-features-and-modular-gameplay-in-unreal-engine) (🆓 🥇)
* **State Tree**
  * General-purpose hierarchical state machine
  * [Unreal Engine Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/state-tree-in-unreal-engine) (🆓 🥇)
* **Smart Objects**
  * Interaction (Reservation) system for Player and AI interactable objects
  * [Unreal Engine Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/smart-objects-in-unreal-engine) (🆓 🥇)
* **Mass AI, Instanced Actors & Zone Graph**
  * Data-oriented design (Similar to Entity Component System (ECS))
  * [Unreal Engine Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/mass-entity-in-unreal-engine) (🆓 🥇) 
* **Instanced Struct (Struct Utils)**
  * Editor compatible Struct Template (like Instanced UObject)Instanced Struct Framework
  * [Unreal Engine Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/InstancedStruct) isn't available yet!
  * [Generic Itemization by Matthew Boatswain](https://github.com/mattyman174/GenericItemization) (❤️ 🆓 🥇)
  * Extra: [Working with Data (Unreal Engine Learning)](https://dev.epicgames.com/community/learning/tutorials/Gp9j/working-with-data-in-unreal-engine-data-tables-data-assets-uproperty-specifiers-and-more#howtomakeinstanceobjects) (🆓 🥇)
* **Gameplay Cameras**
  * Define your complex camera behaviors
  * [Unreal Engine Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/gameplay-camera-system) (🆓 ❓)
* **Mutable**
  * Create your Modular Character in Runtime
  * [Unreal Engine Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/mutable-overview-in-unreal-engine) (🆓 ❓)
  * [Mutable-Documentation by anticto](https://github.com/anticto/Mutable-Documentation/wiki) (🆓 ❓)

**Future:**
  * *Online Services (aka Online Subsystem v2)* - [Lyra Sample](https://www.fab.com/listings/93faede1-4434-47c0-85f1-bf27c0820ad0)
  * *Mover 2.0 Plugin* - [Unreal Engine Youtube](https://www.youtube.com/watch?v=P4IKS5k47Wg)
  * *Anim Next (Unreal Animation Framework (UAF))*
  * *Contextual Animation Plugin* - [Blog by Alvaro Jover-Alvarez](https://vorixo.github.io/devtricks/contextual-anim/)
  * *Common Conversation Plugin* - [Common Conversation Youtube Tutorial by Il Canale Che Non C'è](https://www.youtube.com/watch?v=l-k3ymFdA10)


Also check out these:
Niagara / Niagara Fluids, Enhanced Input, Control Rig & Modular Control Rig, Environment Query System (EQS), Take Recorder, Editor Utilities, Data Table/Asset/Registry and many more...

## Level Design
* **Procedural Content Generation (PCG)**
  * Create your Level with Procedural Generation Tool
  * [Unreal Engine Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/procedural-content-generation--framework-in-unreal-engine) & [Electric Dream Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/procedural-content-generation-in-electric-dreams) (🆓 🥇)
  * [Unreal Engine Tutorial](https://www.youtube.com/watch?v=j3ke6MmcaeY) & [Indoor Environment](https://www.youtube.com/watch?v=FW5U_IsV3Pw) 
* **Geometry Scripting**
  * Create your Geometry / Meshes / Models by Coding (i.e. Blueprint)
  * [Unreal Engine Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/modeling-and-geometry-scripting-in-unreal-engine) (🆓 🥇)
* **Scriptable Tools**
  * Create and Customize your Level Design Tools
  * [Unreal Engine Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/scriptable-tools-system-in-unreal-engine) (🆓 🥇)
* **Water**
  * Create Water Elements (River, etc.) & Buoyancy
  * [Unreal Engine Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/water-system-in-unreal-engine) (🆓 🥇)
 
Also check out these:
Actor Palette, Lightweight Instances Editor

## Art
* **MetaHuman** (🥉 🎮)
  * Create your Digital Human Character
  * [Unreal Engine Documentation](https://dev.epicgames.com/documentation/en-us/metahuman/metahuman-documentation) (🆓 🥇)
* **Motion Design** (🥉 🎮)
  * Create your motion graphics / animations
  * [Unreal Engine Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/motion-design-in-unreal-engine) (🆓 🥇)
* **Texture Graph** (🥉 🎮)
  * Create Texture like Substance Designer
  * [Unreal Engine Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/getting-started-with-texture-graph-in-unreal-engine) (🆓 🥇)
  * [Unreal Engine Learning](https://dev.epicgames.com/community/learning/tutorials/z0VJ/unreal-engine-getting-started-with-texture-graph) (🆓 🥉)


## UI
* **Common UI** (🥉 🎮)
  * Create Game / Platform Independent UI
  * [Unreal Engine Documentation](https://dev.epicgames.com/documentation/en-us/metahuman/metahuman-documentation) (🆓 🥇)
* **UMG Viewmodel**
  * [Unreal Engine Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/umg-viewmodel-for-unreal-engine) (🆓 🥇)
* **Electra Player**

## Audio
* **Audio Modulation Plugin**

## Extras
Elegant Tutorials, Communities & Documentations
* **[Unreal Engine](https://www.youtube.com/watch?v=VMZftEVDuCE) [Game Framework](https://www.youtube.com/watch?v=IaU2Hue-ApI), [Replication](https://www.youtube.com/watch?v=JOJP0CvpB8w)  Tutorials by Alex Forsythe** (🆓 🥇)
* **[Technical Art & Materials](https://www.youtube.com/@BenCloward/videos) Tutorials by Ben Cloward** (🆓 🥇)
* **Epic / Unreal Engine [Learning](https://dev.epicgames.com/community/unreal-engine/learning?source=epic_games), [Documentation](https://dev.epicgames.com/documentation/unreal-engine), [Livesteams](https://www.youtube.com/@UnrealEngine)** (🆓 🥇)
* **[Unreal Source Discord](https://discord.com/invite/unrealsource) Community** (🆓 🥇)
* **Game Developers Conference (GDC) [Vault](https://gdcvault.com/browse/) & [Youtube](https://www.youtube.com/@Gdconf)** (🆓 🥇)
