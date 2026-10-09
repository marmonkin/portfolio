# Maksim Vlasov — Gameplay Programmer

[![itch.io](https://img.shields.io/badge/itch.io-marmonkin-FA5C5C?style=flat-square&logo=itchdotio&logoColor=white)](https://marmonkin.itch.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Maksim_Vlasov-0A66C2?style=flat-square&logo=linkedin&logoColor=white)]([LINKEDIN URL])
[![Email](https://img.shields.io/badge/Email-Contact_me-555555?style=flat-square)](mailto:[EMAIL])

Game development student at KAMK (Kajaani University of Applied Sciences), Finland. I build gameplay systems in Unity and Godot with a focus on mechanics that are easy to extend, and I contribute to design on every project I work on, from core mechanics to full design documentation.

My eye for design comes from Dark Souls: I pay attention to how small details like level architecture and item descriptions carry a game's world, and I build systems that leave room for that kind of content.

- **Tech:** Unity (C#), Godot ([GDScript / C#])
- **Also:** Game design, design documentation, client communication

---

## Spaceship Cannoneer

<img src="Screenshots/LogoWarLost2_kopio.webp" width="170">

[![Play on itch.io](https://img.shields.io/badge/Play_on-itch.io-FA5C5C?style=for-the-badge&logo=itchdotio)](https://realkam1.itch.io/spaceship-cannoneer)

| Role | Engine | Team | Duration | Client |
|---|---|---|---|---|
| Gameplay Programmer, Design Lead | Godot | 4 people | [X months] | [Kalla Gameworks](https://www.kallagameworks.com/) |

An atmospheric first-person strategy game: you command a giant spaceship lost deep in enemy territory, and the only way to survive is to manage your cannons and hold off the waves of enemies closing in. Built as a demo prototype for an external client, Kalla Gameworks, to present to one of their partner companies. Released on itch.io for Windows and Linux in April 2026.

**Systems I built**
- **Holographic map:** tile functionality, map enemies, cannon tile targeting and shooting, VFX implementation
- **Exterior cannon sync:** cannon visuals outside the ship stay synchronized with the map
- **Cannon status screen:** full screen functionality

These systems depended on features two other programmers were building at the same time, in an engine none of us had much experience with. We planned the integration points ahead so each part could plug in as soon as it was ready.

**Design and production**
- Led design decisions on gameplay mechanics and visual style
- Acted as the team's contact with the client; our only brief was an old GDD for a different game, so we met regularly to agree on changes and direction
- Wrote all design documentation

<!-- Add a code snippet here, e.g. the cannon targeting logic, or a GIF of the map in action -->

<img src="Screenshots/Screenshot_1.png" width="600"> <br>
<img src="Screenshots/Screenshot_2.png" width="600"> <br>
<img src="Screenshots/3.png" width="600">

---

## Strung Flowers

<img src="Screenshots/ZbldLd.png" width="170">

[![Play on itch.io](https://img.shields.io/badge/Play_on-itch.io-FA5C5C?style=for-the-badge&logo=itchdotio)](https://sokifin.itch.io/strung-flowers)

| Role | Engine | Team | Duration |
|---|---|---|---|
| Gameplay Programmer, Designer | Unity | 10 people | [X months] |

A roguelike deckbuilding dice game: gamble your way out of hell by beating Satan's underling at dice three times, then face Satan himself. Special dice from the shop improve your odds, but you pay for them with your own health. Released on itch.io with ~5k views and 288 downloads as of April 2026.

**Systems I built**
- **Dice:** side detection and score numbers. Built for expandability: a new die is created by duplicating the base die, applying a texture and setting its side values.
- **Shop labels:** automatically assign price, name and texture to the die for sale, so new dice can easily be added to the shop. My favorite feature of the project, because it works so well with every die.

<img src="Screenshots/gaming.png" width="603">
<img src="Screenshots/shoppe.png" width="602">

**Design**
- Designed dice functionality, dice names, the gameplay loop and enemies together with the team
- Wrote all project documentation

<!-- Add a code snippet here, e.g. dice side detection -->

---

## DumbshoW

<img src="Screenshots/spr_mask_strip6.png" width="170" style="image-rendering: pixelated;">

[![Play on itch.io](https://img.shields.io/badge/Play_on-itch.io-FA5C5C?style=for-the-badge&logo=itchdotio)](https://marmonkin.itch.io/dumbshow)

| Role | Engine | Team | Duration | Event |
|---|---|---|---|---|
| Programmer, Co-designer | Godot | 2 people | 2 days | Global Game Jam [YEAR] |

An arcade survival game: dodge the deadly mask, throw boxes to stun enemies, and turn the mask against them to survive as long as you can. We came up with a highly replayable concept, built a working prototype in two days, and left room to expand it with more mechanics later.

**Systems I built**
- **Player:** movement, box throwing
- **Enemies:** movement and AI, getting stunned by boxes, dying
- **Boxes:** all box behavior and interactions

**Design**
- Co-designed the core mechanics, gameplay and visual style

<img src="Screenshots/Screenshot_20260409_203226.png" width="606">

---

More projects on [my itch.io page](https://marmonkin.itch.io/).
