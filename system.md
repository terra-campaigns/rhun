# Terra System's Rhûn {#system}

This section details how to play **Shadows of Rhûn**, a [The One Ring](https://freeleaguepublishing.com/games/the-one-ring/) inspired *Play by Post* RPG using a forked version of the **Terran Engine v0.6.2**.
The **Terran Engine** is self contained in this section, and will not require reading the [SRD](https://efsalvarenga.github.io/terraSystem/) separately.

#### Taxonomy {-}

- "You"/"Your" are used to refer to players and their characters, interchangeably.
- "Challenge" is used to represent anything that is antagonistic to you, be that an NPC, the environment, etc.
- Meta game concepts, stats and currencies are marked in *italic*.
- Book references are marked in `code`, they might be accompanied by page ranges.

## Characters

1. With the other players, define a cohesive group concept.
2. Always start with a Name and *Archetype*.
3. Roll for *Attributes* and assign points.
4. Roll for *Grit* and *Ego.*
5. Choose one *Advancement.*
6. Make an image.

A text version of the character sheet is available here.

### Archetypes

You are defined by an *Archetype*, which encapsulates your background, concept and role within the narrative.
Each *Archetype* should offer an immediate grasp of your identity and behaviours.
It is expected you will evolve beyond these initial *Archetypes* towards unique narratives.

< ADAPT TABLE BELOW FOR RHUN>

| Archetype      | Description                         | Skill Groups (Optional)    |
| :------------- | :---------------------------------- | :------------------------- |
| **Clergy**     | Spiritual leaders and advisors      | Cultures, Administration   |
| **Bureaucrat** | Administrators and office workers   | Liaison, Administration    |
| **Trainer**    | Coaches and fitness instructors     | Athletics, Administration  |
| **Agent**      | Covert operatives and enforcers     | Violence, Administration   |
| **Coder**      | Programmers and software developers | Technology, Administration |
| **Artist**     | Creators of art and culture         | Liaison, Cultures          |
| **Criminal**   | Illicit operatives and thieves      | Survival, Cultures         |
| **Dilettante** | Jack-of-all-trades and adventurers  | Athletics, Liaison         |
| **Protector**  | Bodyguards and security personnel   | Violence, Liaison          |
| **Disciple**   | Devoted followers and apprentices   | Survival, Liaison          |
| **Fixer**      | Repair experts and mediators        | Technology, Liaison        |
| **Academic**   | Scholars and researchers            | Sciences, Liaison          |
| **Spy**        | Undercover agents and infiltrators  | Survival, Athletics        |
| **Soldier**    | Survivalists and combat experts     | Survival, Violence         |
| **Spacer**     |                                     |                            |
| **Traveller**  | Explorers and navigators            | Vehicles, Survival         |
| **Mechanic**   | Engineers and machine operators     | Vehicles, Technology       |
| **Scientist**  | Researchers and innovators          | Sciences, Technology       |

### Attributes

There are $6$ *Attributes* that you can use to overcome obstacles.

- **Intuition**: track targets, understand creatures, care, survive.
- **Reason**: concentrate, think abstractly, build knowledge.
- **Finesse**: dextrous manipulation, precision, subtle misdirection.
- **Exertion**: apply physical force and power, melee.
- **Attunement**: get in the flow and tune the arcane or technology.
- **Influence**: compel obedience, socialise, influence.

Each *Attribute* has a rating (from $0$ to $4$) that determine how many **Light Dice** to roll when performing *Risky Actions.*
On the character sheet, their ratings are read horizontally.

*Saves* are groupings of two *Attributes* each.

- **Evasion** groups **Intuition** and **Reason**.
- **Fortitude** groups **Finesse** and **Exertion**.
- **Resolve** groups **Attunement** and **Influence**

*Saves* also have ratings (from $0$ to $2$) that determine how many dice to roll in a *Reaction* situation.
On the character sheet, their ratings are read vertically.

#### Determine Attributes  {-}

For each *Save* grouping (**Insight**, **Prowess**, and **Resolve**) roll $1d$ and consult the table below to determine how many *Attribute* points you have to distribute for each.

|                    | $1:3$ | $4:5$ | $6$ |
| :----------------- | :---: | :---: | :-: |
| *Attribute* points |  $1$  |  $2$  | $3$ |

Finally, choose an *Attribute* and assign it an additional point.

In certain conditions, you might permanently lose *Attribute* points, this is discussed in other sections.

#### Example: Scuff's Attributes {-}

![](https://i.imgur.com/bnKfumi.png)


Scuff has an **Attunement** *Attribute* rating of $3$ (read horizontally).
They roll $3d$ when performing a Risky Action related to **Attunement**.
They also have **Influence** $0$ (horizontally), so they roll $0d$ (i.e. no chance if no advantage is found).
If their **Resolve** is challenged, they may roll a *Reaction* with $1d$, based on their **Resolve/Willpower** *Save* rating (read vertically).

### Grit & Ego

> *"It's about how hard you can get hit and keep moving forward"*
> (Rocky Balboa)

While *Grit* represents your disposition, *Ego* represents your resilience to keep pushing.
Roll $1d$ to determine your *Grit* and *Ego.*
Advancements and conditions may change the number of dice you roll.

#### Trauma {-}

You lose *Grit* when you are harmed.
When your *Grit* reaches $0$ you start marking *Trauma* tracks.
You have $3$ *Trauma* tracks: Stressed ($-1d$ **Insight**), Broken ($-1d$ **Prowess**) and Weary ($-1d$ **Resolve**).
When all three *Wound* tracks are marked, you become *Mortally Wounded*.

While *Mortally Wounded* you cannot gather *Light Die* for your *Risky Actions*.
You will die instantly if harmed further, or in minutes if not attended to.
If you survive being *Mortally Wounded*, you develop a *Malaise*.
Roll $1d$ and consult the table below.
With the GM, describe it narratively.

|     | *Malaises*                                                                         |
| :-: | ---------------------------------------------------------------------------------- |
| $1$ | No *Malaise*.                                                                      |
| $2$ | $-1$ **Prowess**, you die if it goes below $0d$.                                   |
| $3$ | $-1$ **Insight**, you die if it goes below $0d$.                                   |
| $4$ | $-1$ **Resolve**, you die if it goes below $0d$.                                   |
| $5$ | When you re-roll your *Ego,* use $-1d$ from now on. You die if it goes below $0d$. |
| $6$ | Re-roll your *Grit* with $-1d$ from now on. You die if it goes below $0d$.         |

After a well fed and rested night, you roll and reset your *Grit* ($1d$).
If you did not rest well you have $-1d$ to roll for *Grit*.
Each *Wound* track recovers through appropriate care and a week's rest.
A *Malaise* never recovers.

#### Pushing yourself {-}

You spend *Ego* when you push beyond yourself in *Risky Actions*.
When your *Ego* reaches $0$ you are lost somehow.
With the GM determine how your last scene goes.

< ADAPT BELOW FOR RHUN>

Any time you *Fail* in a *Risky Action* you may choose to suffer a **Panic Event**.
When you do so, roll your Ego die ($1d$) and consult the table below.

|       | Outcome                                                                                  |
| :---: | ---------------------------------------------------------------------------------------- |
| $1:3$ | Reset your *Ego* to $1:3$. You **Flight**, compelled to leave the scene.                 |
| $4:5$ | Reset your *Ego* to $4:5$. You **Freeze**, silently or otherwise.                        |
|  $6$  | Reset your *Ego* to $6$. You **Fight**, obsessed with being successful during the scene. |

Describe the outcome narrativelly.
In any case, after the scene ends, you gain a *Condition*.
With the GM, determine the mechanical effects and how to introduce your *Condition* into the narrative.

#### Example: Scuff's scuffs {-}

![](https://i.imgur.com/IYdZoZh.png)


Scuff has $1d$ for both *Grit* and *Ego* (usual for early characters).
They have seen some harm, having lost $3$ *Grit* (from $5$ to $2$) and taken a **Hazed** wound.
This means that any time they roll related to **Insight** (**Intuition** or **Reason** for *Risky Actions*, or **Evasion** *Reaction*), they take $-1d$.

Scuff also risked their *Ego* a few times, and took a **Condition** to reset it (from 2 to 4).
Finally, they have gotten a malaise at some point, having reduced their **Exertion** *Attribute* rating because of a weakened lower back.

### Advancements

As you become more seasoned, you gain *Advancements*.
You start the game with $1$ *Advancement*.
The list below are examples of a simple framework for their in-game mechanics.

For every session you play (and survive) you gain $+2$ *Experience*.
You also gain $+1$ *Experience* for each new *Condition* you develop.

Whenever it is narratively coherent, you may spend *Experience* equal to $2\times$ your current number of *Advancements* to gain a new one.

< ADAPT TABLE BELOW FOR RHUN>

|                |                                                                                            |
| -------------- | ------------------------------------------------------------------------------------------ |
| Asceticism     | You do not take $-1d$ when rolling for *Grit* while poorly fed.                            |
| Assassin       | $+2d$ when trying to assassinate an unaware rival.                                         |
| Bodyguard      | You can choose to take damage instead of one of your allies.                               |
| Could be worse | When **Broken** you do not take the penalty of $-1d$.                                      |
| Danger sense   | $+1d$ whenever you use a **Insight/Evasion** *Save*.                                       |
| Developed      | Gain $1$ in an *Attribute*. The maximum you can have in all *Attributes* together is $10$. |
| Die Hard       | When you reset your *Grit*, roll $+1d$ and sum all the dice you rolled.                    |
| Eager          | When you reset your *Ego*, roll $+1d$ and keep the highest.                                |
| Fast           | When you roll, your *Effect* is always applied first.                                      |
| Healer         | You can automatically stabilise a *Mortally Wounded* ally.                                 |
| Henchkeeper    | You automatically succeed acquiring non-combatant henchmen in a community.                 |
| Ironhide       | When unarmoured, your **Armour** is $1$.                                                   |
| Sensory acuity | You have $+1d$ on noticing things through a chosen sense.                                  |
| Sleek          | $+1d$ whenever you contort yourself to to break free.                                      |
| Unyielding     | When **Weary** you do not take the penalty of $-1d$.                                       |
| Whirlwind      | In melee combat, when you are successful, select an additional die as a second effect.     |

### Conditions

*Conditions* are detrimental mechanically, but not necessarily negative in the narrative.
The list below can be used as a starting point.
With the GM you can adapt these or create new ones.

< ADAPT TABLE BELOW FOR RHUN>

- **Fear-Driven Vigilance**: Fear instills a heightened sense of vigilance, making you more cautious. In situations related to the your fear, you have $-1d$
- **Obsessive Focus**: Your single-minded pursuit leads to significant personal development and expertise in a specific area, in detriment of others. Gain $+1$ Point in one *Skill* and $-1$ Point in two other *Skills*.
- **Moral Reservations**: Your steadfast morality leads to a firm stance on certain issues. Actions that go against your moral code have $-1d$.
- **Compulsive Honesty**: You vow to always speak the truth.
- **Kleptomaniac**: You are unable to resist urges to steal items that you generally don't really need.
- **Battle-Scarred**: After some injury, you develop a scar. You might have lost part of a member, an eye, or something else that impacts you physically, intellectually or socially.
- **Protective Instinct**: You are genuinely concerned with your team's welfare, and become a reluctant leader. When an ally is in danger, you have $-1d$.
- **Estranged**: You lose the bond with someone you love or cherish. With the GM, agree the mechanical impact.
- **Slow**: When you roll, your *Effect* is always applied last.

### Equipment 

The following is a list of equipment tags. 

|     Tag     | Description                                       |
| :---------: | ------------------------------------------------- |
|    $-1d$    | **Improvised**                                    |
|    $-1e$    | **Inefective**: Disadvataged *Effect* is applied. |
| $\emptyset$ | **Base**: No modifications.                       |
|    $+1e$    | **Effective**: Advantaged *Effect* is applied.    |

The table below contains example weapons, and may be expanded with the GM.
For ranges, use what is narratively appropriate.

|    Tags     | Melee Examples               | Ranged Examples      |
| :---------: | ---------------------------- | -------------------- |
|    $-1d$    | **Unarmed**                  | Throwing **Objects** |
|    $-1e$    | Small **Knives**             | Throwing **Knives**  |
| $\emptyset$ | Short **Swords** & **Maces** | Short **Bow**        |
|    $+1e$    | Long **Swords** & **Lances** | Long **Bow**         |

Armours act as buffers when you take damage from *Challenges*.
Subtract the armour modifier from the *Effect* before reducing your *Grit*

| Armour     | Modifier | Details                                            |
| ---------- | :------: | -------------------------------------------------- |
| **Light**  |   $-1e$  |                                                    |
| **Heavy**  |   $-2e$  | $-1d$ to run, observe, sneak, swim, etc.           |
| **Shield** |   $-1e$  | Can be sacrificed to completely avoid an *Effect*. |

## Rules

### Risky Actions

When you are trying your chances at a *Risky Action*, say what you intend to do.
With the GM determine your appropriate *Attribute* or *Save*.
Then gather 6-sided dice.

|                                | Dice Pool                                                                                                                                                                                                |
| :----------------------------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![](imgs/dice-light-6-sml.png) | Take a number of **Light Dice** equal to your applicable *Attribute* or *Save*. Relevant *Advancements* / *Conditions* may give you $\pm 1d$. You must always roll between $0d$ and $4d$ **Light Dice**. |
| ![](imgs/dice-dark-6-sml.png)  | Take as many **Dark Dice** as you wish to risk *Ego* for pushing yourself for a success. For each **Dark Die** that rolls equal or lower than your current *Ego*, decrease your *Ego* in one.            |

Roll the dice and choose one die to be your *Precision* (generally the highest, but you might choose differently if you wish) and consult the table.

|       | Outcome                                                                                                                                                     |
| :---: | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| $1:3$ | You *Fail*, and things get worse. With the GM describe the consequences. The GM may also allow you to succeed, but things will get worse in some other way. |
| $4:5$ | You *Succeed*, but there’s some consequences. If applying *Effects*, they are halved. With the GM describe the complication and how you succeed.            |
|  $6$  | You *Succeed*. With the GM describe what happens.                                                                                                           |

*Risky Actions* may be used when you are working on something time consuming.
This favours pacing of the game.

### Challenges

Sometimes, multiple actions are required to overcome *Challenges*.
Examples of *Challenges* are

- fighting an enemy,
- duelling rhetorically,
- negotiating an environment,
- crawling a location,
- journeying.

#### Effects {-}

*Effects* determines the quantitative result of your *Risky Actions* towards overcoming *Challenges*.
Examples of *Effects* are:

- Damage given,
- Convincing done,
- Distance covered,
- Weakness learned.

When you roll your *Risky Actions*, choose one die to be your *Effect* (generally the second highest, if the highest was used as *Precision*).
The *Effect* die is an exploding die (i.e. if the result is a $6$, keep rolling and accumulating the result).
The *Effect* is modified depending on the approach you take.
Your *Effect* is subtracted from the *Challenge* **Disposition**.

|                             | Approaches                                                 |
| :-------------------------- | ---------------------------------------------------------- |
| $-1e$<br>**Disadvantaged**  | Primitive tool<br>Weak argument<br>Small weapons           |
| $\emptyset$<br>**Baseline** | Fit for purpose tool;<br>Good argument; <br>Medium weapons |
| $+1e$<br>**Advantaged**     | Expert grade tool<br>Strong rationale<br>Large weapons     |
#### Tiers {-}

*Challenges* are divided in **Tiers**, which define how much *Effect* they take to be overcame (**Disposition**), and how many *Effect* dice they use (**Dice**).

|                 | Tier           | Examples                                                             |
| --------------- | :------------- | -------------------------------------------------------------------- |
| **Trivial**     | $1$<br>$d/2$   | Unskilled adversaries, low height climb, known journey               |
| **Dangerous**   | $5$<br>$1d$    | Skilled adversaries, small predator, large prey, troublesome journey |
| **Serious**     | $10$<br>$2d$   | Expert adversaries, large predator, traverse fire or acid            |
| **Formidable**  | $15$<br>$3d$   | Human prime, apex predator, climbing the Everest                     |
| **Exceptional** | $20+$<br>$4d+$ | Transhuman, often fatal environments, heroic journeys                |

Some challenges might be multifaceted.
A bulky rival might be a Dangerous *Challenge* to fight against, but a Trivial *Challenge* to be convinced to ignore you.

When *Challenge Effects* are applied to you narratively, use the table.

|       | Consequence                                                   |
| :---: | ------------------------------------------------------------- |
| $1:3$ | Something annoying happens. An uncertain encounter.           |
| $4:5$ | Something troublesome happens. An unfriendly encounter.       |
| $6+$  | Something devastating happens. A hostile encounter.           |
| $12+$ | $6+$ and immediately harmful. A hostile and violent encounter |

When *Challenge* *Effects* are applied to you as damage your *Grit* might be reduced.
Subtract the armour rating from the *Effect*, and then reduce the remainder from your *Grit*.

When you reduce a *Challenge*'s **Disposition** to $0$, you have defeated it for now.
If the *Challenge* is sentient, and has a choice, the GM might roll its **Dice** and consult the **Morale** table below.

|       | Morale                                                                                                |
| :---: | ----------------------------------------------------------------------------------------------------- |
| $1:3$ | They give up.                                                                                         |
| $4:5$ | They push through, with a lower **Tier**. Reset its **Disposition** and **Dice** to the new **Tier**. |
| $6+$  | They continue with the original **Tier**. Reset its **Disposition**.                                  |

#### Consequences {-}

The following is a non-exhaustive list of consequences.

- Advance trouble
- Reveal an unwelcome truth
- Ask a provocative question
- Put someone on a spot, worsen position or stress
- Use up their resources
- Remove a safety net, cut supply or connection
- Remove a sense
- Hurt someone, directly or collateral
- Separate them
- Capture someone
- Turn their action back on them
- Demonstrate a downside
- Expose a secret
- Offer an opportunity (with a tough choice)
- Tell them the consequences (e.g. create a witness)
- Advance a countdown, progress a new challenge
- Increase risk (roll morale)
- Exploit someone's flaw
- Change the environment
- Provide a choice of paths
- Bar the way, make them go backward
- Hint at more than meets the eye
- Present a discovery
- Point to a looming danger
- Introduce person, faction, danger
- Offer riches at a price

### Fortune die

When the GM wants to leave some decision to the dice, determine the chances and roll $1d$.

### Sayonara

At any moment you can decide it is your last scene.
When you do that, choose a song and then re-roll your *Ego* and *Grit*, keeping the highest values.
For this scene, you only expend *Ego* if you roll a $1$ on **Dark Dice**.
By the end of the scene, you have to figure out how you depart (death, madness, mission, etc.).
You can create a new character with half (rounded up) the number of *Advancements* the previous character had.
