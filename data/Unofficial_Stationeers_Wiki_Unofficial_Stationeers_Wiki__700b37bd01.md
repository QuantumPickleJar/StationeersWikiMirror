__

# [ Unofficial Stationeers Wiki Unofficial Stationeers Wiki](/Main_Page)

__

  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Kit_\(Large_Direct_Heat_Exchanger\) "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Kit_\(Large_Direct_Heat_Exchanger\) "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Kit_\(Large_Direct_Heat_Exchanger\)&action=info "More information about this page")



  * [Log in](/index.php?title=Special:UserLogin&returnto=Kit+%28Large+Direct+Heat+Exchanger%29&returntoquery=action%3Dedit)



  * [ ![Unofficial Stationeers Wiki](/resources/assets/stationeers-wiki.png)](/Main_Page)
  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Kit_\(Large_Direct_Heat_Exchanger\) "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Kit_\(Large_Direct_Heat_Exchanger\) "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Kit_\(Large_Direct_Heat_Exchanger\)&action=info "More information about this page")



_  Actions_

  * [Page](/Kit_\(Large_Direct_Heat_Exchanger\) "View the content page \[c\]")
  * [Discussion](/index.php?title=Talk:Kit_\(Large_Direct_Heat_Exchanger\)&action=edit&redlink=1 "Discussion about the content page \[t\]")
  * [Edit](/index.php?title=Kit_\(Large_Direct_Heat_Exchanger\)&action=edit "Edit this page")
  * [History](/index.php?title=Kit_\(Large_Direct_Heat_Exchanger\)&action=history "Past revisions of this page \[h\]")



## Editing Kit (Large Direct Heat Exchanger)

##### 

**Warning:** You are not logged in. Your IP address will be publicly visible if you make any edits. If you **[log in](https://stationeers-wiki.com/index.php?title=Special:UserLogin&returnto=Kit_%28Large_Direct_Heat_Exchanger%29)** or **[create an account](https://stationeers-wiki.com/index.php?title=Special:CreateAccount&returnto=Kit_%28Large_Direct_Heat_Exchanger%29)** , your edits will be attributed to your username, along with other benefits. 

Anti-spam check. Do **not** fill this in!

[[Category:Atmospherics]] {{Itembox | name = Kit (Large Direct Heat Exchanger) | image = | stacks = No | paintable = Yes | constructs = '''Large Direct Geat Exchanger -<br>Gas + Gas''',<br> '''Large Direct Geat Exchanger -<br>Gas + Liquid''',<br> '''Large Direct Geat Exchanger -<br>Liquid + Liquid''' | createdwith = [[Hydraulic Pipe Bender]] Tier two | cost = 10g [[Steel]], 10g [[Invar]] | prefabhash = 450164077 | prefabname = ItemKitLargeDirectHeatExchanger | slot_class = | sorting_class = }} {{Structurebox | name = Large Direct Geat Exchanger -<br> Gas + Gas [[File:Stationeers large direct heat exchanger gas to gas.png|In-game screenshot showing the exhchanger gas pipe inputs]] Large Direct Heat Exchanger -<br> Gas + Liquid [[File:Stationeers large direct heat exchanger liquid to gas.png|In-game screenshot showing the exhchanger different pipe inputs]] Large Direct Heat Exchanger -<br> Liquid + Liquid [[File:Stationeers large direct heat exchanger liquid to liquid.png|In-game screenshot showing the exhchanger liquid pipe inputs]] | prefab_hash = Varies | prefab_name = Varies | placed_with_item = '''Kit (Large Direct Heat Exchanger)''' | placed_on_grid = Small Grid | const_with_tool1 = [[Wrench]] | const_with_item1 = [[Kit (Pipe)]] x1 | decon_with_tool1 = [[Hand Drill]] | item_rec1 = '''Kit (Large Direct Heat Exchanger)''' | const_with_tool2 = [[Welder]] | const_with_item2 = [[Steel Sheets]] x1 | decon_with_tool2 = [[Hand Drill]] | item_rec2 = [[Kit (Pipe)]] x1 | const_with_tool3 = | const_with_item3 = | decon_with_tool3 = [[Hand Drill]] | item_rec3 = [[Steel Sheets]] x1 }} ==Description== <blockquote><q> Direct Heat Exchangers equalize the temperature of the two input networks. </q><br> '''- Stationpedia'''</blockquote> Exchanges heat between two pipe networks very quickly, ~10x as fast as the [[Kit (Small Direct Heat Exchanger)‏‎|Small Direct Heat Exchanger]]. It's counterpart is the [[Kit (Counterflow Heat Exchanger)‏‎|Counterflow Heat Exchanger]]. <small><sub>pun intended</sub></small> ==Usage== It's purpose is to equalize the temperature of two pipe networks without allowing their contents to mix. <br> The heat exchanger does not have an internal volume and instead transfers heat directly between the two input pipe networks. A meter on the side displays the heat exchange rate in joules per tick. ===Heat Transfer=== Heat will flow from warmer to colder at a rate that increases with a greater difference in temperature. Newton's law of cooling can be used to approximate the rate of heat transfer according to the equation:<br> Rate = k(T<sub>1</sub>-T<sub>2</sub>)<br> Where: <br> k = 425 Heat Exchange constant ''(Rough estimate)''<br> T<sub>1</sub> = Input 1 Temperature <br> T<sub>2</sub> = Input 2 Temperature <br> == Notes == * It has no logic port * Requires frame support, unlike the small heat exchanger * In older versions, [[Kit (Heat Exchanger)|heat exchangers]] had 2 inputs and 2 outputs intended for active liquid flow. This feature has been consolidated in the form of the [[Kit (Counterflow Heat Exchanger)|counterflow heat exchanger]] === Prefab Information === {| class="wikitable" |- ! !! Prefab Hash !! Prefab Name |- | Gas to Gas ||-1230658883||StructureLargeDirectHeatExchangeGastoGas |- | Gas to Liquid ||1412338038||StructureLargeDirectHeatExchangeGastoLiquid |- | Liquid to Liquid ||792686502||StructureLargeDirectHeatExchangeLiquidtoLiquid |} 

Summary:

Please note that all contributions to Unofficial Stationeers Wiki may be edited, altered, or removed by other contributors. If you do not want your writing to be edited mercilessly, then do not submit it here.  
You are also promising us that you wrote this yourself, or copied it from a public domain or similar free resource (see [Unofficial Stationeers Wiki:Copyrights](/index.php?title=Unofficial_Stationeers_Wiki:Copyrights&action=edit&redlink=1 "Unofficial Stationeers Wiki:Copyrights \(page does not exist\)") for details). **Do not submit copyrighted work without permission!**

To edit this page, please answer the question that appears below ([more info](/Special:Captcha/help "Special:Captcha/help")): 

What machine do you use to smelt ore?

[Cancel](/Kit_\(Large_Direct_Heat_Exchanger\)) |  [Editing help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Editing_pages) (opens in new window)

Templates used on this page: 

  * [Template:Construction stage](/Template:Construction_stage "Template:Construction stage") ([edit](/index.php?title=Template:Construction_stage&action=edit "Template:Construction stage")) 
  * [Template:Infobox](/Template:Infobox "Template:Infobox") ([edit](/index.php?title=Template:Infobox&action=edit "Template:Infobox")) 
  * [Template:Itembox](/Template:Itembox "Template:Itembox") ([edit](/index.php?title=Template:Itembox&action=edit "Template:Itembox")) 
  * [Template:Structurebox](/Template:Structurebox "Template:Structurebox") ([edit](/index.php?title=Template:Structurebox&action=edit "Template:Structurebox")) 
  * [Module:Infobox](/Module:Infobox "Module:Infobox") ([view source](/index.php?title=Module:Infobox&action=edit "Module:Infobox")) (protected)
  * [Module:Navbar](/Module:Navbar "Module:Navbar") ([view source](/index.php?title=Module:Navbar&action=edit "Module:Navbar")) (protected)



This page is a member of 1 hidden category: 

  * [Category:Itembox with old style recipe](/Category:Itembox_with_old_style_recipe "Category:Itembox with old style recipe")



Retrieved from "<https://stationeers-wiki.com/Kit_(Large_Direct_Heat_Exchanger)>"

  * [Privacy policy](/Unofficial_Stationeers_Wiki:Privacy_policy "Unofficial Stationeers Wiki:Privacy policy")
  * [About Unofficial Stationeers Wiki](/Unofficial_Stationeers_Wiki:About "Unofficial Stationeers Wiki:About")
  * [Disclaimers](/Unofficial_Stationeers_Wiki:General_disclaimer "Unofficial Stationeers Wiki:General disclaimer")



  *   * [Powered by MediaWiki](//www.mediawiki.org/)


  *[v]: View this template
  *[t]: Discuss this template
  *[e]: Edit this template
  *[m]: This is a minor edit
  *[N]: This edit created a new page
