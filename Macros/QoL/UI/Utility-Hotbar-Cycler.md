---
title: Utility Hotbar Cycler
description: Simple utility hotbar cycler
parent: UI
grand_parent: Quality of Life
permalink: /Macros/QoL/DoM/Utility-Hotbar-Cycler
---

This macro setup is for setting up shared hotbars that you can cycle between. It comes in useful for cleanign up a cluttered UI. It can be used for almost anything the user desires it for.

Simply add these macros to shared hotbar 6 and then set items you would like to cycle between to shared hotbars 7, 8, 9, and 10.

Display Hotbar 7
```
/mlock
/merror off
/hotbar display share 7 on
/hotbar display share 8 off
/hotbar display share 9 off
/hotbar display share 10 off
```

Display Hotbar 8
```
/mlock
/merror off
/hotbar display share 7 onff
/hotbar display share 8 on
/hotbar display share 9 off
/hotbar display share 10 off
```

Display Hotbar 9
```
/mlock
/merror off
/hotbar display share 7 off
/hotbar display share 8 off
/hotbar display share 9 on
/hotbar display share 10 off
```

Display Hotbar  10
```
/mlock
/merror off
/hotbar display share 7 off
/hotbar display share 8 off
/hotbar display share 9 off
/hotbar display share 10 on
```