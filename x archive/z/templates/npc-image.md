---
obsidianUIMode: preview
Race: dwarf
Class: fighter
Perception: "1"
Investigation: "2"
Insight: "3"
Gender: male
Age: "14"
Home: land
Party: party on
NoteIcon: npc
Campaign:
---
````col
```col-md
flexGrow=4
===
## Overview
**Primary Goal |** How does the primary goal influence their interaction with the PCs?
**Unique Trait or Flaw |** How will the PCs remember them?
**Story Connection |** How will they impact the main story?
```
```col-md
flexGrow=1
===
> [!npc|no-t no-i right color-red background-red] NPC
> ># `=this.file.name`
>![[`=this.file.name + ".png"`|cover hsmall]]
>[[NPC-image-placeholder.png|Show To Players]]
>###### Basic Information
>Type |  Stat |
>---|---|
>Race | `=this.race` |
>Class | `=this.class` |

>###### Passive Skills
>Type |  Stat |
>---|---|
>Perception | `=this.perception` |
>Investigation | `=this.investigation` |
>Insight | `=this.insight` |
>

>###### Other Info
>Type |  Note |
>---|---|
>Gender | `=this.gender` |
>Age | `=this.age` |
>Home | `=this.home` |
>Party | `=this.party` |

```
````
