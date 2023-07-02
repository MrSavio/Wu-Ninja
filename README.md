# Wu-Ninja

Must Install restart editor, and auto-size comment box plugins - All other plugins should install automatically

### High Concept

A short but well crafted third person action game with a variety of mechanics to fight, platform, and race through levels to become a Black Belt Ninja.

* <KEY FEATURES LIST - TOP 5>

Unique Movement Mechanics = Roll Dodging, Wall Running, Wall Sliding, Wall Jumping, Chain Sword Grapple, Chain Sword Swing, Ball Rolling

Combo Attack System = Basic and Heavy Attack Combos, Special Attack Combos, Assasinations, Power Ups, Special Abilities from Combo Multipliers

Belt System = Player progression based on a belt system like MMA, start with white belt and earn your way up to black belt

### Documents

See "EUW_Documentation" Located in "Content>Documentation"

### Controls

Action               | Keyboard Control  | Gamepad Control
---                  |---                |---
Movement             | AWSD              | Left stick
Direction Aim        | Mouse position    | Right stick
Jump                 | Space Bar         | Bottom Face Button
Crouch               | C                 | Left Bumper
Basic Combo Attack   | Left mouse click  | Left Face Button
Heavy Combo Attack   | Right mouse click | Right Face Button
Interact(Pick up)    | F                 | Bottom Face Button

### Debug tools/controls

Use the <key> to open the menu

ex. Press <button> to <trigger behaviour>

1. Debug menu can be accessed in the pause menu during run time (please don't change values outside of these unless you know what you're doing)


### Known Issues

* <CAVEATS: KNOWN THINGS TO NOT DO, CRASH BUGS>

1. grappling while attacking causes some weird issues with the rotation of the character and causes movement to be slugish until the next time you attack.

2. also attacking while grappling causes the grappling system to break until you attack again which resets some variables and causes it to become active again. (solving these with a isAttacking variable check but I would like to find a way to allow attack interuptions during a grapple. or vice versa)

### Team:

* <TEAM MEMBER - ROLE>

Nicolas Seymour - Solo Developer, Everything!
