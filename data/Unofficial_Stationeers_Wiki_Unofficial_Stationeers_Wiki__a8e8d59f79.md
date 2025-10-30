__

# [ Unofficial Stationeers Wiki Unofficial Stationeers Wiki](/Main_Page)

__

  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Ice_Crusher "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Ice_Crusher "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Ice_Crusher&action=info "More information about this page")



  * [Log in](/index.php?title=Special:UserLogin&returnto=Ice+Crusher&returntoquery=action%3Dedit)



  * [ ![Unofficial Stationeers Wiki](/resources/assets/stationeers-wiki.png)](/Main_Page)
  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Ice_Crusher "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Ice_Crusher "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Ice_Crusher&action=info "More information about this page")



_  Actions_

  * [Page](/Ice_Crusher "View the content page \[c\]")
  * [Discussion](/index.php?title=Talk:Ice_Crusher&action=edit&redlink=1 "Discussion about the content page \[t\]")
  * [Edit](/index.php?title=Ice_Crusher&action=edit "Edit this page")
  * [History](/index.php?title=Ice_Crusher&action=history "Past revisions of this page \[h\]")



## Editing Ice Crusher

##### 

**Warning:** You are not logged in. Your IP address will be publicly visible if you make any edits. If you **[log in](https://stationeers-wiki.com/index.php?title=Special:UserLogin&returnto=Ice_Crusher)** or **[create an account](https://stationeers-wiki.com/index.php?title=Special:CreateAccount&returnto=Ice_Crusher)** , your edits will be attributed to your username, along with other benefits. 

Anti-spam check. Do **not** fill this in!

[[Category:Items]] [[Category:Atmospherics]] {{Itembox | name = Kit (Ice Crusher) | image = [[File:ItemKitIceCrusher.png]] | maxpressure = | volume = | createdwith = [[Hydraulic Pipe Bender]] | cost = 3g [[Iron Ingot]], 1g [[Gold Ingot]], 1g [[Copper Ingot]] }} {{Structurebox | name = Ice Crusher | image = [[File:StructureIceCrusher.png]] | power_usage = 10W standby + 1.0kW crushing | build states = Three | placed_with_item = [[Kit (Ice Crusher)]] | placed_on_grid = Small Grid | const_with_tool1 = [[Welding Torch]] | const_with_item1 = 1x [[Iron Sheets]] | const_with_item2 = 2x [[Cable Coil]] }} {{Itembox | name = Overall Ice Crusher Cost/Requirements | image = [[File:StructureIceCrusher.png]] | createdwith = [[Hydraulic Pipe Bender]], [[Autolathe]] | cost = 1g [[Gold Ingot]], 2g [[Copper Ingot]], 5g [[Iron Ingot]] }} ==Description== This kit is used to crush ice into liquids and/or gases. The Ice Crusher has two outputs at the back. The top port can be connected to [[Pipes]] (yellow) and the lower port can be connected to [[Kit (Liquid Pipe)|Liquid Pipe]] (blue) to extract the products. The top pipe output is for Gas, and the lower pipe output is for Liquids. Different kinds of Ice can be crushed: :[[Ice (Water)]] produces liquid Water and [[Nitrogen]] gas (80% water, 20% nitrogen) :[[Ice (Oxite)]] produces [[Oxygen]] and [[Nitrogen]] gas (90% Oxygen, 10% nitrogen) :[[Ice (Volatiles)]] produces [[Hydrogen]] gas (100% Hydrogen) :[[Ice (Nitrice)]] produces [[Nitrogen]] and [[Nitrous_Oxide]] gas (90% Nitrogen, 10% Nitrous Oxide) ==Refilling Water Bottles Early Game== The ice crusher can be used to get drinkable water early on, by connecting it to a [[Water Bottle Filler]] using [[Kit (Liquid Pipe)|Liquid Pipe]] and piping the [[Nitrogen]] out with a pump or an [[Active Vent]] to avoid blocking the ice crusher. Note however that if done inside, this could lead to pressure accumulating over time, which could be dangerous if not eventually upgraded to a more robust gas handling system. [[File:Ice Crusher Front View.jpg|thumb|Ice Crusher Front View (liquid pipe middle back, and gas pipe top.)]] {{Data Network Header}} {{Data Parameters}} {| class="wikitable" |- ! Parameter Name !! Data Type !! Description |- | Lock || Boolean || One(1) is locked, where as zero(0) is not locked |- | Setting || Integer || Temperature of the output in degrees kelvin |- | On || Boolean || One(1) is On, where as zero(0) is off |- |} {{Data Outputs}} {| class="wikitable" |- ! Output Name !! Data Type !! Description |- | Maximum || Integer || |- | Lock || Boolean || One(1) is locked, where as zero(0) is not locked |- | ImportCount || Integer || |- | Error || |- | Activate || |- | Setting || Integer || Temperature of the output in degrees kelvin |- | RequiredPower || Integer || |- | Ratio || Integer || |- | Prefabhash || - || 443849486 |- | Power || Boolean || One(1) is on, where as zero (0) is off |- | On || Boolean || One(1) is on, where as zero (0) is off |} ==Notes== * It can be safely used in higher temperature environments if the ice is transferred instantly into the crusher from the mining belt. * When using it for crushing [[Ice (Water)]], 20% [[Nitrogen]] gas is still produced, and care must be taken to avoid overpressurization over time. * It is insulated, so only the built in heater and the addition of gases from melting ice can change its internal temperature. * Must be kept turned on to release the liquids and/or gases it contains. * Has an internal capacity of 200L. * Will not explode from overpressure of its internal capacity, but will stop crushing ice and flash an error if its internal pressure exceeds 125 MPa. It will resume crushing once its internal pressure drops below approximately 121 MPa. * Outputs gas at a maximum rate of 9.231 MPa per tick into a single pipe segment (exactly 20 MPa into 6 pipe segments every 13 ticks), stopping once its internal pressure equals the pressure of the output port. This drops its internal pressure by 0.4615 MPa per tick. * Can generate gas from crushing ice substantially faster than its maximum gas output rate, at a rate of approximately 5 MPa to its internal capacity per tick spent crushing ice. * Changing the 'Setting' Value (represented in degrees kelvin) with IC/Logic circuits can dramatically speed up crushing times. For example, I changed my volatiles crusher from the default value to 273k(ice crusher are capped at 0°C/273.5k) and was able to process a stack of 50 volatiles in only 5 seconds. 

Summary:

Please note that all contributions to Unofficial Stationeers Wiki may be edited, altered, or removed by other contributors. If you do not want your writing to be edited mercilessly, then do not submit it here.  
You are also promising us that you wrote this yourself, or copied it from a public domain or similar free resource (see [Unofficial Stationeers Wiki:Copyrights](/index.php?title=Unofficial_Stationeers_Wiki:Copyrights&action=edit&redlink=1 "Unofficial Stationeers Wiki:Copyrights \(page does not exist\)") for details). **Do not submit copyrighted work without permission!**

To edit this page, please answer the question that appears below ([more info](/Special:Captcha/help "Special:Captcha/help")): 

What gas do we need to breathe in order to survive?

[Cancel](/Ice_Crusher) |  [Editing help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Editing_pages) (opens in new window)

Templates used on this page: 

  * [Template:Construction stage](/Template:Construction_stage "Template:Construction stage") ([edit](/index.php?title=Template:Construction_stage&action=edit "Template:Construction stage")) 
  * [Template:Data Network Header](/Template:Data_Network_Header "Template:Data Network Header") ([edit](/index.php?title=Template:Data_Network_Header&action=edit "Template:Data Network Header")) 
  * [Template:Data Outputs](/Template:Data_Outputs "Template:Data Outputs") ([edit](/index.php?title=Template:Data_Outputs&action=edit "Template:Data Outputs")) 
  * [Template:Data Parameters](/Template:Data_Parameters "Template:Data Parameters") ([edit](/index.php?title=Template:Data_Parameters&action=edit "Template:Data Parameters")) 
  * [Template:Infobox](/Template:Infobox "Template:Infobox") ([edit](/index.php?title=Template:Infobox&action=edit "Template:Infobox")) 
  * [Template:Itembox](/Template:Itembox "Template:Itembox") ([edit](/index.php?title=Template:Itembox&action=edit "Template:Itembox")) 
  * [Template:Structurebox](/Template:Structurebox "Template:Structurebox") ([edit](/index.php?title=Template:Structurebox&action=edit "Template:Structurebox")) 
  * [Module:Infobox](/Module:Infobox "Module:Infobox") ([view source](/index.php?title=Module:Infobox&action=edit "Module:Infobox")) (protected)
  * [Module:Navbar](/Module:Navbar "Module:Navbar") ([view source](/index.php?title=Module:Navbar&action=edit "Module:Navbar")) (protected)



This page is a member of 2 hidden categories: 

  * [Category:Infobox without prefab data](/Category:Infobox_without_prefab_data "Category:Infobox without prefab data")
  * [Category:Itembox with old style recipe](/Category:Itembox_with_old_style_recipe "Category:Itembox with old style recipe")



Retrieved from "<https://stationeers-wiki.com/Ice_Crusher>"

  * [Privacy policy](/Unofficial_Stationeers_Wiki:Privacy_policy "Unofficial Stationeers Wiki:Privacy policy")
  * [About Unofficial Stationeers Wiki](/Unofficial_Stationeers_Wiki:About "Unofficial Stationeers Wiki:About")
  * [Disclaimers](/Unofficial_Stationeers_Wiki:General_disclaimer "Unofficial Stationeers Wiki:General disclaimer")



  *   * [Powered by MediaWiki](//www.mediawiki.org/)


  *[v]: View this template
  *[t]: Discuss this template
  *[e]: Edit this template
  *[m]: This is a minor edit
  *[N]: This edit created a new page
