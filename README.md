# PBCharacterMovement
Project Borealis character movement component.

Includes all your standard classic FPS movement from HL2:

* Strafe bunnyhopping
* Forward bunnyhopping
* Accelerated back hopping (and forward and back hopping)
* Strafe boosting
* Circle strafing
* Wall strafing
* Ramp sliding/trimping/collision boosting
* Smooth crouching and uncrouching, and crouch jumping
* Optional pogo jumping (automatic bunnyhopping)
* WIP Surfing

## Note

Our ladder movement code is game specific and is not publicly redistributed at this time.

Some functionality, like sprinting speed logic, is not publicly redistributed at this time.

# Instructions

1. Paste the [PBCharacterMovement folder](https://github.com/ProjectBorealis/PBCharacterMovement/archive/master.zip) into your project's `Plugins/` folder, or in your engine `Plugins/` folder.
2. Open your Unreal Engine project.
3. Add input action bindings for jump and crouch (Settings > Project Settings > Engine > Input). Add axis bindings for forward, right, look up and turn.
4. Create a new player controller in Blueprint or C++. Here's a [simple Blueprint example](https://blueprintue.com/blueprint/l7vxktwk/).
5. Create a Blueprint child class of PBPlayerCharacter.
6. Create a gamemode with Default Pawn set to your Blueprint character class, and Player Controller set to your player controller.
7. Enjoy the movement!

You may also want to use HL2 gravity settings. Go to Settings > Project Settings > Engine > Physics > Constants > Default Gravity Z and set it to `-1143`.
