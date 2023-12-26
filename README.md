# FPSZombies

## Call Of Duty Zombies style game made in Unreal Engine 5

* Player movement with Enhanced Input System (Input actions & Mapping Context)
* Player animations using Blend Spaces (Walking & Running) and Aim Offset animations
* Shooting functionality using Line Trace and includes Muzzle flash, sound and shake effect
* Reload animation and sound

### Zombie AI System:
* Chase player using nav mesh (AIMoveTo function)
* Attack the player when it's in reach (less than 1 meter) (Functionality & Animation)
* Reload attack to meet the attack rate specified

### Money System
* Player recieves money (points) for shooting the zombies
* Each bullet hit gives 25$ to the player
* Use the Money to open Doors and Escape
