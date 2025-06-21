In here are some generally useful notes that make my life easier and will hopefully make yours easier too.

1: In 1v1s and Training with 1 CPU, there is a 1.2 damage multiplier. Make sure to account for that in you mods.

2: The hitbox angles work on the assumption that the object with the hitbox, is facing left if it goes behind the fighter, and right if it goes in front of the fighter. This is reversed if the fighter is facing left.

3: When adding moves or effects or anything in general, add it to the install at the top of the mod.rs, it won't apply if it's not there.

4: The angle 361 is known as "The Sakurai Angle". How it works is when you hit an enemy at low percent, the attack will send them straight, but as they take more damage, it starts to shoot them up and forward diagonally.

5: If you are adding hitboxes, remember that each frame, if there are multiple hitboxes, they all have to have their own ID, otherwise, that hitbox with an improper ID, will not activate. IDs start at 0 and go upwards. ie. 0,1,2,3 etc.