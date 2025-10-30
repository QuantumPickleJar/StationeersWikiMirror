__

# [ Unofficial Stationeers Wiki Unofficial Stationeers Wiki](/Main_Page)

__

  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Autolathe/Data_Network "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Autolathe/Data_Network "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Autolathe/Data_Network&action=info "More information about this page")



  * [Log in](/index.php?title=Special:UserLogin&returnto=Autolathe%2FData+Network&returntoquery=action%3Dedit%26section%3DT-2)



  * [ ![Unofficial Stationeers Wiki](/resources/assets/stationeers-wiki.png)](/Main_Page)
  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Autolathe/Data_Network "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Autolathe/Data_Network "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Autolathe/Data_Network&action=info "More information about this page")



_  Actions_

  * [Page](/Autolathe/Data_Network "View the content page \[c\]")
  * [Discussion](/index.php?title=Talk:Autolathe/Data_Network&action=edit&redlink=1 "Discussion about the content page \[t\]")
  * [Edit](/index.php?title=Autolathe/Data_Network&action=edit "Edit this page")
  * [History](/index.php?title=Autolathe/Data_Network&action=history "Past revisions of this page \[h\]")



## Editing Autolathe/Data Network (section)

##### 

**Warning:** You are not logged in. Your IP address will be publicly visible if you make any edits. If you **[log in](https://stationeers-wiki.com/index.php?title=Special:UserLogin&returnto=Autolathe%2FData_Network)** or **[create an account](https://stationeers-wiki.com/index.php?title=Special:CreateAccount&returnto=Autolathe%2FData_Network)** , your edits will be attributed to your username, along with other benefits. 

Anti-spam check. Do **not** fill this in!

=== Output Data (Read) === These are all parameters, that can be read by using different means of logic. {| class="wikitable sortable" style="width:100%;" ! Parameter Name ! class="unsortable" | Data Type ! class="unsortable" | Value ! class="unsortable" | Description |- ! rowspan="2" | On | rowspan="2" | Boolean | style="text-align:center;" | 0 | The <b>Autolathe</b> is not powered. This is the same as the physical red powerswitch located on the structure. |- | style="text-align:center;" | 1 | The <b>Autolathe</b> is powered. This is the same as the physical red powerswitch located on the structure. |- ! rowspan="2" | Open | rowspan="2" | Boolean | style="text-align:center;" | 0 | Output of the <b>Autolathe</b> is closed. This is the same as the physical lever located on the structure. |- | style="text-align:center;" | 1 | Output of the <b>Autolathe</b> is opened. This is the same as the physical lever located on the structure. |- ! rowspan="2" | Activate | rowspan="2" | Boolean | style="text-align:center;" | 0 | The structure is currently producing nothing. |- | style="text-align:center;" | 1 | The structure is currently producing something. |- ! rowspan="2" | Lock | rowspan="2" | Boolean | style="text-align:center;" | 0 | 1 if device is locked, otherwise 0, can be set in most devices and prevents the user from access the values. |- | style="text-align:center;" | 1 | 1 if device is locked, otherwise 0, can be set in most devices and prevents the user from access the values. |- ! rowspan="2" | Power | rowspan="2" | Boolean | style="text-align:center;" | 0 | Can be read to return if the device is correctly powered or not, set via the power system, return 1 if powered and O if not. |- | style="text-align:center;" | 1 | Can be read to return if the device is correctly powered or not, set via the power system, return 1 if powered and O if not. |- ! rowspan="2" | Error | rowspan="2" | Boolean | style="text-align:center;" | 0 | 1 if device is in error state, otherwise 0. |- | style="text-align:center;" | 1 | 1 if device is in error state, otherwise 0. |- ! RecipeHash | Integer | | Current hash of the recipe the device is set to produce. |- ! Reagents | Integer | | Total number of reagents inside the device (e.g. 92g of iron = 92). |- ! RequiredPower | Integer | | Idle operating power quantity. Does not include extra power demanded during recipe fabrication. |- ! CompletionRatio | Integer | | How complete the current production is for this device, between 0 and 1. |- ! ExportCount | Integer | | How many items exported since last ClearMemory. This count is based on every ouput stack of items (e.g. 1 item and 12g of iron = 2). |- ! ImportCount | Integer | | How many items imported since last ClearMemory. The count is based on stacks (e.g. 92g of iron in on stack = 1). |- ! PrefabHash | Integer | | The hash of the structure. |- ! Referenceld | Integer | | Unique Reference Identifier for this object. |- ! colspan="4" | <i>Update 0.2.4677.21598 - Fri 29/12/2023</i> <span class="right">[[Autolathe/Data Network|/Data_Network]]</span> |} </div> 

Summary:

Please note that all contributions to Unofficial Stationeers Wiki may be edited, altered, or removed by other contributors. If you do not want your writing to be edited mercilessly, then do not submit it here.  
You are also promising us that you wrote this yourself, or copied it from a public domain or similar free resource (see [Unofficial Stationeers Wiki:Copyrights](/index.php?title=Unofficial_Stationeers_Wiki:Copyrights&action=edit&redlink=1 "Unofficial Stationeers Wiki:Copyrights \(page does not exist\)") for details). **Do not submit copyrighted work without permission!**

To edit this page, please answer the question that appears below ([more info](/Special:Captcha/help "Special:Captcha/help")): 

What machine do you use to smelt ore?

[Cancel](/Autolathe/Data_Network) |  [Editing help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Editing_pages) (opens in new window)

Retrieved from "<https://stationeers-wiki.com/Autolathe/Data_Network>"

  * [Privacy policy](/Unofficial_Stationeers_Wiki:Privacy_policy "Unofficial Stationeers Wiki:Privacy policy")
  * [About Unofficial Stationeers Wiki](/Unofficial_Stationeers_Wiki:About "Unofficial Stationeers Wiki:About")
  * [Disclaimers](/Unofficial_Stationeers_Wiki:General_disclaimer "Unofficial Stationeers Wiki:General disclaimer")



  *   * [Powered by MediaWiki](//www.mediawiki.org/)


  *[v]: View this template
  *[t]: Discuss this template
  *[e]: Edit this template
  *[m]: This is a minor edit
  *[N]: This edit created a new page
