__

# [ Unofficial Stationeers Wiki Unofficial Stationeers Wiki](/Main_Page)

__

  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Template:Data_Parameters "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Template:Data_Parameters "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Template:Data_Parameters&action=info "More information about this page")



  * [Log in](/index.php?title=Special:UserLogin&returnto=Template%3AData+Parameters&returntoquery=action%3Dedit%26section%3DT-1)



  * [ ![Unofficial Stationeers Wiki](/resources/assets/stationeers-wiki.png)](/Main_Page)
  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Template:Data_Parameters "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Template:Data_Parameters "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Template:Data_Parameters&action=info "More information about this page")



_  Actions_

  * [Template](/Template:Data_Parameters "View the template \[c\]")
  * [Discussion](/index.php?title=Template_talk:Data_Parameters&action=edit&redlink=1 "Discussion about the content page \[t\]")
  * [Edit](/index.php?title=Template:Data_Parameters&action=edit "Edit this page")
  * [History](/index.php?title=Template:Data_Parameters&action=history "Past revisions of this page \[h\]")



#### Template

## Editing Data Parameters (section)

##### 

**Warning:** You are not logged in. Your IP address will be publicly visible if you make any edits. If you **[log in](https://stationeers-wiki.com/index.php?title=Special:UserLogin&returnto=Template%3AData_Parameters)** or **[create an account](https://stationeers-wiki.com/index.php?title=Special:CreateAccount&returnto=Template%3AData_Parameters)** , your edits will be attributed to your username, along with other benefits. 

Anti-spam check. Do **not** fill this in!

=== Data Parameters === {{#if: {{{1|}}} |{{#if:{{{skip_intro|}}}||These are all parameters that can be written with a [[Kit_(Logic_I/O)#Logic_Writer|Logic Writer]], [[Kit_(Logic_I/O)#Batch_Writer|Batch Writer]], or [[Integrated Circuit (IC10)]], and can be read with a [[Kit_(Logic_I/O)#Logic_Reader|Logic Reader]], [[Kit_(Logic_I/O)#Batch_Reader|Batch Reader]], or [[Integrated Circuit (IC10)]].}} <div class="mw-customtoggle-datanetworkproperties-{{PAGENAMEE}}" style="width:auto; overflow:auto; text-indent:10px; border: 2px solid #253C60; border-radius:10px;"><b>Click here to see/hide all the <span style="color:#E57125;">data network properties</span></b></div> <div class="mw-collapsible mw-collapsed" id="mw-customcollapsible-datanetworkproperties-{{PAGENAMEE}}"> {{{!}} class="wikitable sortable large" ! Parameter Name ! Data Type ! Access ! class="unsortable" {{!}} Value ! class="unsortable" colspan=2 {{!}} Description {{!}}- {{Ifnotempty|{{{1|}}}| {{{1}}} }} {{!}}} </div> |{{#if: {{{empty|}}}|This device does not have any logic parameters and can not be selected with a [[Kit_(Logic_I/O)#Logic_Writer|Logic Writer]] or a [[Kit_(Logic_I/O)#Batch_Writer|Batch Writer]].| These are all parameters that can be written with a [[Kit_(Logic_I/O)#Logic_Writer|Logic Writer]], [[Kit_(Logic_I/O)#Batch_Writer|Batch Writer]], or [[Integrated Circuit (IC10)]]. }} }} {{#if: {{{empty|}}}||{{#if: {{{1|}}}| [[Category:Data Network]] }} }} <noinclude> {{Documentation}} <!-- Categories go on the /doc subpage, and interwikis go on Wikidata. --> {{Data Parameters| {{Data Parameters/row|Power|Boolean|w=0|Can be read to return if the device is correctly powered or not, set via the power system, return 1 if powered and 0 if not|multiple=2|0|Off|1|On}} {{Data Parameters/row|Mode|Integer|The mode of the Sorter, '''Split''' does alternate outputs, '''Filter''' decides output via [[Motherboard (Sorter)]], '''Logic''' determines output via parameter '''Output'''|multiple=3|0|Split|1|Filter|2|Logic}} {{Data Parameters/row|Error|Boolean|w=0|1 if device is in error state, otherwise 0|multiple=2|0|<p></p>|1|Error}} {{Data Parameters/row|Lock|Boolean|Disable manual operation of the Sorter.|multiple=2|0|Unlocked|1|Locked}} {{Data Parameters/row|On|Integer|The current state of the Sorter.|multiple=2|0|On|1|Off}} {{Data Parameters/row|RequiredPower|Integer|w=0|Idle operating power quantity, does not necessarily include extra demand power}} {{Data Parameters/row|ClearMemory|Integer|r=0|When set to 1, clears the counter memory (e.g. ExportCount). Will set itself back to 0 when actioned}} {{Data Parameters/row|ExportCount|Integer|w=0|How many items exported since last ClearMemory}} {{Data Parameters/row|ImportCount|Integer|w=0|How many items imported since last ClearMemory}} {{Data Parameters/row|Output|Integer|In Logic mode, decides which side the next item will be sent to. (defaults to -1 after action)|multiple=3|-1|Unset|0|Straight|1|Side}} {{Data Parameters/row|PrefabHash|Integer|w=0|The hash of the structure}} {{Data Parameters/row|ReferenceId|Integer|w=0|Unique Reference Identifier for this object}} {{Data Parameters/row|NameHash|Integer|w=0|Provides the hash value for the name of the object as a 32 bit integer.}} }} </noinclude> 

Summary:

Please note that all contributions to Unofficial Stationeers Wiki may be edited, altered, or removed by other contributors. If you do not want your writing to be edited mercilessly, then do not submit it here.  
You are also promising us that you wrote this yourself, or copied it from a public domain or similar free resource (see [Unofficial Stationeers Wiki:Copyrights](/index.php?title=Unofficial_Stationeers_Wiki:Copyrights&action=edit&redlink=1 "Unofficial Stationeers Wiki:Copyrights \(page does not exist\)") for details). **Do not submit copyrighted work without permission!**

To edit this page, please answer the question that appears below ([more info](/Special:Captcha/help "Special:Captcha/help")): 

What game is this wiki for?

[Cancel](/Template:Data_Parameters) |  [Editing help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Editing_pages) (opens in new window)

Retrieved from "<https://stationeers-wiki.com/Template:Data_Parameters>"

  * [Privacy policy](/Unofficial_Stationeers_Wiki:Privacy_policy "Unofficial Stationeers Wiki:Privacy policy")
  * [About Unofficial Stationeers Wiki](/Unofficial_Stationeers_Wiki:About "Unofficial Stationeers Wiki:About")
  * [Disclaimers](/Unofficial_Stationeers_Wiki:General_disclaimer "Unofficial Stationeers Wiki:General disclaimer")



  *   * [Powered by MediaWiki](//www.mediawiki.org/)


  *[v]: View this template
  *[t]: Discuss this template
  *[e]: Edit this template
  *[m]: This is a minor edit
  *[N]: This edit created a new page
