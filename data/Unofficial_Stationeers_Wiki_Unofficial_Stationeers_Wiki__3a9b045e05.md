__

# [ Unofficial Stationeers Wiki Unofficial Stationeers Wiki](/Main_Page)

__

  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Powered_Vent "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Powered_Vent "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Powered_Vent&action=info "More information about this page")



  * [Log in](/index.php?title=Special:UserLogin&returnto=Powered+Vent&returntoquery=action%3Dedit)



  * [ ![Unofficial Stationeers Wiki](/resources/assets/stationeers-wiki.png)](/Main_Page)
  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Powered_Vent "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Powered_Vent "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Powered_Vent&action=info "More information about this page")



_  Actions_

  * [Page](/Powered_Vent "View the content page \[c\]")
  * [Discussion](/index.php?title=Talk:Powered_Vent&action=edit&redlink=1 "Discussion about the content page \[t\]")
  * [Edit](/index.php?title=Powered_Vent&action=edit "Edit this page")
  * [History](/index.php?title=Powered_Vent&action=history "Past revisions of this page \[h\]")



## Editing Powered Vent

##### 

**Warning:** You are not logged in. Your IP address will be publicly visible if you make any edits. If you **[log in](https://stationeers-wiki.com/index.php?title=Special:UserLogin&returnto=Powered_Vent)** or **[create an account](https://stationeers-wiki.com/index.php?title=Special:CreateAccount&returnto=Powered_Vent)** , your edits will be attributed to your username, along with other benefits. 

Anti-spam check. Do **not** fill this in!

{{Itembox | name = Kit (Powered Vent) | image = [[File:ItemKitPoweredVent.png]] | prefabhash = 2015439334 | prefabname = ItemKitPoweredVent | stacks = 5 | slot_class = SlotClass.None | sorting_class = SortingClass.Kits | recipe_machine1 = Hydraulic Pipe Bender (Tier Two) | recipe_cost1 = 5g [[Steel]], 5g [[Electrum]], 2g [[Invar]] | constructs = [[Powered Vent]], [[Powered Vent Large]] }} {{Structurebox | name = Powered Vent | image = [[File:StructurePoweredVent.png]] | prefab_hash = 938836756 | prefab_name = StructurePoweredVent | power_usage = 250W | placed_on_grid = Small Grid | decon_with_tool1 = [[Hand Drill]] | placed_with_item = [[Kit (Powered Vent)]] | item_rec1 = [[Kit (Powered Vent)]] | decon_with_tool2 = [[Wrench]] | const_with_tool1 = [[Screwdriver]] | const_with_item1 = 2 x [[Kit (Pipe)]] | decon_with_tool3 = [[Angle Grinder]] | const_with_tool2 = [[Welding Torch]] | const_with_item2 = 2 x [[Plastic Sheets]] }} {{Structurebox | name = Powered Vent Large | image = [[File:StructurePoweredVentLarge.png]] | prefab_hash = -785498334 | prefab_name = StructurePoweredVentLarge | power_usage = 500W | placed_on_grid = Small Grid | decon_with_tool1 = [[Hand Drill]] | placed_with_item = [[Kit (Powered Vent)]] | item_rec1 = [[Kit (Powered Vent)]] | decon_with_tool2 = [[Wrench]] | const_with_tool1 = [[Screwdriver]] | const_with_item1 = 2 x [[Electronic Parts]] | decon_with_tool3 = [[Angle Grinder]] | const_with_tool2 = [[Welding Torch]] | const_with_item2 = 4 x [[Plastic Sheets]] }} ==Description== Powered vents move air and pull vacuum far more quickly than an [[Active Vent|active vent]]. Powered vents have a unique behavior to <nowiki>"scavenge"</nowiki> air from grids outside the one it's built on once the pressure is low enough (~20kpa), skipping the wait for the last few pascals of gas to diffuse into the vent. == Powered Vent == <blockquote><q>Great for moving large quantities of air into a pipe network. Its primary purpose is for the creation of multi-grid airlocks. It can efficiently pull a vacuum on a small to medium sized room.</q><br> '''- Stationpedia'''</blockquote> By moles per tick, pulls inward ~2.04x and blows outward about 2.14x as much as an active vent. Scavenge range 9x9x9 large grid centered on vent. == Powered Vent Large == <blockquote><q>For building large scale airlock systems and pressurized hangars, a bigger and bolder version of the powered vent that can efficiently pull a vacuum in large room. </q><br> '''- Stationpedia'''</blockquote> By moles per tick, pulls inward ~4.14x and blows outward about 4.34x as much as an active vent. Scavenge range 13x13x13 large grid centered on vent. {{Data Network Header}} === Mode Values === These list the values and meanings for the "Mode" property of the Power Vent/Large. {| class="wikitable" |- ! Value !! Meaning |- | 0 || "Outward" mode (Moves gas from the connected pipe network to the surrounding atmosphere.) |- | 1 || "Inward" mode (Moves gas from the surrounding atmosphere to the connected pipe network.) |} {{Data Parameters| {{Data Parameters/row|Power|Boolean|w=0|Can be read to return if the device is correctly powered or not, set via the power system, returns 1 if powered and 0 if not|multiple=2|0|Off|1|On}} {{Data Parameters/row|PressureExternal|Float|<div>"Outward" mode: Maximum pressure of the surrounding atmosphere. Default 101.325 (kPa).<br> "Inward" mode: Minimum pressure of the surrounding atmosphere. Default 0 (kPa).</div>}} {{Data Parameters/row|Mode|Integer|The mode of the Power Vent.|multiple=2|0|Outward|1|Inward}} {{Data Parameters/row|Lock|Boolean|Disable manual operation of the Power Vent.|multiple=2|0|Unlocked|1|Locked}} {{Data Parameters/row|On|Boolean|The current state of the Power Vent.|multiple=2|0|Off|1|On}} {{Data Parameters/row|RequiredPower|Integer|w=0|Idle operating power quantity, does not necessarily include extra demand power}} {{Data Parameters/row|PrefabHash|Integer|w=0|The hash of the structure}} {{Data Parameters/row|ReferenceId|Integer|w=0|Unique Reference Identifier for this object}} {{Data Parameters/row|NameHash|Integer|w=0|Provides the hash value for the name of the object as a 32-bit integer.}} }} 

Summary:

Please note that all contributions to Unofficial Stationeers Wiki may be edited, altered, or removed by other contributors. If you do not want your writing to be edited mercilessly, then do not submit it here.  
You are also promising us that you wrote this yourself, or copied it from a public domain or similar free resource (see [Unofficial Stationeers Wiki:Copyrights](/index.php?title=Unofficial_Stationeers_Wiki:Copyrights&action=edit&redlink=1 "Unofficial Stationeers Wiki:Copyrights \(page does not exist\)") for details). **Do not submit copyrighted work without permission!**

To edit this page, please answer the question that appears below ([more info](/Special:Captcha/help "Special:Captcha/help")): 

What machine can you use to craft iron frames?

[Cancel](/Powered_Vent) |  [Editing help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Editing_pages) (opens in new window)

Templates used on this page: 

  * [Template:=](/Template:%3D "Template:=") ([edit](/index.php?title=Template:%3D&action=edit "Template:=")) 
  * [Template:Construction stage](/Template:Construction_stage "Template:Construction stage") ([edit](/index.php?title=Template:Construction_stage&action=edit "Template:Construction stage")) 
  * [Template:Data Network Header](/Template:Data_Network_Header "Template:Data Network Header") ([edit](/index.php?title=Template:Data_Network_Header&action=edit "Template:Data Network Header")) 
  * [Template:Data Parameters](/Template:Data_Parameters "Template:Data Parameters") ([edit](/index.php?title=Template:Data_Parameters&action=edit "Template:Data Parameters")) 
  * [Template:Data Parameters/row](/Template:Data_Parameters/row "Template:Data Parameters/row") ([edit](/index.php?title=Template:Data_Parameters/row&action=edit "Template:Data Parameters/row")) 
  * [Template:Ifnotempty](/Template:Ifnotempty "Template:Ifnotempty") ([edit](/index.php?title=Template:Ifnotempty&action=edit "Template:Ifnotempty")) 
  * [Template:Infobox](/Template:Infobox "Template:Infobox") ([edit](/index.php?title=Template:Infobox&action=edit "Template:Infobox")) 
  * [Template:Itembox](/Template:Itembox "Template:Itembox") ([edit](/index.php?title=Template:Itembox&action=edit "Template:Itembox")) 
  * [Template:P1](/Template:P1 "Template:P1") ([edit](/index.php?title=Template:P1&action=edit "Template:P1")) 
  * [Template:P2](/Template:P2 "Template:P2") ([edit](/index.php?title=Template:P2&action=edit "Template:P2")) 
  * [Template:Structurebox](/Template:Structurebox "Template:Structurebox") ([edit](/index.php?title=Template:Structurebox&action=edit "Template:Structurebox")) 
  * [Module:Infobox](/Module:Infobox "Module:Infobox") ([view source](/index.php?title=Module:Infobox&action=edit "Module:Infobox")) (protected)
  * [Module:Navbar](/Module:Navbar "Module:Navbar") ([view source](/index.php?title=Module:Navbar&action=edit "Module:Navbar")) (protected)



Retrieved from "<https://stationeers-wiki.com/Powered_Vent>"

  * [Privacy policy](/Unofficial_Stationeers_Wiki:Privacy_policy "Unofficial Stationeers Wiki:Privacy policy")
  * [About Unofficial Stationeers Wiki](/Unofficial_Stationeers_Wiki:About "Unofficial Stationeers Wiki:About")
  * [Disclaimers](/Unofficial_Stationeers_Wiki:General_disclaimer "Unofficial Stationeers Wiki:General disclaimer")



  *   * [Powered by MediaWiki](//www.mediawiki.org/)


  *[v]: View this template
  *[t]: Discuss this template
  *[e]: Edit this template
  *[m]: This is a minor edit
  *[N]: This edit created a new page
