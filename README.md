# iTheon's New Tasks Addon v0.4.1a

This mod adds several new repeatable quests to Stalker Anomaly that bring some fresh air to the vanilla set of quests that are very similar to each other.<br>
Note: "During the night" refers to 10 PM - 3 AM.<br>
Changelog available at the bottom.<br>
You need the modified exes by Demonized for some the quest dialogs to be registered properly to the existing NPCs (if you're playing some modpack, then you almost surely got them installed)

Added questlines (much longer than the radiant tasks described below):
- The Living Fire - questline starts at Bar and is taken from Snitch in a similar manner as an ordinary task. Prerequisites: finished Living Legend and turned of the Miracle Machine (DLTX mandatory for the dialogs to get registered)
- Mystery of the Swamps - continues the story of some other tasks. It has some hidden prerequisites that aren't hard to meet and the player will be guided towards the quest giver afterwards through some SMS and dialogs once it becomes available.

Currently available quests with short descriptions (you'll find more in-depth story behind when talking with NPCs):

**From important NPCs:**

Petrenko:
- Hold the Ground - defend the Flea Market from bandit invasion.

Lukash:
- Skyfall - destroy a military helicopter

Dushman:
- No Step Back - take back part of Limansk and hold against storming monolith forces.

Sakharov:
- Brain Game - kill a controller without damaging its head.
- Stolen Specimen - retrieve a rare artifact required for further research from Sinners

Voronin:
- Urgent Orders - this quest is assigned automatically to Dutyer (original Dutyer - disguise won't work) to give a more military-like feeling to the faction. Go to Yantar and bring back a squad of sciencists to save wounded soldier with limited time (5 in game hours)

Kuznetsov:
- Urgent Orders - same as Voronin's quest but for military.
- Enforce Embargo - intercept an artifact from a loner stalker

Sidor:
- Dead Night - investigate the disappearance of stalkers in Darkscape at night.
- Cold-blooded Betrayal - retrieve an artifact from a loner outcast

Barman:
- Baba Yaga - investigate the disappearance of stalkers on Garbage at night.

Cold:
- House of Horrors - an eviscerated sentry has been found at the seemingly safe Clear Sky outpost. You need to look into this case.

Beard:
- Mirage - an artifact hunter has barely made it out alive after being shot by someone who looked exactly like himself. You need to investigate the place.

Trapper:
- Big Game - a pack of pseudogiants has taken refuge in a train tunnel in Jupiter. Trapper asks you to eliminate the threat.

Olivius:
- Shakedown - retrieve an artifact from a group of scientists that tresspassed on Bandit's territory.

Cashier:
- Blood-stained Coin - Cashier was robbed of a rare artifact right before making a deal with a stalker. You need to retrieve it.

Hawaiian:
- The Keepsake - a stalker has lost his actual brother during their last northern contract before leaving the Zone for good. He wants the contract target back as a memento

Pilot:
- Pilot's PDA - search a stash containing Pilot's PDA in Sarcophagus

Griffin:
- Monolith Plans - search a stash containing Monolith battle plans (limited to norther maps)

Loki:
- Freedom Intel Documents - retrieve the intel documents hidden by one of the Freedom's scouting parties (limited to northern maps) 
 
**From random NPCs:**

Freedom:
- Gambling with Life - kill a healthy bloodsucker using only a knife

Bandits:
- Vengence Amplified - finish-off chimera using an axe (can be damaged by anyone and with any weapon before)

Contributors:<br>
[JohnMcClane161](https://github.com/JohnMcClane161) - Russian translation and typos fix<br>
El_Rosarino - Spanish translation<br>
[Thundard](https://github.com/Thundard) - French translation

v0.4.1a
- Fixed a typo in utils that caused northern map restrictors for intercept task to be omitted 

v0.4.1
- Add invincibility particles to MoTS Baba Yaga
- Add sound hint to Dead Night. Slightly reduce script firing radius to prevent insta-swarm by enemies
- Fix MoTS Barman dialog logic. Create stash task framework.
- Added new stash tasks for Loki, Pilot and Griffin

v0.4.0
- Address many TODOs and fix softlocks in The Living Fire

v0.3.0
- Added Mystery of the Swamps questline

v0.2.1
- Fix minor bugs in The Living Fire for vanilla Anomaly

v0.2.0a
- Add compatibility patch for Demonized's dynamic anomalies artifact spawning

v0.2.0
- Added The Living Fire questline

v0.1.4a
- Fix find_random_stalker edge case that causes CTDs

v0.1.4
- Add Blood-stained Coin (Cashier)
- No Step Back adjustments - switched 2 novice squads for 2 veteran ones and changed the target of the squads to (hopefully) prevent them from always bum-rushing the building
- Add The Keepsake (Hawaiian)
- Made the northern artifact interception (T3 artifacts) quests one-time only by default

v0.1.3
- Add Stolen Specimen task (Sakharov)
- Add Cold-blooded Betrayal task (Sidor)
- Add Shakeup task (Olivius)
- Fix typos and capitalization
- Lay foundations for Outskirts tasks
- Code cleanup (add mini-framework for artifact interception tasks, greatly reducing the size of code)
- Potential fix for silent engine error in Baba Yaga, House of Horrors and Mirage

v0.1.2
- Add Enforce Embargo task (Kuznetsov)

v0.1.1
- Add MCM config for tasks replayability and auto-assignment (currently only one task is auto-assigned)

v0.1.0: There has to be some point where I start versioning it, so why not start right now. At this point the mod introduces 13 new tasks
