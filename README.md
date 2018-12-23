## Mod Resource - Magic Dampening Device  
### This is a 'plug-in' to be used in other mods.  
### It adds a creature with custom graphics to the game which will pulse a spellcasting inhibiting aura.  
  
The creature and magic dampening aura default stats:  
  
**Creature:**  
HP:31  
AC:20  
Immune to all none-physical damage and spells  
Piercing/Missile Resistance: 80%  
Slashing Resitance: 50%  
Crushing Resitance: 30%  
  
**Aura:**  
(large area, pulses once per sec, lasts two seconds, killing the creature instantly removes the aura)  
50% casting failure priest/mage (dead magic)  
-10 caster level priest/mage  
save vs. spells +5 bonus  
magic damage dealt: -50%  
  


**To include the Magic Dampening Device Mod-Builder-Block into a mod:**  
  
1. drop the `lib` and `UB_+PLY` folders into the mod main folder // if lib folder already exists drop files from one/or integrate one into the other
  
2. add the following code to your mod .tp2 file:  
   `INCLUDE ~%MOD_FOLDER%/lib/UB_+PLY.tpa~`   
     
3. relevant files to modify the Mod-Builder-Block  
   -creature file: `UB_+PLY.CRE` (Default name: 'Magic Dampening Device')  
   -'Magic Dampening Aura' payload: `UB_+NONE.SPL`  
   
4. TRA-fying:   
   the mod only contains one line of text, which can be found in `%MOD_FOLDER%/lib/UB_+PLY.tpa`  
  
change-log  
     
	v2: added new base graphic  
       adjusted bams and cre file  
	v3: adjusted explosion animation  
       adjusted circle/size  
