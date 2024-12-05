---
title: Ability Hotbar Cycler
description: Simple ability hotbar cycler
parent: UI
grand_parent: Quality of Life
permalink: /Macros/QoL/DoM/Ability-Hotbar-Cycler
---

This macro setup is for setting up ability hotbars that you can cycle between. This can be useful for organizing your ability bars while cleaning up your UI.

For this to work you need to set the macros to the desgnated spots on hotbars 1, 2, 3, and 4. Once done simply add your abilities to the remaining slots.

### Hotbar 1 - Slot 1 | Hotbar 3 - Slot 12

```
/mlock
/merror off
/hb display 1 off
/hb display 2 off
/hb display 3 off
/hb display 4 on
```
### Hotbar 2 - slot 1 | Hotbar 4 - Slot 12

```
/mlock
/merror off
/hb display 1 on
/hb display 2 off
/hb display 3 off
/hb display 4 off
```

### Hotbar 3 - Slot 1 | Hotbar 1 - Slot 12

```
/mlock
/merror off
/hb display 1 off
/hb display 2 on
/hb display 3 off
/hb display 4 off
```

### Hotbar 4 - Slot 1 | Hotbar 2 - Slot 12

```
/mlock
/merror off
/hb display 1 off
/hb display 2 off
/hb display 3 on
/hb display 4 off
```