# 05-Space-SHMUP
 
Change 1
 I added a fifth enemy type with a cosin wave movement pattern.  I used a cube and a sphere to make the enemy ship and programmed the cosin wave into it.
 
 
Change 2
 Adding a sniper rifle weapon would be my second change.  To accomplish this, I would add a new WeaponType in the enum WeaponType.  The sniper rifle weapon would then be   able to be editable within the Unity Inspector to set damage and velocity. I could set it as a Power Up  so when I shoot an enemy it would drop the sniper rifle power
  up and allow the Hero to, if the current weapon is not of type Sniper Rifle, switch the weapon to the Sniper Rifle.
  
For tuning, I decreased the damage of the blaster from 1 to 0.5 and decreased the delay between shots to .1 from .2.  For the Spread shot, I increased the delay between shots from 0.4 to 0.8 to simulate a more of a slug shot feeling for the player and also increased the velocity of the projectile from 50 to 80 as I wanted there to be a feeling of force behind the weapon.  
