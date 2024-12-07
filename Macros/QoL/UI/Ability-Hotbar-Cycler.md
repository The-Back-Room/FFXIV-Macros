---
title: Ability Hotbar Cycler
description: Simple ability hotbar cycler
parent: UI
grand_parent: Quality of Life
permalink: /Macros/QoL/DoM/Ability-Hotbar-Cycler
---

This macro setup is for setting up ability hotbars that you can cycle between. This can be useful for organizing your ability bars while cleaning up your UI.

For this to work you need to set the macros to the desgnated spots on hotbars 1, 2, 3, and 4. Once done simply add your abilities to the remaining slots in hotbars 1, 2, 3, and 4 then hide hotbars 2, 3, and 4. Finally, unhide shared hotbar 1.

This works for each class without needing to specify the class. Simply make sure you are on the class you are setting uo and it should work flawlessly.

### Display Hotbar 1
Place this into slot 1 of hotbar 2 and slot 12 of hotbar 2, then add your primary abilities into the remaining slots

```
/mlock
/merror off
/hotbar copy 1 share 1
```

### Display Hotbar 2
Place ths into slot 1 of hotbar 3 and slot 12 of hotbar 1, then add your secondary abilities into the remaining slots

```
/mlock
/merror off
/hotbar copy 2 share 1
```

### Display Hotbar 3
Place this into slot 1 of hotbar 1 and slot 12 of hotbar 2, then add your trinary abilities into the remaining slots

```
/mlock
/merror off
/hotbar copy 3 share 1
```