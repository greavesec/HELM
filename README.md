Welcome to HELM!

HELM is a **modular**, **internal**, **unbiased** role-playing game system designed for use in multiplayer games like *World of Warcraft*, or in standalone IRC chats or forums. It uses basic random number generation to query player versus Game Master in self-contained sessions, called *events*.

HELM is a **modular** system; It can be customized to fit specific game environments and user preferences. HELM can range from a barebones roll tracker to a fully realized d20 system. 

HELM operates **internally**, within a game setting, webapp or site, or other application chosen by the Game Master--even on pen and paper!

HELM is **unbiased**, meaning its themes and mechanics can be adapted to fit a wide variety of settings. Elements are genre-agnostic, and may be presented in whichever flavor the Game Master wishes.

A list of HELM modules can be found in Appendix II, towards the end of this document. It is recommended that you play using the core modules, then add additional modules according to your preferences. If you are a player, your Game Master will inform you of which modules you will be using.

HELM is in an unfinished state. It is likely that many rules will be unclear, certain builds will be unbalanced, and game flow will be broken. It is up to the Game Master to navigate these issues and make rulings on the fly to ensure a smooth experience for their players. When in doubt, *just say yes*, *fail forward*, and follow *the rule of cool*.

Thank you for trying HELM! 

\- Greaves
# Chapter 1 - Create a Character

> [!NOTE] Important!
> New players are strongly encouraged to read this document through in its entirety.
> 
> It is important for Game Masters to familiarize themselves with the character creation process. However, information more pertinent to their role can be found beginning at **Chapter 1.6 - Character Sheet**.


The first step to playing HELM is to create a character. 

To do so, you will select their attributes from a list of presets. You may select any of the options below, but your choices should reflect the character you are representing.

Your Game Master may inform you of specific limitations ..
## 1.1 - Skill Level
Your character's skill level reflects their fundamental ability to land attacks, deflect damage, solve problems, and benefit their allies. It is the root of all interactions done within HELM.

Certain conditions, such as wealth, fitness, equipment, mood, etc., may all confer a higher or lower skill level than those on otherwise equal footing.

You may change your character's skill level between events.

| Skill Level | Hitpoints | Defense | Roll Table | Ability*          | Max Talents* |
| ----------- | --------- | ------- | ---------- | ----------------- | ------------ |
| Novice      | 20        | 3       | 1-20       | Beginner's Luck   | 1            |
| Journeyman  | 25        | 4       | 1-20       | -                 | 2            |
| Expert      | 30        | 5       | 1-21       | -                 | 2            |
| Master      | 35        | 5       | 2-21       | Master's Tutelage | 2            |

\* - Requires [[Talented 0.1]] module. Consult the module for descriptions.
## 1.2 - Role
Your character's role is their preferred (or natural) position in the adventuring party. This might not just mean their place in the marching order, but could infer the tools and disposition they bring with them in and out of combat.

You may change your role between events.

| Role            | Description                                                                                                                                                                                                                                                                                                                            |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| The Frontman    | You take the lead in the marching order. As a result, you are often the first target of a trap, hazard, or surprise attack, and you have advantage on all rolls made to negotiate them.                                                                                                                                                |
| The Face        | You are the talker of the party. You have advantage on all rolls made to charm, lie, intimidate, or otherwise coerce a target, or detect when you or your allies are the target of such.                                                                                                                                               |
| The Sneak       | You stick to the shadows (and probably chose the Rebel archetype). You have advantage on all rolls made to sneak, hide, and steal, and you automatically succeed at bypassing mundane locks.                                                                                                                                           |
| The Lookout     | You stand watch while others do the solving. As a result, you have advantage on all rolls made to spot suspicious activity and incoming danger. You cannot be Surprised.                                                                                                                                                               |
| The Scholar     | Years of nonspecific study and experience has rendered you proficient in detecting arcana and technology, and solving puzzles. You have advantage on all rolls made to track and identify magic or technology, and discern solutions to problems.                                                                                      |
| The Freebooter* | You're in it to win it, baby. When you're shown the *hoard*--the items typically distributed at the end of an event--you have first pick at the loot, so long as your character knows it's there and can plausibly reach it in time. <br><br>You also gain 1-10 additional Treasury coins (guild-specific) when first shown the hoard. |

\* - Requires [[Treasury 0.2]] module.
## 1.3 - Archetype
Your character's archetype represents their preferred role in combat. Archetypes are designed so that those who are proficient in certain skills may flourish, and not be overpowered by those with completely different skill-sets.

You may change your archetype between events.

Archetypes require use of the [[Talented 0.1]] and [[Treasury 0.2]] modules.

| Archetype    | Description                                                                                                                                                                                                                                                                                            |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Brawler**  | - +15 Hitpoints.<br>- You gain Bully in addition to your other talent(s).<br>- You may target as many enemies with Bully as you wish.                                                                                                                                                                  |
| **Sentinel** | - Maximum Defense is now 30.<br>- Passive. +2 Defense.                                                                                                                                                                                                                                                 |
| **Maverick** | - +2 Attack.<br>- Twice per day, you may make an additional Attack during the Ally Phase.<br>- Your items have one additional charge. If they are **Use**, they are now **Use (2/2)**. Items that have been partially used **Use (1/2)** may not regain charges, and are lost at the end of the event. |
| **Rebel**    | - Twice per day, you may double your damage dealt in a single Attack (after modifiers).<br>- You have advantage on all of your Attacks, but you can no longer Support.<br>- You do not benefit from your ally's Passives, Defense, or Support (except when used to heal).                              |
| **Wingman**  | - +2 Support.<br>- Once per day, you may restore an ally to their maximum Hitpoints.<br>OR<br>- Once per day, during the Ally Phase, allocate a bonus of +30 across your allies' rolls as you see fit.                                                                                                 |
| **Wildcard** | - +2 Attack, Defense, and Support.<br>- Gain an additional Talent. This does not count against your Max Talents.                                                                                                                                                                                       |
## 1.4 - Talents
See: [[Talented 0.1]]

Talents are special abilities that you may select to provide additional customization to your character. These are minor spells and maneuvers that may be flavored however you wish, but they all have specific effects that can influence the course of an event.

You may use talents alongside items *and* your normal roll in the same phase unless stated otherwise. Each talent may only be used once per phase, but you may use as many talents as you wish.

The maximum number of talents you may select is determined by your character's skill level.

Talents may be swapped between events.
## 1.5 - Items & Equipment
See: [[Treasury 0.2]]

Game Masters may adopt an item system to provide an additional layer of character building to their HELM events. HELM provides an expansive list of items--and a currency in which to purchase them--in the [[Treasury 0.2]] module.

Using [[Treasury 0.2]], all player characters are given a starting allowance of 5 coins to spend on initial adventuring gear. More coins are found or earned during events, or by selling used items.

Characters may bring a maximum of 3 items to an event. Items are typically retained between events. If a character obtains an item during an event (and has space to hold it), that character will retain access to that item.

Items may be swapped between events. Characters may discard items at any time.

You may use or activate any number of your items in addition to your roll that phase. However, items may each only be used *once per phase* unless otherwise stated.

> [!NOTE] Important!
> Consult the [[Treasury 0.2]] module for additional rules.
## 1.6 - Character Sheet
See: [[Csheets 0.1]]

HELM requires you to record your character's data in a shareable format, such as a public text file. If you are a player, your Game Master will provide you with a solution.

Players are generally expected to keep track of their own character sheets. Your Game Master may be keeping an eye on them, but they are often juggling too many things to keep them updated and accurate.

When sharing files related to HELM, ensure read AND write permissions are granted: 
- So that your Game Master may make updates and corrections, and...
- So that your players can import their own character sheets.

Common solutions:
- Google Docs/Sheets, Miro, or other cloud-based document manager;
- Note-taking software with collaborate feature;
- In-game text editor or profile add-on;
- A shared piece of paper.

Example Format:

|                                                         | HP    | DEF | ROLL | MOD       | TALENTS                                        | ITEMS                                                       | STATUS    |
| ------------------------------------------------------- | ----- | --- | ---- | --------- | ---------------------------------------------- | ----------------------------------------------------------- | --------- |
| **Jacob Grim**<br><br>Expert Maverick<br><br>*The Face* | 30/30 | 4/4 | 1-21 | +4 Attack | Maverick (2/2)<br><br>Pep Talk<br><br>Frontman | The Coin (2/2)<br><br>Beard Oil (1/2)<br><br>Barber's Razor | Beard Oil |
 

> [!NOTE] Game Masters' Note
> You can array NPCs using the same format as the players' character sheets. In the [[Csheets 0.1]] module, there is a section for your NPCs. Note that the players can see whatever you fill this field with; This is the default configuration for HELM. 
> 
> If you wish to have an NPC's attributes be hidden, you must create a separate, private file to track it (or simply store it in your head).

# Chapter 2 - Playing the Game

At its core, HELM (and many other TTRPGs) is a collaborative exercise in creativity and problem solving between player and Game Master. It operates on back-and-forth dialogue and feedback between both parties to build and present a cohesive game together:
1. The **Game Master** describes a setting or encounter that the players are faced with.
2. The **players** inform the Game Master of their decisions on how to proceed.
3. The **Game Master** informs the players on how to navigate the challenge, typically with a roll.
4. The **players** relay their roll to the Game Master after applying all relevant modifiers.
5. The **Game Master** describes the outcome based on the player rolls.
6. Repeat.

> [!NOTE] Game Masters' Note
> While there are many ways to set up and play with HELM, it is ultimately a collaborative environment; It should not feel to your players that you are inhibiting them, nor to you that they are foes to be opposed.

## 2.1 - Actions & Rolls
When a character performs an action, like swinging at an enemy, casting a spell, or navigating an obstacle, your Game Master may ask you to *roll*. When doing so, consult your *roll table* (ex. 1-20). This is the range in which you will *roll*.

Rolling is system-dependent, but only requires the ability to generate a random number within a range (your roll table). *Rolling* refers to generating this random number.

> [!NOTE] Important!
> Your roll table can be influenced by a wide variety of sources, such as talents and equipment. If you are equipping a weapon, you may have a separate roll table for Attack rolls only.

After rolling, you must apply any relevant modifiers, such as +2 to your Attack rolls if you selected the Maverick archetype, or the bonus provided by an ally Support roll (see below for preset rolls and how to use them).

Once the final roll value is calculated, it must then be presented to the Game Master. Once you have made your roll, you cannot take it back, nor change your intended action.
### 2.1.1 - Preset Rolls
Preset rolls are HELM's default player actions. They are keywords that link to other elements within HELM, such as your equipment and archetype.

| Roll    | Description                                                                                                                                                                                                                                                                                       |
| ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Attack  | Compare your roll to the target's Defense:<br><br>- If your roll is higher, reduce the target's Hitpoints by the difference.<br>- If your roll is lower, the attack fails.                                                                                                                        |
| Defend  | Increase your Defense or an ally's by the value rolled, to a maximum of 20.<br><br>- Defense is reset upon being targeted by an opponent's attack, whether it is successful or not.<br>- In the event an Attack ties with Defense, the defender has the upper hand, and the offending roll fails. |
| Bide    | Modify your next roll by the value rolled.<br><br>- You may not stack Bide with itself; You must use your Bide before making another Bide roll.                                                                                                                                                   |
| Support | Increase an ally's roll or recover their Hitpoints by the value rolled.<br><br>- All rolls may be supported by multiple allies.                                                                                                                                                                   |
### 2.1.2 - Skill Checks
At any point during an event, your Game Master may ask you to make a *skill check*. This is typically done in response to a player's general action. To do so, make a roll based on your roll table, add any applicable modifiers, and present the final value to your Game Master.

While 'skill check' is a colloquial term, you will most often find the following 'skills' at play during events (followed by the relevant role in brackets):
- Survival check (The Frontman)
- Social check (The Face)
- Stealth check (The Sneak)
- Perception check (The Lookout)
- Knowledge check (The Scholar)
### 2.1.3 - Free & Pass Actions
..

### 2.1.4 - Critical Rolls
A *critical roll* refers to the highest value on your roll table. Certain rules or abilities may allow you to automatically roll a critical.

If you make a critical roll naturally (without the aid of modifiers), you double your roll and then add any applicable modifiers.

If a rule states that you make a critical roll, unless that rule states otherwise, you may treat it as a natural critical roll.
## 2.2 - Game Phases
HELM operates in phases, alternating between the players and Game Master. These are called the Ally Phase, and World Phase respectively. Typically, these game phases are only tracked during combat or tense encounters where the Game Master must retain control and make minute rulings.

Your Game Master will announce when a new phase begins.
### 2.2.1 - Ally Phase
During the ally phase, players may take actions and make rolls. Generally, all player actions are considered to happen simultaneously (no turn order), with pivotal moments--such as first blood or the final blow--happening on the first and last points of damage respectively.

If you wish to prioritize your action over your allies', preface your emote with an exclamation point (!) or simply mention it early in the ally phase.
### 2.2.2 - World Phase
During the world phase, the Game Master executes the actions of nearby NPCs and/or triggers encounters. Players cannot typically take actions during the world phase.
### 2.2.3 - Example Round
..
### 2.2.4 - Event vs. Adventuring Day
Certain items and abilities may have restrictions on how often they may be used or changed. This is typically determined by *uses per event* or *uses per day*. 

Event refers to the whole body of the current game. It typically means the present game session, but can encompass the entirety of a multi-session campaign. Consult your Game Master to determine how your game is structured.

The adventuring day is a smaller division within the overall event structure. It represents the in-universe day that your character is adventuring on. A single event may be made up of multiple adventuring days.

When your Game Master determines that an adventuring day has passed, all your stats are refreshed to their defaults, and all items with the *uses per day* tag are recharged.

## 2.3 - Conditions

| Condition         | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| ----------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Incapacitated** | A character is *Incapacitated* when they reach 0 Hitpoints or below. They are removed from the encounter and cannot make rolls or benefit from modifiers.<br><br>If a character is healed above 0 Hitpoints, they return to the fight and may take actions and make rolls as normal on the next phase.<br><br>When a player reduces an NPC to 0 Hitpoints or below, the player may decide if they wish to incapacitate the target, slay it, or otherwise destroy it. *A slain foe cannot be revived, but it is assumed that the player's method of incapacitation will always render the target unable to interfere further.* |
| **Surprised**     | A character is *Surprised* when an enemy confronts them in an unexpected manner, typically after failing a check to prevent it (ex. spotting an ambush). <br><br>A *Surprised* character may not take any action on the next phase.                                                                                                                                                                                                                                                                                                                                                                                           |
# Appendix
## i. Glossary
- **Advantage.** Roll twice and pick your preferred result.
	- **Disadvantage.** Roll twice and pick the lowest result.
- **Character Sheet.** Document that houses character attributes in a ready format.
- **Conditions.** Status effects inflicted upon characters, often having negative qualities.
- **Defense (DEF).** Determines a character's defensive capabilities. When a character takes damage, its defense is reset to this value.
- **HELM.** **H**ost **E**ngine for **L**inked **M**odules.
- **Hitpoints (HP).** Determines a character's Hitpoint maximum. When a character's hitpoints reach 0, it is *Incapacitated.*
- **Module.** Optional expansions for the host engine.
	- **Core.** Modules that are considered integral to HELM by the developer.
	- **Xpac.** Official, non-essential modules; 'eXpansion PACks'.
	- **Community.** Third-party modules designed by the community.
- **Roll.** Get a random number within the applicable roll table.
- **Roll Table.** The values that a character rolls between when performing a relevant action. Alternate roll tables may be provided by your Game Master.
- **Skill Level.** Governs baseline attributes and roll table.
- **Talents.** Special abilities that characters possess. Requires [[Talented 0.1]] module.
	- **Ability.** Inherent talents that certain skill levels possess. These do not count against your Max Talents.
## ii. Modules
### Core
- [[Csheets 0.1]] - Character Sheet Rules
- [[Talented 0.1]] - Talents Manager
- [[Treasury 0.2]] - Item Manager
### Xpac
- **Cavalry 0.1** - Grid Movement & Mounted Combat (discont.)
- **Classified 0.1** - Class & Leveling System (discont.)
### Community
- None.. yet!
## iii. Credits

| Version        | 0.4                                              |
| -------------- | ------------------------------------------------ |
| Project Lead   | Greaves                                          |
| Artists (Icon) | Jan & Vlad Schwarts                              |
| Contributors   | Claret Coin<br>Quillspark<br>Swordpunk<br>Winter |
| Created        | 2022                                             |
| Created By     | Greaves                                          |
| Special Thanks | Battered Buckler                                 |