__

# [ Unofficial Stationeers Wiki Unofficial Stationeers Wiki](/Main_Page)

__

  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Fabricator "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Fabricator "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Fabricator&action=info "More information about this page")



  * [Log in](/index.php?title=Special:UserLogin&returnto=Fabricator&returntoquery=action%3Dedit)



  * [ ![Unofficial Stationeers Wiki](/resources/assets/stationeers-wiki.png)](/Main_Page)
  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Fabricator "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Fabricator "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Fabricator&action=info "More information about this page")



_  Actions_

  * [Page](/Fabricator "View the content page \[c\]")
  * [Discussion](/Talk:Fabricator "Discussion about the content page \[t\]")
  * [Edit](/index.php?title=Fabricator&action=edit "Edit this page")
  * [History](/index.php?title=Fabricator&action=history "Past revisions of this page \[h\]")



## Editing Fabricator

##### 

**Warning:** You are not logged in. Your IP address will be publicly visible if you make any edits. If you **[log in](https://stationeers-wiki.com/index.php?title=Special:UserLogin&returnto=Fabricator)** or **[create an account](https://stationeers-wiki.com/index.php?title=Special:CreateAccount&returnto=Fabricator)** , your edits will be attributed to your username, along with other benefits. 

Anti-spam check. Do **not** fill this in!

{{deprecated|0.2.2479.11384}}[[Category:Deprecated]] <languages /> <translate> <!--T:1--> {{Itembox | name = Kit (Fabricator) | image = [[File:ItemKitFabricator.png]] | stacks = No | createdwith = Fabricator | cost = 30g Iron, 5g Gold, 20g Copper }} {{Structurebox | name = Fabricator | image = [[File:Fabricator.jpg]] | power_usage = 50W + Recipe Usage | placed_with_item = Kit (Fabricator) | placed_on_grid = Small Grid | decon_with_tool1 = Hand Drill | item_rec1 = Kit (Fabricator) }} <!--T:2--> Note: The Fabricator was removed from the survival mode in version 0.2.2479.11384. Available in [[Creative Mode]] only via the spawn menu ('/' key by default). The [[Fabricator]] is an advanced machine used to manufacture most of the craftable items in the game. It largely fills the role of the [[Autolathe]], [[Electronics Printer]], [[Hydraulic Pipe Bender]], [[Tool Manufactory]] and [[Security Printer]]. However at current version one can not search a recipe like other dedicated printers, making it less convenient. It also manufactures certain items slower then the dedicated printers. For example, it's much faster to print a [[Cable Coil|cable coil]] using [[Electronics Printer|electronics printer]] than using a fabricator. == Usage == <!--T:3--> In order to use the fabricator, you will need to set up a [[Computer]] with a [[Motherboard (Manufacturing)]] and connect it to the fabricator's data port. You can then use the manufacturing interface in order to request manufacturing jobs from the fabricator. You can choose the quantity of each item you want to build and set up a queue of items to be manufactured. If the fabricator is unable to finish an item, it will idle until it is able to continue (materials are added or power is resumed). ''Fabricator with computer hooked up''<br> [[File:Fabricator_computer.jpg|Fabricator with computer hooked up]] == Recipes == <!--T:4--> '''Used to create:''' <div style="column-count:3;-moz-column-count:3;-webkit-column-count:3"> * [[Cables|Cable Coil]] * [[Chutes|Construction Kit (Chutes)]] * [[Pipes|Construction Kit (Pipe)]] * [[Kit (Wall)]] * [[Floor Grating]] * [[Glass Sheets]] * [[Iron Frames]] * [[Iron Sheets]] * [[Kit (Arc Furnace)]] * [[Autolathe|Kit (Autolathe)]] * [[Kit (Door)]] * [[Electronics Printer|Kit (Electronics Printer)]] * [[Furnace|Kit (Furnace)]] * [[Hydraulic Pipe Bender|Kit (Hydraulic Pipe Bender)]] * [[Iron Walls|Kit (Iron Walls)]] * [[Locker|Kit (Locker)]] * [[Stairs|Kit (Stairs)]] * [[Tool Manufactory|Kit (Tool Manufactory)]] * [[Steel Frames]] * [[Steel Sheets]] * [[Kit (Lights)]] * '''And many more!''' </div> '''UNABLE to create:''' <div style="column-count:3;-moz-column-count:3;-webkit-column-count:3"> * [[Spray Paint | Any paints]] (use [[Tool Manufactory]]) * [[Portable Tank]] (use [[Hydraulic Pipe Bender]]) * [[Portable Light]] (use [[Electronics Printer]]) * [[Ground Penetrating Radar]] (use [[Electronics Printer]]) * [[Plastic Sheets]] (use [[Autolathe]]) * '''And some more!''' </div> {{Data Network Header}} {{Data Parameters}} {| class="wikitable" |- ! Parameter Name !! Data Type !! Description |- | Lock || Boolean || Locks the Fabricator, when set to 1. Unlocks it when set to 0. |- | ClearMemory || Boolean || Writing on this Parameter will reset the ExportCount and ImportCount values to zero. Will set itself back to 0 when actioned. |- | Activate || Boolean || Activates the Fabricator, when set to 1. Deactivates it, when set to 0. |- | Open || Boolean || Opens the Fabricator, when set to 1. Closes it, when set to 0. |- | On || Boolean || Turns the Fabricator on, when set to 1. Turns it off, when set to 0. |} {{Data Outputs}} {| class="wikitable" |- ! Output Name !! Data Type !! Description |- | Open || Boolean || Returns whether the Fabricator is open. (0 for no, 1 for yes) |- | On || Boolean || Returns whether the Fabricator is turned on. (0 for no, 1 for yes) |- | Lock || Boolean || Returns whether the Fabricator is locked. (0 for no, 1 for yes) |- | ImportCount || Integer || How many items imported since last ClearMemory. |- | ExportCount || Integer || How many items exported since last ClearMemory. |- | Error || Boolean || Returns whether the Fabricator is flashing an error. (0 for no, 1 for yes) |- | Activate || Boolean || Returns whether the Fabricator is active. (0 for no, 1 for yes) |- | RequiredPower || Integer || The amount of power, currently needed by the Fabricator, in Watts. |- | RecipeHash || Integer || Current hash of the recipe the device is set to produce. |- | Reagents || Float || Returns the amount of reagent contents in the Fabricator in grams. |- | PrefabHash|| Integer || The hash of the structure. |- | Power || Boolean || Returns whether the Fabricator is turned on and receives power. (0 for no, 1 for yes) |} == Bugs == * If the Fabricator is deconstructed while fabricating an item, the complete [''glowing!''] item will be left behind along with any other reagents in the Fabricator. * If the Fabricator is opened while fabricating an item (paused and unpaused), it will not drop any reagents it holds. </translate> 

Summary:

Please note that all contributions to Unofficial Stationeers Wiki may be edited, altered, or removed by other contributors. If you do not want your writing to be edited mercilessly, then do not submit it here.  
You are also promising us that you wrote this yourself, or copied it from a public domain or similar free resource (see [Unofficial Stationeers Wiki:Copyrights](/index.php?title=Unofficial_Stationeers_Wiki:Copyrights&action=edit&redlink=1 "Unofficial Stationeers Wiki:Copyrights \(page does not exist\)") for details). **Do not submit copyrighted work without permission!**

To edit this page, please answer the question that appears below ([more info](/Special:Captcha/help "Special:Captcha/help")): 

What gas do we need to breathe in order to survive?

[Cancel](/Fabricator) |  [Editing help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Editing_pages) (opens in new window)

Templates used on this page: 

  * [Template:Construction stage](/Template:Construction_stage "Template:Construction stage") ([edit](/index.php?title=Template:Construction_stage&action=edit "Template:Construction stage")) 
  * [Template:Data Network Header](/Template:Data_Network_Header "Template:Data Network Header") ([edit](/index.php?title=Template:Data_Network_Header&action=edit "Template:Data Network Header")) 
  * [Template:Data Outputs](/Template:Data_Outputs "Template:Data Outputs") ([edit](/index.php?title=Template:Data_Outputs&action=edit "Template:Data Outputs")) 
  * [Template:Data Parameters](/Template:Data_Parameters "Template:Data Parameters") ([edit](/index.php?title=Template:Data_Parameters&action=edit "Template:Data Parameters")) 
  * [Template:Deprecated](/Template:Deprecated "Template:Deprecated") ([edit](/index.php?title=Template:Deprecated&action=edit "Template:Deprecated")) 
  * [Template:Dir](/index.php?title=Template:Dir&action=edit&redlink=1 "Template:Dir \(page does not exist\)") ([edit](/index.php?title=Template:Dir&action=edit "Template:Dir \(page does not exist\)")) 
  * [Template:Infobox](/Template:Infobox "Template:Infobox") ([edit](/index.php?title=Template:Infobox&action=edit "Template:Infobox")) 
  * [Template:Itembox](/Template:Itembox "Template:Itembox") ([edit](/index.php?title=Template:Itembox&action=edit "Template:Itembox")) 
  * [Template:Structurebox](/Template:Structurebox "Template:Structurebox") ([edit](/index.php?title=Template:Structurebox&action=edit "Template:Structurebox")) 
  * [Template:Warning](/Template:Warning "Template:Warning") ([edit](/index.php?title=Template:Warning&action=edit "Template:Warning")) 
  * [Module:Infobox](/Module:Infobox "Module:Infobox") ([view source](/index.php?title=Module:Infobox&action=edit "Module:Infobox")) (protected)
  * [Module:Navbar](/Module:Navbar "Module:Navbar") ([view source](/index.php?title=Module:Navbar&action=edit "Module:Navbar")) (protected)



This page is a member of 2 hidden categories: 

  * [Category:Infobox without prefab data](/Category:Infobox_without_prefab_data "Category:Infobox without prefab data")
  * [Category:Itembox with old style recipe](/Category:Itembox_with_old_style_recipe "Category:Itembox with old style recipe")



Retrieved from "<https://stationeers-wiki.com/Fabricator>"

  * [Privacy policy](/Unofficial_Stationeers_Wiki:Privacy_policy "Unofficial Stationeers Wiki:Privacy policy")
  * [About Unofficial Stationeers Wiki](/Unofficial_Stationeers_Wiki:About "Unofficial Stationeers Wiki:About")
  * [Disclaimers](/Unofficial_Stationeers_Wiki:General_disclaimer "Unofficial Stationeers Wiki:General disclaimer")



  *   * [Powered by MediaWiki](//www.mediawiki.org/)


  *[v]: View this template
  *[t]: Discuss this template
  *[e]: Edit this template
  *[m]: This is a minor edit
  *[N]: This edit created a new page
