# project-feed

Project Feed is an incremental action simulation where you navigate a food chain that never ends. Starting out as a microscopic organism, you consume smaller prey to evolve, and to eventually become big enough to consume the planet. It is a combination of predatory tension with the environmental consumption of a cosmic giant.

## Table of Contents

- [project-feed](#project-feed)
    * [Table of Contents](#table-of-contents)
    * [High Level Vision](#high-level-vision)
    * [Aesthetics](#aesthetics)
    * [Art Style / Theme](#art-style--theme)
    * [Story](#story)
    * [Storyboard](#storyboard)
    * [Core Loop](#core-loop)
    * [Screens, UI, UX](#screens-ui-ux)
    * [Level Schema and Sample Level Design](#level-schema-and-sample-level-design)
    * [Game Economy](#game-economy)
    * [Asset List](#asset-list)
    * [Development Pipeline](#development-pipeline)
    * [Team and Budget](#team-and-budget)
    * [Schedule](#schedule)
    * [References](#references)
    * [Credits](#credits)

## High Level Vision

- A pixel top-down stylized game inspired by Feeding Frenzy, Katamari Damacy and Dingo Games with some elements from Vampire Survivors.
- A game of exponential consumption, predatory evolution, and recursive scale.
- Main platform is PC with mobile port in consideration for the future.
- Business model for this game will be a one time purchase to play forever with optional cosmetic skins for main character.

## Aesthetics

### Sensation

- The act of eating must feel tactile and satisfying. This is emphasized through distinct sound layers that shifts from high pitch towards deep rumbles as you grow in size.
- Particle effects like debris or body parts fly off when successfully feeding to add to visual feedback.
- The main character must display some act of swallowing, similar to Feeding Frenzy's _Gulping_.
<img src="./Media/feeding-frenzy-eat.gif" width="50%">

### Fantasy

- This game features a core "power trip" route of becoming an apex predator of the universe. The contrast of scale must always have a reference object visible. For example, eating what was once bigger than you, and tiny cars fleeing from cities when you are massive.
- As the main character grows in size, there must be some visual development rather than just a bigger blob. Some considerations can be the progression of alien-like to "cosmic". This is so the player feels like they are becoming a legendary entity.

### Submission

- The pace and average playtime of a successful run must be defined (for now about 30 minutes). Vampire survivors feature 30 minute runs with a fast mode to bring it down to 15.  
- The UI must be minimalistic so that the player can focus on the rhythm and movement, of hunting or fleeing.
- As you get massive, consumption becomes passive so that the player can have a movement of "zen" to enjoy the destruction.

## Art Style / Theme

### Rendering Style

3D with pixel shader  
<img src="./Media/x_liquid_owl.webp" width="50%"><img src="./Media/pinterest_daniel_aragon.webp" width="28%">

### Environments

Different levels of scale according to size of main character. Ranges to microscopic to planetary.  
<img src="./Media/pinterest_Xtr4g3dyX_microscopic.jpg" width="25%"><img src="./Media/pinterest_anbinoh_pond.jpg" width="25%"><img src="./Media/pinterest_styca1123323d_forest.webp" width="45%">
<img src="./Media/pinterest_aaa3format_city.jpg" width="33%"><img src="./Media/pinterest_bhuvaneshshan_landscape.webp" width="25%"><img src="./Media/pinterest_fongjisou12_planet.jpg" width="33%">

### Characters

Alien-like entity that grow whenever it consumes.  
<img src="./Media/parasyte-the-maxim-alien.png" width="50%"><img src="./Media/blob.jpg" width="26%">
<img src="./Media/venom.avif" width="50%"><img src="./Media/alien-invasion-rpg.webp" width="50%">
<img src="./Media/carrion.jpg" width="50%">

### User Interface Style

UI style will be minimalistic to increase player immersion and direct focus onto the game world.  
<img src="./Media/hollow-knight-boss.jpg" width="50%"><img src="./Media/a-short-hike-interaction.png" width="50%">

## Story

A spore from outer space drops onto earth. Upon landing, it hatches into a microscopic alien entity. Play as this entity and eat other organisms to grow bigger. Eventually big enough to consume Earth and start releasing spores back out to space, starting the life cycle once again.  

## Storyboard

**TBD**
<!-- <img src="./Media/storyboard1.png" width="100%">
<img src="./Media/storyboard2.png" width="100%">
<img src="./Media/storyboard3.png" width="100%">
<img src="./Media/storyboard4.png" width="100%">
<img src="./Media/storyboard5.png" width="100%">
<img src="./Media/storyboard6.png" width="100%"> -->

## Core Loop

<img src="./Media/core_loop.png" width="100%">

## Screens, UI, UX

<!-- 
A UI that evolves with the main character. Since the character starts from non-threatening and progresses to apocalyptic, the UI should follow that. As for the style, currently it will be minimalistic. It must display size scale, time, and what can be eaten.
font, colors, layout, animations, interactions  
<img src="./Media/tasty_blue_ui.png" width="75%">
<img src="./Media/google_scale_bar.png" width="50%">
-->

## Level Schema and Sample Level Design

**TBD**  
Levels will be procedurally generated.

## Game Economy

Optional costmetic DLC and soundtrack.

| DLC    | Cost (USD) |
| :----: | :---: |
| Skin 1 | $2.99 |
| Skin 2 | $2.99 |
| Skin 3 | $2.99 |
| OST    | $9.99 |

## Asset List

### Main character
| Category | Asset | Description |
| :----: | :---: | :---- |
| Model | Monster | Main character model with animations |
| Sound | Munch | SFX for eating very small organisms |
| Sound | Crunch | SFX for eating smaller organisms |
| Sound | Chomp | SFX for eating slightly smaller organisms |
| Sound | Hit | SFX for  |
| Sound | Bone Break | Occasional SFX for eating humans/animals |
| Sound | Wood Break | SFX for eating trees or wooden objects/structures |
| Sound | Concrete Break | SFX for eating buildings |
| Sound | Metal Break | SFX for eating cars, military vehicles, other other metal objects |

### Microscopic Environment
| Category | Asset | Description |
| :----: | :---: | :---- |
| Background | Microscopic Background | Something to visualize the space. Possibly a solid background color or a leaf under a microscope |
| Model | Acanthamoeba | Looks like a slime. Size is ~12-40μm |
| Model | Bdelloid rotifer | Animal with chainsaw-like mouth. Size is ~150 to 700μm |
| Sound | Rotifer Sound | Chainsaw-like SFX in water |
| Model | Water flea | Looks like a flea. Size is ~1-5mm |
| Sound | Water flea Strike | A kicking motion SFX to pull food into mouth |

### Pond Environment
| Category | Asset | Description |
| :----: | :---: | :---- |
| Background | Freshwater Background | Dark blue background to mimic a pond |
| Terrain | Freshwater Environment | Watery environment on the surface |
| Sound | Water Droplet | General SFX for movement in water with some variation |
| Model | Mosquito Larvae | Neutral animal. Size is about ~1 to 1.5cm |
| Model | Tadpole | Neutral animal. Size is about ~1 to 5cm |
| Model | Mosquito Fish | Preys on mosquito larvae. Size is about ~2.5 to 7cm
| Model | Giant Water Bug | Size is about ~5 to 7.5cm |
| Sound | Giant Water Bug Strike | SFX for Giant Water Bug attack with front limbs |
| Model | Frog | Size is about ~6cm to 13cm |
| Model | Channel Catfish | Biggest monster of the pond. Size is about ~30 to 60cm |

### Forest Environment
**TBD**
| Category | Asset | Description |
| :----: | :---: | :---- |
| Model |  |  |

### City Environment
**TBD**
| Category | Asset | Description |
| :----: | :---: | :---- |
| Model | News Helicopter | Follows the monster around |
| Sound | Helicopter Blades | SFX for spinning helicoptor blades |
| Sound | News Broadcast | News broadcast chatter or noise |

### Continental Environment
**TBD**
| Category | Asset | Description |
| :----: | :---: | :---- |
| Terrain | Mountain | Mountains with variants |
| Model | B2 Bomber | Nuclear bomber |
| Sound | Nuclear Drop | SFX of a dropping nuke |
| Sound | Nuclear Explosion SFX | Boom

### Shaders
| Category | Asset | Description |
| :----: | :---: | :---- |
| Shader | Multi-band Cel Shader | "Toon" shading for standard objects |
| Shader | Outline Shader | Dark outline applied to all objects at Unity's render level |
| Shader | Resolution Downsampling | Post render step to create pixel effect without impacting UI |

### Music
| Category | Asset | Description |
| :----: | :---: | :---- |
| Sound | BGM1 | OST for microscopic scale |
| Sound | BGM2 | OST for pond scale |
| Sound | BGM3 | OST for forest scale |
| Sound | BGM4 | OST for city scale |
| Sound | BGM5 | OST for continental scale |

<!-- ## Community Engagement -->

## Development Pipeline

**TBD**

<!-- ## Risks -->

<!-- ## Integration of Feedback -->

<!-- ## Post-Launch Content -->

## Team and Budget

Jeremy Ng
- Producer
- Game Designer
- Game Programmer
- Game Tester

Budget
- [FEEL](https://assetstore.unity.com/packages/tools/particles-effects/feel-183370) - $30.20

## Schedule

1. Planning and Ideation: `2026-04-20` to `2026-05-04` (2 weeks)
2. Pre-Production: `2026-05-04` to `2026-06-01` (1 month)
3. Production: `2026-06-01` to `2026-07-27` (2 months)
4. Testing and QA: `2026-07-27` to `2026-08-24` (1 month)
5. Post-Production: `2026-08-24` to `2026-12-31` (until end of year)

## References

[A Free Game Design Doc (GDD) Template](https://www.linkedin.com/pulse/free-game-design-doc-gdd-template-david-fox/?trackingId=p8bZP9EonjCr%2FD%2Bp%2FW4FkA%3D%3D)  
[Feeding Frenzy 2](https://store.steampowered.com/app/3390/Feeding_Frenzy_2_Deluxe/)  
[Katamari Damacy](https://store.steampowered.com/app/848350/Katamari_Damacy_REROLL/)  
[Vampire Survivors](https://store.steampowered.com/app/1794680/Vampire_Survivors/)  
[Dingo Games](https://store.steampowered.com/developer/dingogames)  

## Credits
