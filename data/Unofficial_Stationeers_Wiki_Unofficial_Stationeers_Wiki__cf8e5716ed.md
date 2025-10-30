__

# [ Unofficial Stationeers Wiki Unofficial Stationeers Wiki](/Main_Page)

__

  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Kit_\(Atmospherics\)_Electrolyzer "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Kit_\(Atmospherics\)_Electrolyzer "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Kit_\(Atmospherics\)_Electrolyzer&action=info "More information about this page")



  * [Log in](/index.php?title=Special:UserLogin&returnto=Kit+%28Atmospherics%29+Electrolyzer&returntoquery=action%3Dedit)



  * [ ![Unofficial Stationeers Wiki](/resources/assets/stationeers-wiki.png)](/Main_Page)
  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Kit_\(Atmospherics\)_Electrolyzer "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Kit_\(Atmospherics\)_Electrolyzer "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Kit_\(Atmospherics\)_Electrolyzer&action=info "More information about this page")



_  Actions_

  * [Page](/Kit_\(Atmospherics\)_Electrolyzer "View the content page \[c\]")
  * [Discussion](/index.php?title=Talk:Kit_\(Atmospherics\)_Electrolyzer&action=edit&redlink=1 "Discussion about the content page \[t\]")
  * [Edit](/index.php?title=Kit_\(Atmospherics\)_Electrolyzer&action=edit "Edit this page")
  * [History](/index.php?title=Kit_\(Atmospherics\)_Electrolyzer&action=history "Past revisions of this page \[h\]")



## Editing Kit (Atmospherics) Electrolyzer

##### 

**Warning:** You are not logged in. Your IP address will be publicly visible if you make any edits. If you **[log in](https://stationeers-wiki.com/index.php?title=Special:UserLogin&returnto=Kit_%28Atmospherics%29_Electrolyzer)** or **[create an account](https://stationeers-wiki.com/index.php?title=Special:CreateAccount&returnto=Kit_%28Atmospherics%29_Electrolyzer)** , your edits will be attributed to your username, along with other benefits. 

Anti-spam check. Do **not** fill this in!

[[Category:Atmospherics]] <languages/> <translate> {{Structurebox | name = Electrolyzer | image = [[File:Electrolyzer front.png]] | prefab_hash = -1668992663 | prefab_name = StructureElectrolyzer | power_usage = 1200W | placed_on_grid = Small Grid | decon_with_tool1 = [[Hand Drill]] | placed_with_item = [[Kit (Atmospherics)]] | item_rec1 = [[Kit (Atmospherics)]] | decon_with_tool2 = [[Wrench]] | const_with_item1 = 2 x [[Kit (Pipe)]] | decon_with_tool3 = [[Hand Drill]] | const_with_tool2 = [[Screwdriver]] | const_with_item2 = 2 x [[Cable Coil]] }} <!--T:1--> ==Purpose== An Electrolyzer is a powered Atmospheric processor used to separate water (H<sub>2</sub>O) into H<sub>2</sub> and O<sub>2</sub>. [[Guide (Electrolyzer)]] provides additional information regarding the function, construction, and operation of an Electrolyzer. <!--T:2--> ==Characteristics== * It has a manual power switch. * It consumes #W of [[Power]] per [[Tick]] when idle. * It consumes a maximum of #kW of [[Power]] per [[Tick]] when active. * It has a separate [[Power Port]] and [[Data Port]]. * It has a pipe port (labelled "Input") for the water that '''will be''' electrolyzed. * It has a pipe port (labelled "Output") for the produced H<sub>2</sub> + O<sub>2</sub> gas mixtured. * It outputs a perfect [[Special:MyLanguage/Fuel|Fuel]] mixture of 66.6% H<sub>2</sub> + 33.3% O<sub>2</sub>. <!--T:3--> ==User Interface== An Electrolyzer provides the following user interface: {| class="wikitable" |- ! Name || Type !! Function |- | On/Off|| Switch || Switches Electrolyzer between turned on or turned off. |- |} {{Data Network Header}} {{Data Parameters}} <!--T:4--> {| class="wikitable" |- ! Parameter Name !! Data Type !! Description |- | Lock || Boolean || Locks the Electrolyzer when set to 1. Unlocks it when set to 0. |- | On || Boolean || Powers on the Electrolyzer on when set to 1. Powers off when set to 0. |} {{Data Outputs}} <!--T:5--> {| class="wikitable" |- ! Output Name !! Data Type !! Description |- | Power || Boolean || Returns whether the Electrolyzer is turned on and receives power. (0 for no, 1 for yes) |- | Error || Boolean || Returns whether the Electrolyzer is flashing an error. (0 for no, 1 for yes) |- | Lock || Boolean || Returns whether the Electrolyzer is locked. (0 for no, 1 for yes) |- | On || Boolean || Returns whether the Electrolyzer is turned on. (0 for no, 1 for yes) |- | RequiredPower || Integer || Returns the current amount of power in Watts required by the Electrolyzer. |} <!--T:6--> ==See Also== * [[Guide (Electrolyzer)]] * [[Kit (Atmospherics)]] </translate> 

Summary:

Please note that all contributions to Unofficial Stationeers Wiki may be edited, altered, or removed by other contributors. If you do not want your writing to be edited mercilessly, then do not submit it here.  
You are also promising us that you wrote this yourself, or copied it from a public domain or similar free resource (see [Unofficial Stationeers Wiki:Copyrights](/index.php?title=Unofficial_Stationeers_Wiki:Copyrights&action=edit&redlink=1 "Unofficial Stationeers Wiki:Copyrights \(page does not exist\)") for details). **Do not submit copyrighted work without permission!**

To edit this page, please answer the question that appears below ([more info](/Special:Captcha/help "Special:Captcha/help")): 

What machine can you use to craft iron frames?

[Cancel](/Kit_\(Atmospherics\)_Electrolyzer) |  [Editing help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Editing_pages) (opens in new window)

Templates used on this page: 

  * [Template:Construction stage](/Template:Construction_stage "Template:Construction stage") ([edit](/index.php?title=Template:Construction_stage&action=edit "Template:Construction stage")) 
  * [Template:Data Network Header](/Template:Data_Network_Header "Template:Data Network Header") ([edit](/index.php?title=Template:Data_Network_Header&action=edit "Template:Data Network Header")) 
  * [Template:Data Outputs](/Template:Data_Outputs "Template:Data Outputs") ([edit](/index.php?title=Template:Data_Outputs&action=edit "Template:Data Outputs")) 
  * [Template:Data Parameters](/Template:Data_Parameters "Template:Data Parameters") ([edit](/index.php?title=Template:Data_Parameters&action=edit "Template:Data Parameters")) 
  * [Template:Infobox](/Template:Infobox "Template:Infobox") ([edit](/index.php?title=Template:Infobox&action=edit "Template:Infobox")) 
  * [Template:Structurebox](/Template:Structurebox "Template:Structurebox") ([edit](/index.php?title=Template:Structurebox&action=edit "Template:Structurebox")) 
  * [Module:Infobox](/Module:Infobox "Module:Infobox") ([view source](/index.php?title=Module:Infobox&action=edit "Module:Infobox")) (protected)
  * [Module:Navbar](/Module:Navbar "Module:Navbar") ([view source](/index.php?title=Module:Navbar&action=edit "Module:Navbar")) (protected)



Retrieved from "<https://stationeers-wiki.com/Kit_(Atmospherics)_Electrolyzer>"

  * [Privacy policy](/Unofficial_Stationeers_Wiki:Privacy_policy "Unofficial Stationeers Wiki:Privacy policy")
  * [About Unofficial Stationeers Wiki](/Unofficial_Stationeers_Wiki:About "Unofficial Stationeers Wiki:About")
  * [Disclaimers](/Unofficial_Stationeers_Wiki:General_disclaimer "Unofficial Stationeers Wiki:General disclaimer")



  *   * [Powered by MediaWiki](//www.mediawiki.org/)


  *[v]: View this template
  *[t]: Discuss this template
  *[e]: Edit this template
  *[m]: This is a minor edit
  *[N]: This edit created a new page
