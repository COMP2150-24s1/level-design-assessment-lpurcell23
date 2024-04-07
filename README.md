[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: [Louis Purcell]
### Student number: [47311088] 

## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

### 1.1. Discovery

Progressive Skill Development: Starting with basic controls in the initial levels, such as movement and combat, players gradually learn more advanced maneuvers like crouching and shooting simultaneously, jumping while dodging spikes, and navigating through complex environments. This approach ensures players can always handle the information simultaneously, allowing them to develop their skills organically.

Enemy Awareness and Strategy:  Players must adapt their tactics and strategies from the initial encounter with elemental foes like acid and chomper to the introduction of more formidable adversaries like spitters. By learning the strengths and weaknesses of each enemy type, players can devise practical approaches to overcome obstacles and progress through the levels.

Decision-Making and Risk Assessment: The level design incorporates elements that require players to make decisions and take calculated risks. For example, in the final level, players are presented with three distinct paths, each with challenges and rewards. This encourages players to consider their options carefully, weighing the potential dangers against the possible benefits. 

Anticipation and Adaptation: By introducing unexpected twists and obstacles, such as deceptive pathways and environmental hazards, players must learn to think on their feet and adjust their strategies in real-time. This keeps players on their toes and promotes a sense of satisfaction as they successfully navigate unpredictable situations.



### 1.2. Drama

Introduction of Mechanics and Incremental Complexity:  This gives a gentle introduction, allowing players to familiarise themselves with the game environment without feeling overwhelmed when the levels progress. For example, players encounter a new enemy type (spitters) in the second level and learn to utilise a long-range weapon. This increases the complexity of gameplay while still building upon the skills learned in previous levels.

Problem-Solving: I integrated problem-solving elements into the gameplay, such as pressure plates that require strategic thinking to navigate. This adds depth to the gameplay experience and encourages players to think critically about their actions.

Moments of Tension and Relief: I strategically insert moments of tension and relief throughout the game to keep the player engaged. For instance, the player may face intense combat encounters followed by moments of exploration or puzzle-solving, providing a brief respite before the next challenge.

Navigational Complexity: In the final level, players must master all previously introduced mechanics and skills. I introduced branching paths and navigational challenges that require careful exploration and decision-making. Players must navigate through deceptive routes and backtrack to complete tasks, adding a layer of complexity and uncertainty to the gameplay.

### 1.3. Challenge

Mechanical Mastery: Players must become proficient in executing mechanics to progress effectively from basic movements to more complex actions like combat maneuvers and environmental interactions. Each level builds upon the skills learned in previous levels, allowing players to acclimate to the controls at their own pace. 

Environmental Hazards and Obstacles Hazards include spikes, acid pools, and other traps requiring precise timing and navigation. I've carefully placed these obstacles in the game world to control the difficulty curve, ensuring they are challenging enough to provide a sense of accomplishment when overcome but not so punishing as to frustrate players. 

Enemy Encounters:  Players must employ different strategies and tactics, from elemental foes to more powerful adversaries, to defeat or evade these enemies. Additionally, we've provided players with multiple options for approaching combat encounters, such as using stealth, ranged attacks, or environmental hazards, allowing for flexibility in gameplay and strategy. 

Puzzle-Solving and Exploration: To maintain engagement during these levels, I've designed intuitive and solvable puzzles with the information provided within the game world. 

### 1.4. Exploration

Organic and Immersive Environments: I strived to make the environments feel organic and immersive, seamlessly blending landscape elements with gameplay features. For example, spikes are integrated into the natural terrain, making them feel like a natural part of the environment rather than artificially placed obstacles. By incorporating these elements into the landscape, players are encouraged to explore their surroundings more deeply, as they feel like authentic parts of the game world.

Curved and Natural Layouts: The level layouts are designed with curves and natural contours rather than rigid block-like structures. This adds visual interest and contributes to the believability and immersion of the game world. Players feel like they are navigating through caves in floating islands, enhancing the sense of discovery and exploration.

Distinct and Memorable Spaces: Through the aesthetic and layout choices, I aimed to create different and memorable spaces that leave a lasting impression on players. Each area of the game world has its unique visual identity and atmosphere, from pink voluminous cotton candy skies to ominous caverns, by carefully crafting these spaces with attention to detail, lighting, and environmental storytelling.

Negative Space as Background: I kept negative space uncluttered to draw attention to key objects and elements, guiding the player's movement and focus. 

Positive Space: These spaces are not merely background elements but integral components of the game world that contribute to its atmosphere and narrative.

## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1. Acid

![Acid!](DocImages/acid.png)

The player approaches a pool of acid.
As the player steps into the acid, they die and respawn at the most recent checkpoint, demonstrating the hazardous nature of the substance.
The player then figures they need to find another way to get past
Introducing acid early in the game establishes it as a dangerous environmental hazard, teaching players to recognize and avoid it to prevent losing progression.

### 2.2. Checkpoints

![Checkpoints!](DocImages/checkpoints.png)

The player reaches a glowing checkpoint marker.
The player activates the checkpoint by interacting with it, causing it to emit a bright light.
The Introduction of checkpoints ensures players understand they can save progress and respawn, providing a sense of security as they navigate through challenging sections of the game.

### 2.3. Chompers

![Chompers!](DocImages/chomper.png)

The player encounters an enemy after picking up a weapon.
As the player approaches, the chompers attack, and will lose health if hit.
The player can use their weapon to defeat the chompers and continue.
Introducing chompers after introducing the weapon helps the player understand how to deal with the enemy.

### 2.4. Health Pickups

![HealthPickups!](DocImages/healthpacks.png)

The player approaches a health pickup on the ground, with a medical cross symbol displayed within it.
As the player collects the health pickup, their health bar replenishes.
Health only goes up if the player has previously taken damage
Introducing health pickups after the first incounter with enemy provides players with a means to recover from damage taken, teaching them the importance of managing their health throughout the game.

### 2.5. Keys

![Keys!](DocImages/key.png)

The player discovers the key symbol once completeing a segment of the level.
Once collected the Key will appear as collected for the player
As the player collects the key, it disappears from the environment, and a sound effect plays.
Collecting the key shows the player the player has completed a part of the level and gives them a sense of completion.

### 2.6. Moving Platforms

![MovingPlatforms!](DocImages/movingplatform.png)

The player approaches a large pool of acid with a platform moving from one side to another.
As the player steps onto a moving platform, they are carried over the pool of acid.
The player successfully navigates across the moving platforms to reach the other side..
Using moving platforms familiarizes players with platforming mechanics and dynamic level elements, preparing them for more complex platforming challenges later in the game.

### 2.7. Passthrough Platforms

![PassthroughPlatfroms!](DocImages/passingthroughplatforms.png)

The player encounters a platform with circles on it and realise they are unable to get pass the spikes.
This prompts the player to pass through the platform to avoid the spike safely.
Once the player is safe from the spikes they are able to jump back up through the platform.
The passthrough platforms makes players navigate hazardous areas safely, adding depth to platforming and traversal mechanics.

### 2.8. Spikes

![Spikes!](DocImages/spikes.png)

The player approaches a section of the ground with sharp spikes.
As the player steps onto the spikes, they take damage and a pain animation is triggered.
The player retreats from the spikes and finds an alternate path to get past them.
The initial introduction to the spikes emphasizes their role as deadly hazards, teaching players to avoid them.

### 2.9. Spitters

![Spitters!](DocImages/spitter.png)

The player encounters a spitter enemy perched on a ledge.
The spitter launches projectiles at the player character, demonstrating its ranged attack.
The player can evade the projectiles and defeat the spitter using ranged or melee attacks.
Spitters introduce players to ranged combat mechanics and teaches them to prioritize and strategize when dealing with different enemy types.

### 2.10. Weapon Pickup (Gun)

![WeaponPickupGun!](DocImages/weapongun.png)

The player discovers a gun pickup on the ground.
As the player picks up the gun, a sound effect plays.
The player then uses 'O' to use the gun and defeat the enemy ahead.
Introducing the gun at the same time as the spitters helps the player understand how to deal with ranged situations.

### 2.11. Weapon Pickup (Staff)

![WeaponPickupStaff!](DocImages/weaponstaff.png)

The player discovers a staff pickup on the ground.
As the player picks up the staff, a sound effect plays.
The player then uses 'K' to use the staff and defeat the enemy ahead.
Introducing the staff at the same time as the chomper helps the player understand how to deal enemys.

## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1

### 3.3.	Level Map – Section 2

### 3.4.	Level Map – Section 3

## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.

## Generative AI Use Acknowledgement

Use the below table to indicate any Generative AI or writing assistance tools used in creating your document. Please be honest and thorough in your reporting, as this will allow us to give you the marks you have earnt. Place any drafts or other evidence inside this repository. This form and related evidence do not count to your word count.
An example has been included. Please replace this with any actual tools, and add more as necessary.


### Tool Used: ChatGPT
**Nature of Use** Finding relevant design theory.

**Evidence Attached?** Screenshot of ChatGPT conversation included in the folder "GenAI" in this repo.

**Additional Notes:** I used ChatGPT to try and find some more relevant design theory that I could apply to my game. After googling them, however, I found most of them were inaccurate, and some didn't exist. One theory mentioned, however, was useful, and I've incorporated it into my work.

### Tool Used: Example
**Nature of Use** Example Text

**Evidence Attached?** Example Text

**Additional Notes:** Example Text


