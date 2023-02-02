Admirals Parachute Mod Class Names, & types.xml Code Snippets

Parachute Mod on Steam: https://steamcommunity.com/sharedfiles/filedetails/?id=2912241382

Correct as of 02/02/23

Many thanks to TheAdmiral for creating such an amazing mod!

This document is in no way associated with TheAdmiral. (Control, Jetpack & Json Configuration text copied from the mods Steam Page).

----

Controls:
Parachute:
Jump to activate once falling far enough
WASD to move
Sprint to Turbo

JetPack:
WASD to move
Sprint to Turbo
Jump to go Up
Crouch to go Down
PetrolStation or FuelCan to refuel

----

Json Configuration (will be created inside your servers config / settings / profile folder when mod first starts):

		{
            "ClassName": "ADM_ParachuteBag_Base",//class name of parachute bag
            "CanopyName": "ADM_Parachute_Fabric",//class name of parachute canopy
            "TopSpeedMultiplierY": 1.0, //top falling speed multiplier
            "TopSpeedMultiplierZ": 1.0,//top forward speed multiplier
            "AccelMultiplierY": 0.5,//top falling acceleration multiplier
            "AccelMultiplierZ": 0.5,//top forward acceleration multiplier
            "ParachuteDamage": 1,//parachute damage 0 = none, 1 = damage on deployment, 2 = delete on landing
            "LandingSpeedDamage": 0//player damage for landing to hard
        },


----

CLASS NAMES:

ADM_ParachuteBag_Fabric

ADM_ParachuteBag_RWB

ADM_ParachuteBag_Target

ADM_ParachuteBag_Skull

ADM_ParachuteBag_ADM

ADM_ParachuteBag_Fabric_Speed

ADM_ParachuteBag_RWB_Speed

ADM_ParachuteBag_Skull_Speed

ADM_ParachuteBag_ADM_Speed

ADM_TactiParaBag_Camo

ADM_TactiParaBag_Camo_Speed

ADM_JetPack_Green

----

types.xml Code Snippet:

<!--start of parachute types code snippet-->

 <type name="ADM_ParachuteBag_Fabric">
        <nominal>2</nominal>
        <lifetime>28800</lifetime>
        <restock>0</restock>
        <min>1</min>
        <quantmin>-1</quantmin>
        <quantmax>-1</quantmax>
        <cost>100</cost>
        <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0"/>
        <category name="clothes"/>
        <usage name="Military"/>
        <value name="Tier3"/>
        <value name="Tier4"/>
    </type>
	
	 <type name="ADM_ParachuteBag_RWB">
        <nominal>2</nominal>
        <lifetime>28800</lifetime>
        <restock>0</restock>
        <min>1</min>
        <quantmin>-1</quantmin>
        <quantmax>-1</quantmax>
        <cost>100</cost>
        <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0"/>
        <category name="clothes"/>
        <usage name="Military"/>
        <value name="Tier3"/>
        <value name="Tier4"/>
    </type>
	
	 <type name="ADM_ParachuteBag_Target">
        <nominal>2</nominal>
        <lifetime>28800</lifetime>
        <restock>0</restock>
        <min>1</min>
        <quantmin>-1</quantmin>
        <quantmax>-1</quantmax>
        <cost>100</cost>
        <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0"/>
        <category name="clothes"/>
        <usage name="Military"/>
        <value name="Tier3"/>
        <value name="Tier4"/>
    </type>

	 <type name="ADM_ParachuteBag_Skull">
        <nominal>2</nominal>
        <lifetime>28800</lifetime>
        <restock>0</restock>
        <min>1</min>
        <quantmin>-1</quantmin>
        <quantmax>-1</quantmax>
        <cost>100</cost>
        <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0"/>
        <category name="clothes"/>
        <usage name="Military"/>
        <value name="Tier3"/>
        <value name="Tier4"/>
    </type>
	
	 <type name="ADM_ParachuteBag_ADM">
        <nominal>2</nominal>
        <lifetime>28800</lifetime>
        <restock>0</restock>
        <min>1</min>
        <quantmin>-1</quantmin>
        <quantmax>-1</quantmax>
        <cost>100</cost>
        <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0"/>
        <category name="clothes"/>
        <usage name="Military"/>
        <value name="Tier3"/>
        <value name="Tier4"/>
    </type>
	
	 <type name="ADM_TactiParaBag_Camo">
        <nominal>2</nominal>
        <lifetime>28800</lifetime>
        <restock>0</restock>
        <min>1</min>
        <quantmin>-1</quantmin>
        <quantmax>-1</quantmax>
        <cost>100</cost>
        <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0"/>
        <category name="clothes"/>
        <usage name="Military"/>
        <value name="Tier3"/>
        <value name="Tier4"/>
    </type>
	
	 <type name="ADM_JetPack_Green">
        <nominal>1</nominal>
        <lifetime>28800</lifetime>
        <restock>3600</restock>
        <min>1</min>
        <quantmin>-1</quantmin>
        <quantmax>-1</quantmax>
        <cost>100</cost>
        <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0"/>
        <category name="clothes"/>
        <usage name="ContaminatedArea"/>
    </type>

<!--end of parachute types code snippet-->

----
