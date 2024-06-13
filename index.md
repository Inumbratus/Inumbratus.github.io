---
layout: default
---
##### Portfolio - Mitchell Lynn
Last Update: 6/2024

# Who am I?

I'm a Programmer, or "Software Engineer" if we're being fancy. I started programming in 2019, and so as of writing this have 5 years of experience in the field. 
I completed a Diploma and Bachelor's degree of Game Development (Programming) at SAE Sydney, which took 2 years, and then worked for Spectre Studios, before it was acquired by
Virtually Human Studios (VHS), then at Fenix Studios, which was formed from many of the people who made up Spectre Studios originally. 

## Experience

I've used Unity & C#, but my preference is certainly UE4/5's Blueprint system and C++.

*	Unreal Engine (4/5)
*	C++
*	Github
*	Perforce
*	Blender
*   Unity
*   C#

# Projects

## University Projects
I worked on a few projects at SAE, but as they were some of my first work and only small in scale, they've been grouped into a single section

### Survivaur (2019)
[Survivaur](https://kelinmiao.itch.io/survivaur) is a Dinosaur based local multiplayer brawler, two players select a dinosaur and fight to the death in a prehistoric setting.
Survivaur was developed in Unity/C# by a team of 4

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


### Office Horror (2019)
[Office Horror](https://inumbratus.itch.io/office-horror) Is a horror game made using UE4 by a team of 2 (Me and a designer), in it I made used Unreal Engine's AI System (EQS & Behaviour trees), 
Level Streaming, Material Parameter Collections, Serialisation (Saving player progress), and Animation Blueprints

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
	-	Health
-	AI Characters
	-	EQS perception
	-	Behaviour Tree/Blackboard
	-	Animation blueprints
-	Game Logic
	-	Objectives
	-	Win/Lose conditions
	
### Nature Walk (2020)
Nature Walk was a work placement project developed for [LiminalVR](https://liminalvr.com) using Unity.

## Emergisim (2023)

##### Tech used
*	Unreal Engine 4
* 	Perforce
*	HTC Vive
*	Oculus Rift CV1
*	Steamworks

### Overview
[Emergisim](https://www.spectrestudios.com.au/emergisim) is UE4 powered VR medical training software with First Responder and Military applications. 
I came onto the project a fair ways into development, and worked on creating new medical treatments to perform in the project, 
level management systems (For keeping track of player progress in scenarios), and frameworks for new scenarios.

Emergisim has been adopted to varying degrees by a handful of goverment agencies globally, and it also had a commercial release via steam (Without any restricted content included).
[First Responder VR Steam Page](https://store.steampowered.com/app/2289500/FirstResponderVR/)

### RFDS
RFDS is an extension of emergisim for the Royal Flying Doctor Service, with the specific purpose of training flight attendants how to react in the case of pilot incapacitation.
I worked on the scenario progression and additional interactible items required for the scenario (Flight controls panels, pilot's Headphones & Microphone)

## FireCPR

##### Tech used
*	Unreal Engine 4
*	HTC Vive Focus 3
*	HTC Vive Wrist Trackers
*	CPR Dummy

### Overview
FireCPR was a prototype CPR trainer for NSW Fire Services that I worked on extensively, it was built to target the [Vive Focus 3](https://www.vive.com/au/product/vive-focus3/overview/), 
which is a mobile VR platform developed by HTC, as well as the associated [wrist trackers](https://www.vive.com/au/accessory/vive-wrist-tracker/).
A large part of CPR training is how you pose your hands, so  hand tracking had to be used instead of the normal Focus 3 controllers, which is why the wrist trackers became a necessity. 

### Focus 3 &  Wrist Trackers
Unforunately, the hand tracking on the Focus 3 was rather inaccurate at the time (It hadn't been released yet, I was working with a prototype), so in order to have any sort of accuracy
in recording player input (For grading their performance), the wrist trackers were used, as they were far more accurate. So I strapped one of the two wrist trackers around a CPR dummy's neck, 
and the other around my wrist, and from that was able to accurately determine compression depth, rate, and hand position for scoring.

## Stryker

##### Tech used
*	Unreal Engine 4
*	HTC Vive Focus 3
*	Oculus Quest 2

### Overview
Stryker VR was a project designed to train people to make use of a [Stryker](https://www.stryker.com/us/en/index.html) brand AED, and their stretchers.

## Human Park

[Human Park](./humanpark.html).

After Spectre Studios was acquired by VHS, we were put to work developing a game based on a series of NFTs they were developing. I was charged with quickly creating a couple of initial prototypes, 
first using ALSV4, then the Lyra project after it was released by Epic Games. These served adequately as Proof-of-Concept projects, and development then began on what would become Human Park.
Human Park was a Networked Multiplayer obstacle course & social space

### Things I worked on (All Networked/Replicated)
*	Parkour system using motion warping
*	Player Customisation (Hats, Tails, Tattoos)
*	Game logic (Keeping track of player progress, checkpoints)
*	Equippables (Guns, Jetpacks)
*	Player Emotes
*	Vehicles (Forklift, Bicycle, Spaceship)
*	Administrator Verification & Controls

### Docker & Linux
Due to the intended large-scale release of Human Park, I was designated to create linux-based server images for the project, which I accomplished using UE4's Linux toolchain alongside Docker.

## Office Fight

##### Tech used
*	Unreal Engine 5
*	Blender
*	Perforce
*	Steamworks
*	Epic Games Services

### Overview
[Office Fight](https://store.steampowered.com/app/2747060/Office_Fight/) is a casual physics-based office destruction game. It makes extensive use of UE5's chaos physics system, for both environmental destruction
and Skeletal Mesh Ragdolls.

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

## Brawlers



##The Book
A co-wrote a [book]() (with one of my uni teachers who was briefly a coworker) about the basics of Blueprints in UE5




















## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
