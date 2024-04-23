---
title: "Prototype"
weight: 9
---

## Version 1.0.0

```goat
   .--------------.     .------------.      .--------.                                
   | Start Screen +--->| First Level  +--->| Game End +-----.   
   '--------------'     '------------'      '--------'       |
         ^                                                   |
         '--------------------------------------------------' 

```
## Version 2.0.0
```goat
   .--------------.     .-------.      .------.      .--------.                                
   | Start Screen +--->| Level 1 +--->| Boss 1 +--->| Game End +-----.   
   '--------------'     '-------'      '------'      '--------'       |
         ^                                                            |
         '-----------------------------------------------------------' 

```
## Version 3.0.0
```goat
   .--------------.     .-------.      .------.      .-------.      .------.      .--------.                                
   | Start Screen +--->| Level 1 +--->| Boss 1 +--->| Level 2 +--->| Boss 2 +--->| Game End |   
   '--------------'     '-------'      '------'      '-------'      '------'      '----+---' 
         ^                                                                             |
         '----------------------------------------------------------------------------' 
```
## Version 4.0.0
```goat
   .--------------.     .----.      .-------.      .------.      .----.      .-------.      .------.      .--------.                                
   | Start Screen +--->| REST +--->| Level 1 +--->| Boss 1 +--->| REST +--->| Level 2 +--->| Boss 2 +--->| Game End |   
   '--------------'     '----'      '-------'      '------'      '----'      '-------'      '------'      '----+---' 
           ^                                                                                                   |
           '--------------------------------------------------------------------------------------------------' 
```
## Version 5.0.0
```goat
                                                                              .-------.      .------.     
                                                                        .--->| Level 2 +--->| Boss 2 +---.
.--------------.     .----.      .-------.      .------.      .----.    |     '-------'      '------'     |     .--------.     
| Start Screen +--->| REST +--->| Level 1 +--->| Boss 1 +--->| REST +-->|                                 +--->| Game End |
'------+-------'     '----'      '-------'      '------'      '----'    |     .-------.      .------.     |     '----+---'
       ^                                                                '--->| Level 2 +--->| Boss 2 +---'           |
       |                                                                      '-------'      '------'                |
       |                                                                                                             |
       '------------------------------------------------------------------------------------------------------------' 
```
## Version 6.0.0
```goat
                                                .-----.    .----.     
                                            +--+ Level +->| Boss +-+
                                           /    '-----'    '----'   \ 
                                          /     .-----.    .----.    \
                                         +-----+ Level +->| Boss +----+                           .
                                        /       '-----'    '----'      \                         / \       
.--------------.           .----.      /        .-----.    .----.       \      .-----------+    /   \            .--------.
| Start Screen +-------*--+ REST +--->+--------+ Level +->| Boss +-------+--->/ Increment /--->+Done?+-- YES -->| Game End |
'------+-------'       |   '----'      \        '-----'    '----'       /    '-----------+      \   /            '----+---'
                       |                \       .-----.    .----.      /                         \ /
                       |                 +-----+ Level +->| Boss +----+                           +
                       |                  \     '-----'    '----'    /                            |
                       |                   \    .-----.    .----.   /                             NO
                       |                    +--+ Level +->| Boss +-+                              |
                       |                        '-----'    '----'                                 |
                        '------------------------------------------------------------------------'
```

> In the context of a GDD, this might refer to simple paper prototypes—and gives me another excuse to link to Stone
> Librande's fantastic [one-page designs resource](https://www.gamedeveloper.com/design/video-one-page-designs),
> particularly his examples from The Simpsons, where he used paper and cardboard to create essentially a level design
> prototype for the sprawling game.

> Paper prototypes can be incredibly useful in solving design problems before spending too much time or money cooking
> them
> up in-engine—but they do still take up effort, of course.

> Another use for a prototyping section in your GDD is a dedicated area for proposing prototype ideas: you might list
> out
> mechanics you want to prioritize here and plan to build prototypes for particularly unproven or unique ideas or twists
> on mechanics. If you are creating a platformer where the core character is somehow bolted to a merry go round, and
> experiences the game world in a state of constant rotation, you may want to build out some simple prototypes for basic
> movement before you get to, say, minigame mechanics.
