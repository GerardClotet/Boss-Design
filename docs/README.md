“I am [Gerard Clotet](https://www.linkedin.com/in/gerard-rodriguez-054176176/), student of the Bachelor’s Degree in Video Games by UPC at [CITM](https://www.citm.upc.edu/ing/estudis/graus-videojocs/). This content is generated for the second year’s
subject Project 2, under supervision of lecturer [Ricard Pillosu](https://es.linkedin.com/in/ricardpillosu).”

# Boss Design

## What is a Boss?
A Boss is an extension of an enemy. A boss block the player progression and acts as the climax of the end game/level/environment.  A good boss should always test the player is some unique aspect, the boss fight should be visually and gameplay distinctive from the rest of the level or the enemies the player has fight but in a way related to them


## What should I consider to design a boss?
Sadly there isn’t a boss bible, but here are some of the most relevant aspects about boss designing.


### Boss Patterns
When we talk about the enemy patterns, we talk about how the enemy will decide and attack the player.  The pattern design is splitted in two types, fixed and random patterns 

#### Fixed Pattern:
Fixed patterns means that the boss is designed around one pattern or a repeated set of patterns. As a result the boss ends up being a puzzle and the player has figure it out (know his pattern) to defeat the boss.  The enemy will perform the same attack at the same rate every time you fight it.

Once the player figures out the pattern, the boss fight is not challenging anymore and the boss become an enemy with more health, the tension stop increasing. 
In boss design fixed patterns are the easiest way to design the enemy, although it limits the replayability of the game. When the player know the pattern the fight it’s reduced to wait the end of boss’s pattern, destroying the wall that differentiates normal enemy’s from bosses. 

![Fixed Pattern](https://github.com/GerardClotet/Boss-Design/blob/master/docs/Fixed%20Pattern.png?raw=true)

#### Random Pattern:
Random Patterns means that the boss instead of using the same unchangeable patterns will choose it during the fight. Keep in mind that patterns are limited by developers, the move set is always the same what changes it’s his combination.

The pattern may be completely random, be attached to some conditions or both. Imagine the boss has 4 types of attack.  A completely random pattern will make random combinations of those. 

On the other side the combinations will be decided by the fight events and stats like the health of the player or the boss(known as boss phases), the distance between them, the position in the fight area (may trigger some optional event/attack during fight) or the gameplay style. 

An example of the gameplay style conditioning is the amount of moves the player does during the fight. The game give the player the option to block or evade to defend himself from the boss. If the player abuse from one option the boss will use an attack to penalize the player, like extend the pattern to hit the player while his trying to evade or repeat the same attack to break his block.
In random patterns the player is required to be more reactive and focused during the fight compared to fixed patterns. For the players random patterns are more challenging but they require a huge effort to design and balance.  As a player, you have so many attacks to deal with that you have to be consistently focused on the fight.



#### Balancing random patterns
Pattern for boss design does make things harder when it comes to balance. The difficulty of any random pattern boss comes down to the number of attack that the player must take into account, and how frequent the enemy will use them.

The cool-down between attacks, as well as being able to stun or knock the opponent out of an animation, are vital elements of balance and difficulty. As a designer, you need to keep a careful eye on how hard and unpredictable it is to fight a boss.

As we talked about with variance in replayability, you never want the game to devolve into one build or one strategy that always works. You can also adjust the overall difficulty curve of your game by making the starting bosses have longer cool-down periods.


#### Planning a Pattern:
The type of game and audience you are designing for will determine the kind of bosses that make the most sense.
If your game pillars are not combat or player skill-focused, then you should use fixed patterns. 
If your game’s combat system is detailed enough and you want to give the player a challenge, then a random pattern is the best fit.


### Value of Effort
Value of Effort is the gameplay experience of that one's efforts during gameplay have value. Challenging gameplay is a must if we want the player feels he deserve the reward after the fight. The most common way to achieve this experience is using Setback Penalties during the boss fight. For example if the player passes through the middle of the fight but dies, give him the chance to start from the beginning or the checkpoint but penalize the player with a lower reward if he has choosed the checkpoint. Lastly the player always has to administer the coup de grace to feel the victory as his own.

### Goals
Goals help directly players attention and efforts in a game.  Goal Indicator as a live bar, time to end or lives. Although it’s not a must, for example Cup-Head doesn’t use any goal indicator although the player can check the goal status through the boss phase. 

![LifeBar](https://github.com/GerardClotet/Boss-Design/blob/master/docs/lifebar.jpg)


### Varying Rule Sets
Varying Rule Sets change in a specific boss fight to then back to the original ones. For example the player is immortal, to advance you have to die, magnify the abilities. The variation of the rules increases the boss feeling as a unique enemy.

### Varied Gameplay
Varied gameplay must be reflexed in boss fights. If the game offers different ways to achieve the goals during the whole game, this must be reflexed in the boss fight. Even though the limitation of actions during the fight can be justified through the narrative. A good gameplay variety promotes replayability.

### Balancing Effect
Balacing effect try to correct imbalances when they occur. If the player dies several times trying to defeat the boss indirectly the game increases his damage, reduces boss health or damage. If this changes are visible for the player, the meaning of the fight is reduced, it’s essential that the player don’t notice that balance otherwise it will remove feeling of gameplay mastering and value of effort. On the other side, if the balance is huge the tension disappear. The balance can only be achieve by play-testing

### Clues
Clues are game elements or information that instruct players how his goals can be fulfilled.  Indirectly bosses should give clues to the player about how they can be defeated, through its animation which has a cooldown where is vulnerable and the player is sure he won’t have any penalty if attacks the boss. Also by some part of his body that is visually relevant  called Achilles Heel, or an event in the fight-area indicated to the player by the UI. Clues are strongly related to Vulnerabilities.

### Vulnerabilities
Vulnerabilities are weaknesses that can be exploited by the player. Those are related to the balancing of the game. Often called Achilles Heel, the boss is susceptible to some kind of damage or a certain area of his body is unprotected.

### Invulnerabilities
Invulnerabilities are used to imbalance the game in case it is too easy for the player.  Usually used in RPG games, the designer must decide the kind of invulnerability. Careful, invulnerabilities can destroy the game pillars or frustrated the player and dissipate the value of effort.

Classic JRPG like Final Fantasy or Dragon Quest abuse from invulnerabilities, the game  gives the player a wide range of possibilities during fights, debuffs like burned or confusion apart from the direct damage, so the player construct his gameplay strategy around this possibilities. The 90% of boss fights the boss is immune to any ability apart from direct damage,  the player realizes that despite all the possibilities there is only one to defeat the boss. This breaks the game mechanic and frustrates the player, which sees that in fact there’s only one way to defeat the boss. This bad design affect the replayability of the game and the value of effort after each fight. 

![InvulnerabilityJRPG](https://github.com/GerardClotet/Boss-Design/blob/master/docs/Invulnerability.png)

### Tension
The tension is the feeling of caring about the outcome of actions or events in a game without having full control over them. The tension is generated because the player has something to loose during the fight. Like the progress achieved in the game or  the resources earned. Tension can be increased by making gameplay actions more difficult to the players, perform actions quickly (stress the player) for example quick time events or temporary abilities. Repeated exposure to the same form of events or actions decreases the Tension they cause, it is related to the pattern set of the bosses a random pattern will produce more tension than the fixed one. The tension is also related to the value of effort, as the challenge increases the reward after the fight must increase otherwise the player will feel cheated. 

![Tension chart](https://github.com/GerardClotet/Boss-Design/blob/master/docs/TensionChart.jpg?raw=true)

### Penalties
Penalties are effects on the game state that are negative to players regarding their position, progress, or abilities. To maintain the tension during the fight the player have to know what he is facing if he loses so they have to be introduced since the beginning of the game. The target audience of the game will dictate the kind of penalties


### Thematic Consistency
The boss must have a believable behavior, the key is transition. If a boss uses attacks completely unrelated to both the theme and enemies found earlier in the level, it will feel unattached (and so will the player). The boss esthetic must fit in the world that has been presented to the player, an exception of this are Easter Eggs bosses because those are presented to the player as an extra content out of the universe. The types of attacks don't necessarily have to mimic the same enemy types seen earlier in the level, but they shouldn't be so different that the boss and level feel separated in function. You can also have the boss use weapons/moves that won't be seen until the next level.

![Thematic Consistency](https://github.com/GerardClotet/Boss-Design/blob/master/docs/ThematicConsistency.jpg)

### Emotionally Weight
The goal to defeat bosses must fit in the thematic presented to the player. It can’t be just meet the boss and fight, there’s the need of some kind of background to make the fight unique and memorable, otherwise it’s just another regular enemy. 

### Difficulty
At what point of the game is your boss? If it’s at the beginning you want to make sure it’s easy enough that the player passes through without dying too much. On the other hand the more you advance harder it gets, obviously. The point here is that there’s no clear rule about the difficulty of the boss, it depends on his position in the game story and the target of the game. It is directed to casual gamers? Then the penalties or the balance should be softer than hardcore target games like Dark Souls.

![DifficultyChart](https://github.com/GerardClotet/Boss-Design/blob/master/docs/TimeVSDifficultyProgression.png?raw=true)

### Battle Length
Battle length should last a fraction of the previous level, I repeat there is no boss bible but the ideal time would be between a quarter and a fifth length of the level. Battle length is really important to maintain tension and not saturate the player. The time can be easily modulated by the boss health or the damage done by the player. It is really important to have the time measured to fit the music properly. The time measure can only be achieved with a lot of playtesting.

### Boss Checklist
It’s important to have this document, due to you won’t be working alone in the boss design and develop all the team workers involved in this field should know exactly what you have in mind. It will also end up as a reference bible for the rest of the team and it can’t solve many issues and save lot of time.

- Boss name, image and short description 
- Level description of the environment.
- Animation list 
- List of attacks, description and moveset patterns
-Special player code requirements for the fight.
- List of effects and projectiles
-List of music and FX 


## What means a boss for the player? 
Bosses serve as a way to change up the pace of the gameplay and offer a break from any repetitive game mechanics during the game. 

Bosses must feel as a reward to his effort throughout the game. 
Also as goal, at the end of the boss fight the player must feel that he advanced somehow. It can be through new mechanic implementation, gameplay mastering, advancing in the narrative, new zone, you name it. 

## Boss as a skill test
A final boss should be used to prove the player his gameplay mastering overall game exploiting all the mechanics the player has learned throughout the game. 

The side bosses should be testing a specific mechanic or dynamic learned in the boss level/game chapter, especially if the difficulty increases. A boss is a wall between two different difficulty levels, ensuring that the player is ready to advance. Otherwise the player would be exposed to a new difficulty level without any previous preparation and it would led to frustration. 

Keep in mind that each remarkable difficulty increase should be divided by a boss. 

## Bosses & Levels
The environment should be influenced by the fight or the boss personality so the player can relate the place to the boss there must be a thematic consistency in other words the environment needs to match the boss. For example, if the boss is some lunatic the place should be all a mess with elements that reinforce the boss personality.  

Also the arena should have some elements to develop the fight like pillars to block attacks , stealth path to surprise the enemy, you name it. Those can be presented as clues and vulnerabilities. 
Levels can be centered in a Boss when it’s a final level, so the whole level is designed specifically to the final battle. 
![Arena](https://github.com/GerardClotet/Boss-Design/blob/master/docs/bossarena.jpg)

## Boss themes
Music is the key to immersion, any memorable boss-fight has a great theme behind. First of all you need to know the battle length to structure the music in phases with a crescendo to the fight climax. To fulfill the immersion the rhythm must mimic the gameplay. The music must reinforce the feeling that has been designed to this fight. The music should also fit with the environment presented; a gloomy environment won’t fit with Minecraft main theme. 

## Bibliography
- [Penalties](http://virt10.itu.chalmers.se/index.php/Penalties)
- [Value of Effort](http://virt10.itu.chalmers.se/index.php/Value_of_Effort)
- [Goal Indicators](http://virt10.itu.chalmers.se/index.php/Goal_Indicators)
- [Check Points](http://virt10.itu.chalmers.se/index.php/Check_Points)
- [Varying Rule Sets](http://virt10.itu.chalmers.se/index.php/Varying_Rule_Sets)
- [Varied Gameplay](http://virt10.itu.chalmers.se/index.php/Varied_Gameplay)
- [Complex Gameplay](http://virt10.itu.chalmers.se/index.php/Complex_Gameplay)
- [Balancing](http://virt10.itu.chalmers.se/index.php/Balancing_Effects)
- [Tension](http://virt10.itu.chalmers.se/index.php/Tension)
- [Clues](http://virt10.itu.chalmers.se/index.php/Clues)
- [Thematic Consistency](http://virt10.itu.chalmers.se/index.php/Thematic_Consistency)
- [Challenging Gameplay](http://virt10.itu.chalmers.se/index.php/Challenging_Gameplay)
- [Vulnerabilities](http://virt10.itu.chalmers.se/index.php/Vulnerabilities)
- [Invulnerabilities](http://virt10.itu.chalmers.se/index.php/Invulnerabilities)
- [Boss Monster](http://virt10.itu.chalmers.se/index.php/Boss_Monsters)
- [Creative Process](
https://www.vix.com/es/btg/gamer/64011/el-diseno-de-los-jefes-finales-el-proceso-creativo-detras-de-tan-frustrantes-enemigos)
- [Boss Patterns](https://www.gamasutra.com/blogs/JoshBycer/20180531/319068/The_Evolution_of_Boss_Designs_in_Video_Games.php)
- [Balancing rpgs](https://gamedevelopment.tutsplus.com/articles/balancing-turn-based-rpgs-the-big-picture--gamedev-8286)
- [RPG boss battle design](http://game-wisdom.com/critical/rpg-boss-battle-design)
- [Boss Check PPT](http://mrbossdesign.blogspot.com/2008/02/how-to-create-greatest-boss-battle-and.html
)
- [Modern Games](https://gamedevelopment.tutsplus.com/tutorials/designing-a-boss-fight-lessons-learned-from-modern-games--gamedev-2373)
- [Music](https://www.gamasutra.com/blogs/HarryMack/20120413/168521/GettingMaking_Game_Music_that_Fits__Classic_Genre_Series__Boss_Music.php)
-[Emotional Weight](http://game-wisdom.com/critical/3-boss-fight)

