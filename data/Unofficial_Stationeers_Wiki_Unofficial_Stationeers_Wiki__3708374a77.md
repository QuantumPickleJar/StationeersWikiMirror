__

# [ Unofficial Stationeers Wiki Unofficial Stationeers Wiki](/Main_Page)

__

  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Template:Itembox "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Template:Itembox "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Template:Itembox&action=info "More information about this page")



  * [Log in](/index.php?title=Special:UserLogin&returnto=Template%3AItembox&returntoquery=action%3Dedit)



  * [ ![Unofficial Stationeers Wiki](/resources/assets/stationeers-wiki.png)](/Main_Page)
  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Template:Itembox "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Template:Itembox "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Template:Itembox&action=info "More information about this page")



_  Actions_

  * [Template](/Template:Itembox "View the template \[c\]")
  * [Discussion](/Template_talk:Itembox "Discussion about the content page \[t\]")
  * [Edit](/index.php?title=Template:Itembox&action=edit "Edit this page")
  * [History](/index.php?title=Template:Itembox&action=history "Past revisions of this page \[h\]")



#### Template

## Editing Itembox

##### 

**Warning:** You are not logged in. Your IP address will be publicly visible if you make any edits. If you **[log in](https://stationeers-wiki.com/index.php?title=Special:UserLogin&returnto=Template%3AItembox)** or **[create an account](https://stationeers-wiki.com/index.php?title=Special:CreateAccount&returnto=Template%3AItembox)** , your edits will be attributed to your username, along with other benefits. 

Anti-spam check. Do **not** fill this in!

<includeonly> {{Infobox | name = Itembox | title = {{{name|}}} | image = {{{image|}}} | header19 = {{ #if: {{{stacks|}}}{{{autoignition|}}}{{{flashpoint|}}}{{{paintable|}}} | Properties <!-- \-->{{Infobox | decat = yes | child = yes | label1 = Stacks | data1 = {{#if: {{{stacks|}}} | {{#iferror: {{#expr: {{{stacks|}}}+1 }} | {{{stacks|}}} | {{#ifexpr: {{{stacks|}}} = 1 | No | Yes ({{{stacks|}}}) }} }} }} | label2 = Paintable | data2 = {{{paintable|}}} | label3 = Autoignition | data3 = {{{autoignition|}}} | label4 = Flashpoint | data4 = {{{flashpoint|}}} }} }} | label6 = Constructing Options | data6 = {{{constructs|}}} | label7 = Used With | data7 = {{{usedwith|}}} | label8 = Max Input Power | data8 = {{{maxinpower|}}} | label9 = Max Output Power | data9 = {{{maxoutpower|}}} | label10 = Max Pressure | data10 = {{{maxpressure|}}} | label11 = Pressure Range | data11 = {{{pressurerange|}}} | label12 = Max Temperature | data12 = {{{maxtemp|}}} | label13 = Temperature Range | data13 = {{{temprange|}}} | label14 = Volume | data14 = {{{volume|}}} | header20 = {{ #if: {{{createdwith|}}} | Recipe <!-- Old recipe style \-->{{Infobox | decat = yes | child = yes | label1 = Created With | data1 = {{{createdwith|}}} | label2 = Cost | data2 = {{{cost|}}} }} }} | header21 = {{ #if: {{{recipe_machine1|}}} | Recipes <!-- New recipe style \-->{{Infobox | decat = yes | child = yes | label1 = [[{{{recipe_machine1|}}}]] | data1 = {{{recipe_cost1|}}} | label4 = [[{{{recipe_machine2|}}}]] | data4 = {{{recipe_cost2|}}} | label6 = [[{{{recipe_machine3|}}}]] | data6 = {{{recipe_cost3|}}} }} }} | header22 = {{ #if: {{{logic|}}}{{{prefabhash|}}}{{{prefabname|}}}{{{slot_class|}}}{{{sorting_class|}}}{{{hashid|}}} | Logic <!-- \-->{{Infobox | decat = yes | child = yes | label1 = Item Hash | data1 = {{#if: {{{prefabhash|}}} | <span style="font-family: monospace;">{{{prefabhash|}}}</span> | {{#if: {{{hashid|}}}| <span style="font-family: monospace;">{{{hashid|}}}</span> }} }} | label2 = Item Name | data2 = {{#if: {{{prefabname|}}} | <span style="font-family: monospace;">{{{prefabname|}}}</span>}} | label3 = Logic Classes | data3 = {{#if: {{{slot_class|}}}| <div style="font-family: monospace;">{{{slot_class|}}}</div> }}{{#if: {{{sorting_class|}}}|<div style="font-family: monospace;">{{{sorting_class|}}}</div> }} | label4 = Logic Parameters | data4 = {{{logic|}}} }} }} | header23 = {{ #if: {{{nutrition|}}}{{{quality|}}}{{{growthtime|}}}{{{moodbonus|}}} | Food <!-- \-->{{Infobox | decat = yes | child = yes | label1 = Food Nutrition | data1 = {{{nutrition|}}} | label2 = Food Quality | data2 = {{{quality|}}} | label3 = Growth Time | data3 = {{{growthtime|}}} | label4 = Mood Bonus | data4 = {{{moodbonus|}}} }} }} }} [[Category:Items]] {{ #if: {{{nutrition|}}}{{{quality|}}}{{{moodbonus|}}} | [[Category:Food]] }} {{ #if: {{{constructs|}}} | [[Category:Kits]] }} {{ #if: {{{createdwith|}}}{{{cost|}}} | [[Category:Itembox with old style recipe]] }} {{ #if: {{{prefabhash|}}}{{{hashid|}}} | | [[Category:Infobox without prefab data]] }} {{ #if: {{{prefabname|}}} | | [[Category:Infobox without prefab data]] }} {{ #if: {{{slot_class|}}}{{{sorting_class|}}} | | [[Category:Itembox without logic classes]] }} {{#ifeq: {{{slot_class}}}|SlotClass.Tool|[[Category:Tools]]|}} </includeonly> <noinclude>{{Documentation}}</noinclude> 

Summary:

Please note that all contributions to Unofficial Stationeers Wiki may be edited, altered, or removed by other contributors. If you do not want your writing to be edited mercilessly, then do not submit it here.  
You are also promising us that you wrote this yourself, or copied it from a public domain or similar free resource (see [Unofficial Stationeers Wiki:Copyrights](/index.php?title=Unofficial_Stationeers_Wiki:Copyrights&action=edit&redlink=1 "Unofficial Stationeers Wiki:Copyrights \(page does not exist\)") for details). **Do not submit copyrighted work without permission!**

To edit this page, please answer the question that appears below ([more info](/Special:Captcha/help "Special:Captcha/help")): 

What gas do we need to breathe in order to survive?

[Cancel](/Template:Itembox) |  [Editing help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Editing_pages) (opens in new window)

Templates used on this page: 

  * [Template:Documentation](/Template:Documentation "Template:Documentation") ([edit](/index.php?title=Template:Documentation&action=edit "Template:Documentation")) 
  * [Template:Infobox](/Template:Infobox "Template:Infobox") ([edit](/index.php?title=Template:Infobox&action=edit "Template:Infobox")) 
  * [Template:Itembox](/Template:Itembox "Template:Itembox") ([edit](/index.php?title=Template:Itembox&action=edit "Template:Itembox")) 
  * [Template:Itembox/doc](/Template:Itembox/doc "Template:Itembox/doc") ([edit](/index.php?title=Template:Itembox/doc&action=edit "Template:Itembox/doc")) 
  * [Module:Arguments](/Module:Arguments "Module:Arguments") ([edit](/index.php?title=Module:Arguments&action=edit "Module:Arguments")) 
  * [Module:Documentation](/Module:Documentation "Module:Documentation") ([edit](/index.php?title=Module:Documentation&action=edit "Module:Documentation")) 
  * [Module:Documentation/config](/Module:Documentation/config "Module:Documentation/config") ([edit](/index.php?title=Module:Documentation/config&action=edit "Module:Documentation/config")) 
  * [Module:Infobox](/Module:Infobox "Module:Infobox") ([view source](/index.php?title=Module:Infobox&action=edit "Module:Infobox")) (protected)
  * [Module:Message box](/Module:Message_box "Module:Message box") ([edit](/index.php?title=Module:Message_box&action=edit "Module:Message box")) 
  * [Module:Message box/configuration](/Module:Message_box/configuration "Module:Message box/configuration") ([edit](/index.php?title=Module:Message_box/configuration&action=edit "Module:Message box/configuration")) 
  * [Module:Navbar](/Module:Navbar "Module:Navbar") ([view source](/index.php?title=Module:Navbar&action=edit "Module:Navbar")) (protected)
  * [Module:No globals](/Module:No_globals "Module:No globals") ([edit](/index.php?title=Module:No_globals&action=edit "Module:No globals")) 
  * [Module:Yesno](/Module:Yesno "Module:Yesno") ([edit](/index.php?title=Module:Yesno&action=edit "Module:Yesno")) 



This page is a member of 1 hidden category: 

  * [Category:Itembox with old style recipe](/Category:Itembox_with_old_style_recipe "Category:Itembox with old style recipe")



Retrieved from "<https://stationeers-wiki.com/Template:Itembox>"

  * [Privacy policy](/Unofficial_Stationeers_Wiki:Privacy_policy "Unofficial Stationeers Wiki:Privacy policy")
  * [About Unofficial Stationeers Wiki](/Unofficial_Stationeers_Wiki:About "Unofficial Stationeers Wiki:About")
  * [Disclaimers](/Unofficial_Stationeers_Wiki:General_disclaimer "Unofficial Stationeers Wiki:General disclaimer")



  *   * [Powered by MediaWiki](//www.mediawiki.org/)


  *[v]: View this template
  *[t]: Discuss this template
  *[e]: Edit this template
  *[m]: This is a minor edit
