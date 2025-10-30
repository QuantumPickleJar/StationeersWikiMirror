__

# [ Unofficial Stationeers Wiki Unofficial Stationeers Wiki](/Main_Page)

__

  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Filtration "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Filtration "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Filtration&action=info "More information about this page")



  * [Log in](/index.php?title=Special:UserLogin&returnto=Filtration&returntoquery=action%3Dedit)



  * [ ![Unofficial Stationeers Wiki](/resources/assets/stationeers-wiki.png)](/Main_Page)
  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Filtration "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Filtration "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Filtration&action=info "More information about this page")



_  Actions_

  * [Page](/Filtration "View the content page \[c\]")
  * [Discussion](/index.php?title=Talk:Filtration&action=edit&redlink=1 "Discussion about the content page \[t\]")
  * [Edit](/index.php?title=Filtration&action=edit "Edit this page")
  * [History](/index.php?title=Filtration&action=history "Past revisions of this page \[h\]")



## Editing Filtration

##### 

**Warning:** You are not logged in. Your IP address will be publicly visible if you make any edits. If you **[log in](https://stationeers-wiki.com/index.php?title=Special:UserLogin&returnto=Filtration)** or **[create an account](https://stationeers-wiki.com/index.php?title=Special:CreateAccount&returnto=Filtration)** , your edits will be attributed to your username, along with other benefits. 

Anti-spam check. Do **not** fill this in!

[[Category:Atmospherics]] <languages/> <translate> {{Structurebox | name = Filtration | image = [[File:filtration.jpg]] | power_usage = 5w | placed_with_item = [[Kit (Atmospherics)]] | placed_on_grid = Small Grid | const_with_item1 = 2 x [[Kit (Pipe)]] | decon_with_tool1 = [[Hand Drill]] | item_rec1 = [[Kit (Atmospherics)]] | const_with_tool2 = [[Screwdriver]] | const_with_item2 = [[Cable Coil]] | decon_with_tool2 = [[Wrench]] | decon_with_tool3 = [[Hand Drill]] }} <!--T:1--> =Description= Filtration Unit is a powered machine, that is used to separate [[Gas|gases]] from one [[Pipes|pipe]] network into another using [[Filter|filters]]. Identical to most other machines deployable from the [[Kit (Atmospherics)]], Filtration unit occupies a 2x1 space on the small building grid supported by a frame. Back face of the unit provide floor-level power and logic cable ports, while the front side holds the control panel and two filter sockets. Front and either side also feature dedicated one-way pipe slots for managing gas inputs and ouputs. =Usage= Once you have placed the Filtration Unit in your desired location, there are 3 separate pipe connections that will need to be made: # '''Input''' - Starting gas network that you want to filter from, right of the front panel. # '''Output 1''' - Filtered gas output, left of the front panel. # '''Output 2''' - The remainder gas mixture output, colloquially called "waste output", below the front panel and to the side of the inline between the two primary connections. <br> When powered and turned on, Filtration Unit will take a specific amount (in mols) of the Input gas mixture and process it using the Filters attached. It will then separate all the gases associated with these Filters and eject them to the Output 1 pipe network, and eject the remaining gases to the Output 2 network. Filtration Unit can process greater amount of gas over time if the Input netweork pressure is significantly greater than pressure in either of its ouput networks. <br> [[Guide (Filtration)]] provides additional information regarding the function, construction, and operation of a Filtration unit. =Characteristics= * It has a manual power switch. * It consumes 10W of [[Power]] per [[Tick]] when idle and 44W when active. * It has a separate [[Power Port]] and [[Data Port]]. * It has an on-board IC10 chip slot. * It has a pipe port (labelled "Input") for the gas mixture from which the designated gas(es) '''will be''' filtered. * It has a pipe port (labelled "Filtered") for the designated gas(es) that '''have been''' filtered. (This is in line with and directly opposite of the input) * It has a pipe port (labelled "Unfiltered") for any remaining unfiltered gases. (This is to the side) * It can filter up to 2 different gases at once by inserting two different filters. ** Inserting two of the '''same''' type of filter does not increase filtration speed. Note: When using an I/O slot reader chip, the filter slots are labeled as slot 1, slot 2 and slot 3(IC), with 1 being the slot closer to the inlet. When using an IC chip, the slots are labeled as slot 0, slot1 and slot 2(IC). =User Interface= A Filtration unit provides the following user interface: {| class="wikitable" |- ! Name || Type !! Function |- | [[Filters|Filter]] (Right) || Slot 0 || Port for a gas filter. If gas of the same type is present in the incoming mixture, it will be redirected out the "Filtered" pipe port. |- | Filter (Left) || Slot 1 || Another Port for a gas filter that functions the same as its twin slot. May contain the same or a different filter. |- | v || Slot 2 || IC10 placed in filtration unit (has 2 Input/Outputs) |- | On || Switch || Switches Filtration unit between turned on or turned off. (On=1/Off=0) |- |} {{Data Network Header}} {{Data Parameters}} <!--T:4--> {| class="wikitable" |- ! Parameter Name !! Data Type !! Description |- | On || Boolean || Powers on the Filtration unit on when set to 1. Powers off when set to 0. |- | Open || Boolean || |- | Setting || Integer || |- | Lock || Boolean || |- | Mode || Boolean || 0: idle, 1: Active |} {{Data Outputs}} <!--T:5--> {| class="wikitable" |- ! Output Name !! Data Type !! Description |- | Power || Boolean || Returns whether the Filtration unit is turned on and receives power. (0 for no, 1 for yes) |- | Open || Boolean || Returns whether the Filtration unit IC Slot cover is open or closed. (0 for closed, 1 for open) |- | Mode || Boolean || Returns whether the Filtration unit is active or idle (0 for idle, 1 for Active) |- | Error || Boolean || Returns whether the Filtration unit is flashing an error. (0 for no, 1 for yes) |- | Lock || Boolean || Returns whether the Filtration unit is locked. (0 for no, 1 for yes) |- | Setting || Integer || |- | Maximum || Integer || |- | Ratio || Float || |- | On || Boolean || Returns whether the Filtration unit is turned on. (0 for no, 1 for yes) |- | RequiredPower || Integer || Returns the current amount of power in Watts required by the Filtration unit. |- | PressureInput|| Float || Input pressure in kilopascals |- | TemperatureInput || Float || Input temperature in kelvin |- | RatioOxygenInput || Float || Percentage of Oxygen in input as ratio between 0 and 1 |- | RatioCarbonDioxideInput || Float || Percentage of Carbon Dioxide in input as ratio between 0 and 1 |- | RatioNitrogenInput || Float || Percentage of Nitrogen in input as ratio between 0 and 1 |- | RatioPollutantInput || Float || Percentage of Pollutant in input as ratio between 0 and 1 |- | RatioVolatilesInput || Float || Percentage of Volatiles in input as ratio between 0 and 1 |- | RatioWaterInput || Float || Percentage of Water in input as ratio between 0 and 1 |- | RatioNitrousOxideInput || Float || Percentage of Nitrous Oxide in input as ratio between 0 and 1 |- | TotalMolesInput|| Float || Total quantity of gas in input measured in moles |- | PressureOutput|| Float || Output pressure in kilopascals |- | TemperatureOutput || Float || Output temperature in kelvin |- | RatioOxygenOutput || Float || Percentage of Oxygen in output as ratio between 0 and 1 |- | RatioCarbonDioxideOutput || Float || Percentage of Carbon Dioxide in output as ratio between 0 and 1 |- | RatioNitrogenOutput || Float || Percentage of Nitrogen in output as ratio between 0 and 1 |- | RatioPollutantOutput || Float || Percentage of Pollutant in output as ratio between 0 and 1 |- | RatioVolatilesOutput || Float || Percentage of Volatiles in output as ratio between 0 and 1 |- | RatioWaterOutput || Float || Percentage of Water in output as ratio between 0 and 1 |- | RatioNitrousOxideOutput || Float || Percentage of Nitrous Oxide in output as ratio between 0 and 1 |- | TotalMolesOutput|| Float || Total quantity of gas in output measured in moles |- | PressureOutput2|| Float || Waste pressure in kilopascals |- | TemperatureOutput2 || Float || Waste temperature in kelvin |- | RatioOxygenOutput2 || Float || Percentage of Oxygen in waste as ratio between 0 and 1 |- | RatioCarbonDioxideOutput2 || Float || Percentage of Carbon Dioxide in waste as ratio between 0 and 1 |- | RatioNitrogenOutput2 || Float || Percentage of Nitrogen in waste as ratio between 0 and 1 |- | RatioPollutantOutput2 || Float || Percentage of Pollutant in waste as ratio between 0 and 1 |- | RatioVolatilesOutput2 || Float || Percentage of Volatiles in waste as ratio between 0 and 1 |- | RatioWaterOutput2 || Float || Percentage of Water in waste as ratio between 0 and 1 |- | RatioNitrousOxideOutput2 || Float || Percentage of Nitrous Oxide in waste as ratio between 0 and 1 |- | TotalMolesOutput2 || Float || Total quantity of gas in waste measured in moles |- | CombustionInput || Float || |- | CombustionOutput || Float || |- | CombustionOutput2 || Float || |} <!--T:6--> ==Slot Outputs== Slot 0 and 1 are the two gas [[filter]]s. Slot 2 is the [[Integrated Circuit (IC10)|programmable chip]] {| class="wikitable" |- ! Output Name !! Data Type !! Description |- | Occupied || Boolean || Returns whether the slot is occupied. (0 for no, 1 for yes) |- | OccupantHash || Integer || Returns the hash of the object in the slot. |- | Quantity || Integer || Returns the filter life remaining, in percent. |- | Damage || Integer || Returns the damage state of the item in the slot. |- | Class || Integer || Returns an integer representing the class of object. |- | MaxQuanity || Integer || Returns max stack size of the item in the slot. |- | PrefabHash || Integer || Returns the hash of the structure in the slot. |} <!--T:7--> =See Also= * [[Guide (Filtration)]] * [[Kit (Atmospherics)]] * [[Kit (Portable Scrubber) Portable Scrubber|Portable Scrubber]] </translate> 

Summary:

Please note that all contributions to Unofficial Stationeers Wiki may be edited, altered, or removed by other contributors. If you do not want your writing to be edited mercilessly, then do not submit it here.  
You are also promising us that you wrote this yourself, or copied it from a public domain or similar free resource (see [Unofficial Stationeers Wiki:Copyrights](/index.php?title=Unofficial_Stationeers_Wiki:Copyrights&action=edit&redlink=1 "Unofficial Stationeers Wiki:Copyrights \(page does not exist\)") for details). **Do not submit copyrighted work without permission!**

To edit this page, please answer the question that appears below ([more info](/Special:Captcha/help "Special:Captcha/help")): 

What machine do you use to smelt ore?

[Cancel](/Filtration) |  [Editing help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Editing_pages) (opens in new window)

Templates used on this page: 

  * [Template:Construction stage](/Template:Construction_stage "Template:Construction stage") ([edit](/index.php?title=Template:Construction_stage&action=edit "Template:Construction stage")) 
  * [Template:Data Network Header](/Template:Data_Network_Header "Template:Data Network Header") ([edit](/index.php?title=Template:Data_Network_Header&action=edit "Template:Data Network Header")) 
  * [Template:Data Outputs](/Template:Data_Outputs "Template:Data Outputs") ([edit](/index.php?title=Template:Data_Outputs&action=edit "Template:Data Outputs")) 
  * [Template:Data Parameters](/Template:Data_Parameters "Template:Data Parameters") ([edit](/index.php?title=Template:Data_Parameters&action=edit "Template:Data Parameters")) 
  * [Template:Infobox](/Template:Infobox "Template:Infobox") ([edit](/index.php?title=Template:Infobox&action=edit "Template:Infobox")) 
  * [Template:Structurebox](/Template:Structurebox "Template:Structurebox") ([edit](/index.php?title=Template:Structurebox&action=edit "Template:Structurebox")) 
  * [Module:Infobox](/Module:Infobox "Module:Infobox") ([view source](/index.php?title=Module:Infobox&action=edit "Module:Infobox")) (protected)
  * [Module:Navbar](/Module:Navbar "Module:Navbar") ([view source](/index.php?title=Module:Navbar&action=edit "Module:Navbar")) (protected)



This page is a member of 1 hidden category: 

  * [Category:Infobox without prefab data](/Category:Infobox_without_prefab_data "Category:Infobox without prefab data")



Retrieved from "<https://stationeers-wiki.com/Filtration>"

  * [Privacy policy](/Unofficial_Stationeers_Wiki:Privacy_policy "Unofficial Stationeers Wiki:Privacy policy")
  * [About Unofficial Stationeers Wiki](/Unofficial_Stationeers_Wiki:About "Unofficial Stationeers Wiki:About")
  * [Disclaimers](/Unofficial_Stationeers_Wiki:General_disclaimer "Unofficial Stationeers Wiki:General disclaimer")



  *   * [Powered by MediaWiki](//www.mediawiki.org/)


  *[v]: View this template
  *[t]: Discuss this template
  *[e]: Edit this template
  *[m]: This is a minor edit
  *[N]: This edit created a new page
