__

# [ Unofficial Stationeers Wiki Unofficial Stationeers Wiki](/Main_Page)

__

  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Pressure_Regulator "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Pressure_Regulator "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Permanent link](/index.php?title=Pressure_Regulator&oldid=22781 "Permanent link to this revision of the page")
  * [Page information](/index.php?title=Pressure_Regulator&action=info "More information about this page")



  * [Log in](/index.php?title=Special:UserLogin&returnto=Pressure+Regulator&returntoquery=printable%3Dyes)



  * [ ![Unofficial Stationeers Wiki](/resources/assets/stationeers-wiki.png)](/Main_Page)
  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Pressure_Regulator "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Pressure_Regulator "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Permanent link](/index.php?title=Pressure_Regulator&oldid=22781 "Permanent link to this revision of the page")
  * [Page information](/index.php?title=Pressure_Regulator&action=info "More information about this page")



_  Actions_

  * [Page](/Pressure_Regulator "View the content page \[c\]")
  * [Discussion](/index.php?title=Talk:Pressure_Regulator&action=edit&redlink=1 "Discussion about the content page \[t\]")
  * [Edit](/index.php?title=Pressure_Regulator&action=edit "Edit this page \[e\]")
  * [History](/index.php?title=Pressure_Regulator&action=history "Past revisions of this page \[h\]")



## Pressure Regulator

### From Unofficial Stationeers Wiki

##### 

Pressure Regulator [![ItemKitRegulator.png](/images/b/b9/ItemKitRegulator.png)](/File:ItemKitRegulator.png)  
---  
Operation  
Power Usage|  100W  
Prefab Hash|  209854039  
Prefab Name|  StructurePressureRegulator  
Construction  
Placed with|  [Kit (Pressure Regulator)](/Kit_\(Pressure_Regulator\) "Kit \(Pressure Regulator\)")  
Placed on|  Small Grid  
Stage 1  
Deconstruction  
Deconstructed with|  [Hand Drill](/Hand_Drill "Hand Drill")  
Item received|  [Kit (Pressure Regulator)](/Kit_\(Pressure_Regulator\) "Kit \(Pressure Regulator\)")  
  
  * [v](/Template:Structurebox "Template:Structurebox")
  * [t](/index.php?title=Template_talk:Structurebox&action=edit&redlink=1 "Template talk:Structurebox \(page does not exist\)")
  * [e](https://stationeers-wiki.com/index.php?title=Template:Structurebox&action=edit)

  
  
  


  


## Description

> "Controlling the flow of gas between two pipe networks, pressure regulators shift gas until a set pressure on the outlet side is achieved, or the gas supply is exhausted. The back pressure regulator, by contrast, will only operate when pressure on the intake side exceeds the set value. With a max pressure of over 20,000kPa, it requires power to operate."  
>  **\- Stationpedia**

The standard Pressure Regulator is an active powered device for controlled transfer of substances between the two pipe networks. Pressure Regulator will use the gas from Input pipe network to pressurize the Output pipe network until a target pressure defined by the valve setting is reached or exceeded, or unless the input pipe runs dry. When being placed, hologram indicators will display the Input pipe arrow inward, the Output pipe arrow outward, and the power socket on its side. It has a pressure control valve, which defines the target pressure. 

The most common use for a standard Pressure Regulator is to place one ahead of a [Gas Tank Storage](/Gas_Tank_Storage "Gas Tank Storage") unit to safely fill the inserted [Gas Canister](/Gas_Canister "Gas Canister") or [Gas Canister (Smart)](/Gas_Canister_\(Smart\) "Gas Canister \(Smart\)") with gas input without overpressurizing it. Similar principle can be used to maintain the desired pressure level in any pipe network or room. 

The maximum pressure setting is 60795 kPa - a critical pressure limit for a pipe network before it begin to take damage. 

To calculate the moles per tick, use the following equation: n = (P * V) / (R * T) 

Where: 

  * P = Min(Input pressure, 101.325)
  * V = (OutputPipeVolume / InputPipeVolume) * 100
  * n = Moles per tick
  * R = Gas constant (8.3144)
  * T = Input temperature



## Data Network Properties

These are all [Data Network](/Category:Data_Network "Category:Data Network") properties of this device. 

### Data Parameters

These are all parameters that can be written with a [Logic Writer](/Kit_\(Logic_I/O\)#Logic_Writer "Kit \(Logic I/O\)"), [Batch Writer](/Kit_\(Logic_I/O\)#Batch_Writer "Kit \(Logic I/O\)"), or [Integrated Circuit (IC10)](/Integrated_Circuit_\(IC10\) "Integrated Circuit \(IC10\)"), and can be read with a [Logic Reader](/Kit_\(Logic_I/O\)#Logic_Reader "Kit \(Logic I/O\)"), [Batch Reader](/Kit_\(Logic_I/O\)#Batch_Reader "Kit \(Logic I/O\)"), or [Integrated Circuit (IC10)](/Integrated_Circuit_\(IC10\) "Integrated Circuit \(IC10\)"). 

**Click here to see/hide all the data network properties**

Parameter Name  |  Data Type  |  Access  |  Value  |  Description   
---|---|---|---|---  
Power  |  Boolean  |  Read  | 0  |  Unpowered  | Can be read to return if the Pressure Regulator is correctly powered or not, set via the power system, return 1 if powered and 0 if not   
1  |  Powered   
Error  |  Boolean  |  Read  | 0  |  | 1 if device is in error state, otherwise 0   
1  |  Error   
Lock  |  Boolean  |  Read Write  | 0  |  Unlocked  | Disable manual operation of the Pressure Regulator.   
1  |  Locked   
Setting  |  Integer  |  Read Write  | 0.0 to 60795.0  |  | A variable setting that can be read or written.   
Maximum  |  Float  |  Read  |  |  | Maximum setting of the Pressure Regulator   
Ratio  |  Float  |  Read  | 0.0 to 1.0  |  | Context specific value depending on device, 0 to 1 based ratio   
On  |  Boolean  |  Read Write  | 0  |  Off  | The current state of the Pressure Regulator.   
1  |  On   
RequiredPower  |  Integer  |  Read  |  |  | Idle operating power quantity, does not necessarily include extra demand power   
PrefabHash  |  Integer  |  Read  |  |  | The hash of the structure   
ReferenceId  |  Integer  |  Read  |  |  | Unique Reference Identifier for this object   
NameHash  |  Integer  |  Read  |  |  | Provides the hash value for the name of the object as a 32 bit integer.   
  
Retrieved from "[https://stationeers-wiki.com/index.php?title=Pressure_Regulator&oldid=22781](https://stationeers-wiki.com/index.php?title=Pressure_Regulator&oldid=22781)"

[Categories](/Special:Categories "Special:Categories"): 

  * [Structures](/Category:Structures "Category:Structures")
  * [Data Network](/Category:Data_Network "Category:Data Network")
  * [Atmospherics](/Category:Atmospherics "Category:Atmospherics")



  * This page was last edited on 18 May 2025, at 13:38.
  * [Privacy policy](/Unofficial_Stationeers_Wiki:Privacy_policy "Unofficial Stationeers Wiki:Privacy policy")
  * [About Unofficial Stationeers Wiki](/Unofficial_Stationeers_Wiki:About "Unofficial Stationeers Wiki:About")
  * [Disclaimers](/Unofficial_Stationeers_Wiki:General_disclaimer "Unofficial Stationeers Wiki:General disclaimer")



  *   * [Powered by MediaWiki](//www.mediawiki.org/)


  *[v]: View this template
  *[t]: Discuss this template
  *[e]: Edit this template
  *[m]: This is a minor edit
  *[N]: This edit created a new page
