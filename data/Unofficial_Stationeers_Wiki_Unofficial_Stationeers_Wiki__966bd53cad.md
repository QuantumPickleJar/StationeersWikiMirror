__

# [ Unofficial Stationeers Wiki Unofficial Stationeers Wiki](/Main_Page)

__

  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Pipes "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Pipes "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Pipes&action=info "More information about this page")



  * [Log in](/index.php?title=Special:UserLogin&returnto=Pipes&returntoquery=action%3Dedit)



  * [ ![Unofficial Stationeers Wiki](/resources/assets/stationeers-wiki.png)](/Main_Page)
  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Pipes "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Pipes "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Pipes&action=info "More information about this page")



_  Actions_

  * [Page](/Pipes "View the content page \[c\]")
  * [Discussion](/index.php?title=Talk:Pipes&action=edit&redlink=1 "Discussion about the content page \[t\]")
  * [Edit](/index.php?title=Pipes&action=edit "Edit this page")
  * [History](/index.php?title=Pipes&action=history "Past revisions of this page \[h\]")



## Editing Pipes

##### 

**Warning:** You are not logged in. Your IP address will be publicly visible if you make any edits. If you **[log in](https://stationeers-wiki.com/index.php?title=Special:UserLogin&returnto=Pipes)** or **[create an account](https://stationeers-wiki.com/index.php?title=Special:CreateAccount&returnto=Pipes)** , your edits will be attributed to your username, along with other benefits. 

Anti-spam check. Do **not** fill this in!

<languages /> <translate> <!--T:1--> [[Category:Atmospherics]] {{Itembox | name = Kit (Pipe) | image = [[File:{{#setmainimage:ItemKitPipe.png}}]] | cost = 0.5g [[Iron]] | stacks = Yes, 20 | volume = 10L, 60Mpa | createdwith = [[Hydraulic Pipe Bender]] }} {{Itembox | name = Kit (Insulated Pipe) | image = [[File:{{#setmainimage:ItemKitInsulatedPipe.png}}]] | cost = 1g [[Silicon]], 1g [[Steel]] | stacks = Yes, 20 | volume = 10L, 60Mpa | createdwith = [[Hydraulic Pipe Bender]] }} Pipes are used to transport gas. Pipes are one of the possible types of inputs/outputs from a structure (the others being [[Cables]], [[Chutes]], and [[Kit (Liquid Pipe)]]). Similar to other logistic elements, a contiguous pipeline (not interrupted by valves, regulators, pumps etc.) of any length and shape will constitute a unified "pipe network". This network will always have the same pressure, temperature and mixture over its entire volume. No matter at what point of the pipe you're introducing new gases into the pipe network, they will be instantly distributed over the entire pipe. Pressure and temperature will be interpolated from the present and the introduced gases to acquire the single shared value for the entire network. Machines and devices which interact with such a network through a pipe socket '''must''' be connected via pipe segment - you cannot attach them to the pipe network using other pipe-related devices or components. You need 1x Pipe kit for every odd connection in the same grid cell, i.e. one kit for placing the basic 2-end section, one kit to add a 3rd end, and one extra for a 5-ended junction. Pipes can be uninstalled or merged using the [[Wrench]]. Uninstalling damaged pipe segments will reset their damage state. Pipes that have suffered burst due to stress can also be removed or replaced the same way, but the destroyed segment will not be recovered. === Properties === <!--T:2--> <!--T:3--> * Gas pipes have a mechanical pressure differential limit of 60,795 kPa (60 MPa). Pipes will become audibly stressed (make a noise) when the pressure difference between inside and outside the pipe is greater than 48,636 kPa (80% of the differential limit). If the pressure differential will rise further beyond the differential limit, a random pipe segment in the network (or the previously damaged segment if present) will begin to take damage continuously. If the damage on that segment reaches 100%, it bursts and exposes its contents to the outside space. Greater excess of pressure past the differential limit means greater damage per tick. * Pipes will also be stressed if a Liquid enters them. Excessive amount of liquids will lead to damage and eventual burst. For handling liquids, use [[Kit (Liquid Pipe)]] instead. <code>Stress in % = 5000 x "liters of liquid" / "pipe network volume"</code> * While having a free hand, hovering over a pipe segment allows you to inspect it, which will show you a tooltip telling if the pipe network is overpressurized, contains a liquid substance, and if the exact pipe segment is/was damaged to any of these circumstances currently or previously having a detrimental effect. * Removing segments from the middle of an existing pipe network will split it into two new networks, distributing the contents relative to their new volumes. * Removing segments from a terminal end of a pipe network will subtract the volume while maintaining the substance content. This can lead to inadverted over-pressurization and condensation, therefore it is advised to remove any content before doing this. * If the last segment of the pipe is removed, the pipe network is erased, together with any content it have held. This technically can be exploited to remove unwanted substances frome existence, but might be changed in future updates to yield a different result. Abuse at your own discretion. * Note, that any portable devices with much lower pressure differential limit (such as [[Canister]] or [[Portable Gas Tank]]) connected to the pipe network via corresponding mounting attachments will become the "weakest link" of the whole network and will always burst long before pipes would endure any stress. Mounting attachments themselves do not incur that weakness. ==Variations== <!--T:3--> Pipes can be painted individually or by the stack with a [[Spray Can]] or a loaded [[Spray Gun]]. This consumes a single 'use' of the paint either way, making it more efficient to paint a full stack before deployment. Pipes can also be stacked together regardless of color (either manually or through dismantling), which will convert them to the color of the target stack for free. ===Insulated=== Insulated pipes stop the exchange of heat between the pipe and it's surrounding environment. All intermediate devices (such as [[Pipe Valve]]s or [[Pressure Regulator]]s) are visually based on regular pipes, but have no pipe network of their own, thus will not convect any temperature either if placed between two insulated pipes. Pipes: <gallery mode='traditional'> Image: ItemPipeStraight.png | Straight Image: ItemPipeCorner.png | Corner Image: ItemPipeTJunction.png | T-Junction Image: ItemPipeCrossJunction.png | 4-Way Junction Image: ItemPipeCrossJunction5.png | 5-Way Junction Image: ItemPipeCrossJunction6.png | 6-Way Junction Image: ItemPipeCrossJunction3.png | 3-Way Corner Image: ItemPipeCrossJunction4.png | 4-Way Corner </gallery> Insulated Pipes: <gallery mode='traditional'> Image: ItemInsulatedPipeStraight.png | Straight Image: ItemInsulatedPipeCorner.png | Corner Image: ItemInsulatedPipeTJunction.png | T-Junction Image: ItemInsulatedPipeCrossJunction.png | 4-Way Junction Image: ItemInsulatedPipeCrossJunction5.png | 5-Way Junction Image: ItemInsulatedPipeCrossJunction6.png | 6-Way Junction Image: ItemInsulatedPipeCrossJunction3.png | 3-Way Corner Image: ItemInsulatedPipeCrossJunction4.png | 4-Way Corner </gallery> </translate> 

Summary:

Please note that all contributions to Unofficial Stationeers Wiki may be edited, altered, or removed by other contributors. If you do not want your writing to be edited mercilessly, then do not submit it here.  
You are also promising us that you wrote this yourself, or copied it from a public domain or similar free resource (see [Unofficial Stationeers Wiki:Copyrights](/index.php?title=Unofficial_Stationeers_Wiki:Copyrights&action=edit&redlink=1 "Unofficial Stationeers Wiki:Copyrights \(page does not exist\)") for details). **Do not submit copyrighted work without permission!**

To edit this page, please answer the question that appears below ([more info](/Special:Captcha/help "Special:Captcha/help")): 

What machine do you use to smelt ore?

[Cancel](/Pipes) |  [Editing help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Editing_pages) (opens in new window)

Templates used on this page: 

  * [Template:Infobox](/Template:Infobox "Template:Infobox") ([edit](/index.php?title=Template:Infobox&action=edit "Template:Infobox")) 
  * [Template:Itembox](/Template:Itembox "Template:Itembox") ([edit](/index.php?title=Template:Itembox&action=edit "Template:Itembox")) 
  * [Module:Infobox](/Module:Infobox "Module:Infobox") ([view source](/index.php?title=Module:Infobox&action=edit "Module:Infobox")) (protected)
  * [Module:Navbar](/Module:Navbar "Module:Navbar") ([view source](/index.php?title=Module:Navbar&action=edit "Module:Navbar")) (protected)



This page is a member of 2 hidden categories: 

  * [Category:Infobox without prefab data](/Category:Infobox_without_prefab_data "Category:Infobox without prefab data")
  * [Category:Itembox with old style recipe](/Category:Itembox_with_old_style_recipe "Category:Itembox with old style recipe")



Retrieved from "<https://stationeers-wiki.com/Pipes>"

  * [Privacy policy](/Unofficial_Stationeers_Wiki:Privacy_policy "Unofficial Stationeers Wiki:Privacy policy")
  * [About Unofficial Stationeers Wiki](/Unofficial_Stationeers_Wiki:About "Unofficial Stationeers Wiki:About")
  * [Disclaimers](/Unofficial_Stationeers_Wiki:General_disclaimer "Unofficial Stationeers Wiki:General disclaimer")



  *   * [Powered by MediaWiki](//www.mediawiki.org/)


  *[v]: View this template
  *[t]: Discuss this template
  *[e]: Edit this template
  *[m]: This is a minor edit
  *[N]: This edit created a new page
