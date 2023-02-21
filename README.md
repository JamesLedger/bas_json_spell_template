# bas_json_spell_template

JSON Template for custom spell

## Files Overview

Template JSON files required to add a new spell to Blade and Sorcery. Example in image below where east spell has been added
<img src="https://i.imgur.com/vSUnqyN.png"/>

### Spell_IceBall

Spell JSON. Configure features of your spell such as throwing, spraying and imbuement, select charge effects, and link to your spell's DLL.

### Item_Spell_IceBall

Spell Item JSON. In B&S, every spell has an associated 'spell item' which allows them to be placed in, for example, the player's inventory.

### Effect_Spell_SpellOrbIceball

Spell Orb Effect JSON. Configure how your spell appears in the spell wheel.

### Container_PlayerDefault

Player inventory file. Required to allow the player to cast your spell.

### Manifest

Mod manifest. Required to register your mod, and contains metadata about your mod.
