# ChangeBot
 Magnetic Toolchanging  3d printer system compatable with VzBot
 
 
These files are to replace the Xgantry on the Vzbot with one that can pick up and store tools automatically. The goal of this 
was to create a toolchanging system fairly cheap. It uses 1in SmCo magnets to retain the tool. This means that there are no moving
parts on the pickup mechanism, so there should be little to no weat over time.

The default Volcano printhead costs around $80, and the toolhead that picks up the printheads costs around $50 (including camera)

This is around 3x cheaper than the e3d toolchanger, with simmilar functionality. THe downside of using magnets for retention is that they
provide no cmechanical lock to keep them located, meaning that the printhead can wiggle around or even fall off mid print. I have microswitched on each printhead to detect that it is on the toolhead and stop the print if the printhead falls off. 

That being said, after ~100 hours printing at 100-200mm/s I have had no issues or print defects that stem from the printhead moving around.