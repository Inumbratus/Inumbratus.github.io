---
layout: default
---
##### Portfolio - Mitchell Lynn
Last Update: 3/2025

# Who am I?

I'm a Programmer, or "Software Engineer" if we're being fancy. I started programming in 2019, and so as of writing this have ~5 years of experience in the field. 
I completed a Diploma and Bachelor's degree of Game Development (Programming) at SAE Sydney, which took 2 years, and then worked for Spectre Studios, before it was acquired by
Virtually Human Studios (VHS), then at Fenix Studios, which was formed from many of the people who made up Spectre Studios originally. 

## Experience

I've primarily used UE4/5's Blueprint system and C++ over the last 5 years, but have started using Redot for personal projects.
I've mostly used perforce for source control professionally, privately I use Github.
I've personally shipped projects through Epic Games Store, Steam, XSolla, and Google Play.

*	Unreal Engine (4/5)
*	C++
*	Github
*	Perforce
*	Blender
*	Godot (Redot)
*   Unity
*   C#

# Projects

* * *

## Office Fight
[Office Fight](https://store.steampowered.com/app/2747060/Office_Fight/) is a casual physics-based office destruction game. It makes extensive use of UE5's chaos physics system, for both environmental destruction
and Skeletal Mesh ragdolls.

![](https://raw.githubusercontent.com/Inumbratus/Inumbratus.github.io/main/Assets/Images/OfficeFightheader.png)

### Tech used
*	Unreal Engine 5
*	Blender
*	Perforce
*	Steamworks
*	Epic Games Services

### Things I worked on
-	Takedown system (motion warping)
-	Employee animation blueprint
-	Steamworks build deployment
-	Steam Achievements
-	Epic Games Services build deployment
-	Mobile port
-	Nintendo Switch Port
-	Nearly all UI
-	Throwable Objects
	-	"Fling" throwing
-	Activatable Objects
-	A handful of cosmetics for the Employees
-	Narrative structure
	-	The setting of Office Fight is loosely based on Divine Comedy/Dante's Inferno, the floors of the Office represent the circles of hell, and the bosses of these floors are embodiments of the sin assosciated with their floor. This was my idea.


### Interesting tech and solutions used
- Reverse fling throwing
	-	I created reverse "Fling" throwing in Office Fight using the projectile prediction system in UE5, which takes a start and an end point and tracing a projectile path between them using supplied parameters, and returns collision information based on this trace.
	I achieved this by inverting the player's mouse/finger position in screen space, then getting a point on a line starting at this inversion of the player's input position and ending below the level, closest to the object selected to be thrown, which gives a world-space location opposite the player's input, and using then that as the end point in the projectile pathing calculation.

- Blender foray
	-	I'm not a 3D artist, but I learned some of the basics working on Office Fight. I did a elective animation class in Uni, and have worked quite extensively with UE's animation blueprints in the past, so I had a pretty good basis for skinning/rigging, but modelling took a bit longer to get the handle of. I made a handful of the cosmetics for the employees in the game, they were based on the existing models made by an actual 3D Artist, but I did make and skin the outfits pictured below, these aren't all of the ones I worked on, but they're the most apparent ones.

![](https://raw.githubusercontent.com/Inumbratus/Inumbratus.github.io/main/Assets/Images/OF_Jester_Thumb.PNG) ![](https://raw.githubusercontent.com/Inumbratus/Inumbratus.github.io/main/Assets/Images/OF_ShinobiSetThumb.PNG) ![](https://raw.githubusercontent.com/Inumbratus/Inumbratus.github.io/main/Assets/Images/OF_CardboardSetThumb.PNG)

* * *

## Game Development with Unreal Engine 5 (2023)
I co-wrote a [book](https://bpbonline.com/products/game-development-with-unreal-engine-5?_pos=1&_sid=82f4a319d&_ss=r) (with one of my uni teachers who was briefly a coworker) about the basics of development using Blueprints in UE5

* * *

## Human Park (2022)
After Spectre Studios was acquired by VHS, we were put to work developing a game based on a series of NFTs they were developing. I was charged with quickly creating a couple of initial prototypes, 
first using ALSV4, then the Lyra project after it was released by Epic Games. These served adequately as Proof-of-Concept projects, and development then began on what would become [Human Park](https://humanpark.io).
Human Park was a Networked Multiplayer obstacle course & social space deployed via XSolla.

### Tech used
*	Unreal Engine 4
*	Perforce
*	Epic Games Services
*	XSolla

### Things I worked on (All Networked/Replicated)
-	Player Animations
	-	Parkour system (motion warping)
	-	Emotes
-	Player Customisation
	-	Hats
	-	Tails
	-	Tattoos
-	Game logic
	-	Checkpoints
	-	Scoring
-	Environmental Hazards
-	Equippables
	-	Pistols
	-	Sword
	-	Jetpack
	-	Jetpack with pistols
-	Vehicles
	-	Forklift
	-	Bicycle
	-	Space Ship
	-	Drone
	-	Hoverboard
-	Administrator Verification & Controls
-	Linux-based Server Images

### Interesting tech and solutions used
- Niagara Animation props
	- Partway into development, we were asked to add props to the emotes in the game, the initial plan was to make a component based attachment system, which I heavily disliked for a number of reasons. As the Niagara FX system was just introduced, I tasked a Technical Artist with attempting to render a prop via the Niagara system, once that was shown to be possible, it was extremely easy for our technical animator to add a prop joint to the skeleton and animate it, then we were able to use animation notifiers to render the props, allowing for the entire system to be neatly contained within animation sequences. 

- Linux-based Server Images
	- Due to the intended large-scale release of Human Park, I was designated to create linux-based server images for the project, which I accomplished using UE4's Linux toolchain alongside Docker, the images were then deployed using [Google Kubernetes Engine](https://cloud.google.com/kubernetes-engine)

* * *

## Project Tyrion
[Project Tyrion](https://crisiscastvr.com) is VR diplomatic relations training software developed in UE4, with the specific purpose of preparing the user for engaging in diplomatic engagements with nomads in West Africa.

### Tech used
*	Unreal Engine 4
* 	Perforce
*	HTC Vive

### Things I worked on
-	Animation Blueprinting for the hands
-	Inventory System
-	Player interaction

* * *

## Stryker
Stryker VR was a project designed to train people to make use of a [Stryker](https://www.stryker.com/us/en/index.html) brand AED, and their stretchers.

### Tech used
*	Unreal Engine 4
*	HTC Vive Focus 3
*	Oculus Quest 2

### Things I worked on
-	Packaging & Deployment
-	Scenario progression/game logic

* * *

## FireCPR
FireCPR was a prototype CPR trainer for NSW Fire Services that I worked on extensively, it was built to target the [Vive Focus 3](https://www.vive.com/au/product/vive-focus3/overview/), 
which is a mobile VR platform developed by HTC, as well as the associated [wrist trackers](https://www.vive.com/au/accessory/vive-wrist-tracker/).
A large part of CPR training is how you pose your hands, so  hand tracking had to be used instead of the normal Focus 3 controllers, which is why the wrist trackers became a necessity. 

### Tech used
*	Unreal Engine 4
*	HTC Vive Focus 3
*	HTC Vive Wrist Trackers
*	CPR Dummy

### Focus 3 &  Wrist Trackers
Unfortunately, the hand tracking on the Focus 3 was rather inaccurate at the time (It hadn't been released yet, I was working with a prototype), so in order to have any sort of accuracy
in recording player input (For grading their performance), the wrist trackers were used, as they were far more accurate. So I strapped one of the two wrist trackers around a CPR dummy's neck, 
and the other around my wrist, and from that was able to accurately determine compression depth, rate, and hand position for scoring.

* * *

## Emergisim (2023)
[Emergisim](https://www.spectrestudios.com.au/emergisim) is UE4 powered VR medical training software. 
I came onto the project a fair ways into development, and worked on creating new medical treatments to perform in the project, 
level management systems (For keeping track of player progress in scenarios), and frameworks for new scenarios.

Emergisim has been adopted to varying degrees by a handful of goverment agencies globally, and it also had a commercial release via steam (Without any restricted content included).
[First Responder VR Steam Page](https://store.steampowered.com/app/2289500/FirstResponderVR/)

### Tech used
*	Unreal Engine 4
* 	Perforce
*	HTC Vive
*	Oculus Rift CV1
*	Steamworks

### Things I worked on
-	Scenarios
	-	Tutorials
	-	Pilot Incapacitation
	-	Mass Casualty
	-	Tactical Combat Casualty Care (TCCC)
	-	Ambulance Transit
-	Player Character
	-	Bag Storage
		-	IFAK on hip
		-	Larger bags on back
	-	Hand animation implementation
	-	Blood Sweeping
	-	Crouched bag displacement
-	Player Scoring
	-	Serialisation
-	UI
	-	IMIST
	-	Score/results
-	Equipment
	-	Treatment bags
		-	IFAK
		-	(Para)Medic bags
		-	O2 bag
	-	[QuikClot](https://quikclot.com) Wound Packing
	-	Junctional Tourniquet
	-	Pilot Equipment
		-	Control Panel
		-	Microphone
		-	Headphones
	-	[IGEL](https://au.intersurgical.com/info/igel)
	-	[Laerdal Suction Unit](https://laerdal.com/au/products/medical-devices/airway-management/laerdal-suction-unit-lsu/) (LSU)
	-	Penlight
	-	Space Blanket
	-	Oropharyngeal airway (OPA)
	-	Tourniquet
	-	Triage Tags
	-	Stethoscope
	-	Helmet
	-	Body Armor
	-	Gasmask
	-	Night Vision Goggles (NVGs)
	-	Bag-Valve Mask (BVM)
	-	Blood Glucose Meter (BGM)
-	Drugs
	-	Ketamine
-	Oculus Compatibility

### Interesting tech and solutions used
- Emergisim 2 Prototype
	- Full body IK
	- Bone based injuries & Treatments
	- Replicated ragdolls
	- Responsive vitals
- [Cognitive3D](https://cognitive3d.com) Implementation

### RFDS
RFDS is an extension of Emergisim for the Royal Flying Doctor Service, with the specific purpose of training flight attendants how to react in the case of pilot incapacitation.
I worked on the scenario progression and additional interactible items required for the scenario (Flight controls panels, pilot's Headphones & Microphone)

* * *

# University Projects

## Office Horror (2019)
[Office Horror](https://inumbratus.itch.io/office-horror) Is a horror game made using UE4 by a team of 2 (Me and a designer) about a digruntled employee taking down a company he discovered was partaking in extremely immoral work.

### Tech used
*	Unnreal Engine 4
* 	Github 
*	Itch.io

### Things I worked on
-	UI
	-	Menus
-	Saving & Loading progress
-	Level Streaming
-	Player Character
	-	Movement
	-	Animation Blueprint/Blending
	-	Retargeting (Using the UE4 animation retargeter)
	-	Projectile Launcher
	-	Player Perspective
	-	Health (Material Parameter Collection)
-	AI Characters
	-	EQS perception
	-	Behaviour Tree/Blackboard
	-	Animation blueprints
-	Game Logic
	-	Objectives
	-	Win/Lose conditions

* * *

## Survivaur (2019)
[Survivaur](https://kelinmiao.itch.io/survivaur) is a Dinosaur based local multiplayer brawler, two players select a dinosaur and fight to the death in a prehistoric setting.
Survivaur was developed in Unity/C# by a team of 4

### Tech used
*	Unity
*	C#
* 	Github 
*	Itch.io

### Things I worked on
-	UI
	-	Level Select
	-	Options Menu (Custom input mapping, Graphical & Audio Settings)
	-	Tutorial Implementation
-	Player Characters (Dinosaurs)
	-	Special Abilities
	-	Resources (Health, Stamina, Rage)
	-	Interaction (Combat and Consumption)
	-	Movement
	-	2D Animation state machine
-	Game Logic
	-	Player lives
	-	Respawning
	-	Environmental hazards
	-	Camera Positioning
-	Packaging & Deployment

### WebGL Build

<iframe src="https://i.simmer.io/@Inum/~5d7f0929-d756-aa8c-950b-2d6488177100" style="width:960px;height:600px"></iframe>


* * *