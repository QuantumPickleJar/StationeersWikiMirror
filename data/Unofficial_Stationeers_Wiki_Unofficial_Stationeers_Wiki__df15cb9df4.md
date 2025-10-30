__

# [ Unofficial Stationeers Wiki Unofficial Stationeers Wiki](/Main_Page)

__

  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Autolathe/Internal_Memory "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Autolathe/Internal_Memory "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Autolathe/Internal_Memory&action=info "More information about this page")



  * [Log in](/index.php?title=Special:UserLogin&returnto=Autolathe%2FInternal+Memory&returntoquery=action%3Dedit%26section%3DT-1)



  * [ ![Unofficial Stationeers Wiki](/resources/assets/stationeers-wiki.png)](/Main_Page)
  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Autolathe/Internal_Memory "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Autolathe/Internal_Memory "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Autolathe/Internal_Memory&action=info "More information about this page")



_  Actions_

  * [Page](/Autolathe/Internal_Memory "View the content page \[c\]")
  * [Discussion](/index.php?title=Talk:Autolathe/Internal_Memory&action=edit&redlink=1 "Discussion about the content page \[t\]")
  * [Edit](/index.php?title=Autolathe/Internal_Memory&action=edit "Edit this page")
  * [History](/index.php?title=Autolathe/Internal_Memory&action=history "Past revisions of this page \[h\]")



## Editing Autolathe/Internal Memory (section)

##### 

**Warning:** You are not logged in. Your IP address will be publicly visible if you make any edits. If you **[log in](https://stationeers-wiki.com/index.php?title=Special:UserLogin&returnto=Autolathe%2FInternal_Memory)** or **[create an account](https://stationeers-wiki.com/index.php?title=Special:CreateAccount&returnto=Autolathe%2FInternal_Memory)** , your edits will be attributed to your username, along with other benefits. 

Anti-spam check. Do **not** fill this in!

=== Internal Memory === These are all valid instructions, that can be written or read with IC10, on Autolathe's stack. {| class="wikitable sortable" style="width:100%;" ! Op_code ! class="unsortable" | Name ! class="unsortable" | Description ! class="unsortable" | Valid Address ! class="unsortable" | Bits ! class="unsortable" | Bits Description |- ! rowspan="3" | 1 | rowspan="3" | StackPointer | rowspan="3" | The current address the stack pointer is pointing to. It cycles through the available addresses (0 through 53) in a single tick, making it look like it is decreasing for external observer. | rowspan="3" | 63 | style="text-align:center;" | 0-7 | Op_code |- | style="text-align:center;" | 8-23 | Index |- | style="text-align:center;" | 24-63 | Unused |- ! rowspan="4" | 2 | rowspan="4" | ExecuteRecipe | rowspan="4" | This instruction will set the device to the specified prefabhash, and then begin manufacturing it. The final element of the payload is the quantity. So you can ask the device to make 200 ItemSteelSheets and it will do that. The quantity is a byte - so the maximum you can request is 255. | rowspan="4" | 0-53 | style="text-align:center;" | 0-7 | Op_code |- | style="text-align:center;" | 8-15 | Quantity |- | style="text-align:center;" | 16-47 | Prefab_hash |- | style="text-align:center;" | 48-63 | Unused |- ! rowspan="2" | 3 | rowspan="2" | WaitUntilNextValid | rowspan="2" | This is a flag that if there is an ExecuteRecipe in the next address, then it will wait until it can be completed. So if you put this before an ExecuteRecipe, the device will sit there till the order can be completed because it is waiting for ingredients. | rowspan="2" | 0-53 | style="text-align:center;" | 0-7 | Op_code |- | style="text-align:center;" | 8-63 | Unused |- ! rowspan="3" | 4 | rowspan="3" | JumpIfNextValid | rowspan="3" | This is another flag that applies to the next address (if it is ExecuteRecipe). If the recipe cannot be completed, then the Fabricator will jump to the specified address. | rowspan="3" | 0-53 | style="text-align:center;" | 0-7 | Op_code |- | style="text-align:center;" | 8-23 | Stack_Address |- | style="text-align:center;" | 24-63 | Unused |- ! rowspan="3" | 5 | rowspan="3" | JumpToAddress | rowspan="3" | This will jump to a specific address. This will set the stack pointer to the address you specify. | rowspan="3" | 0-53 | style="text-align:center;" | 0-7 | Op_code |- | style="text-align:center;" | 8-23 | Stack_Address |- | style="text-align:center;" | 24-63 | Unused |- ! rowspan="3" | 6 | rowspan="3" | DeviceSetLock | rowspan="3" | This will set the lock state of the device (true 1, false 0), similar to the "L" IC instruction. Useful if you want to lock the device, do something, then unlock it. | rowspan="3" | 0-53 | style="text-align:center;" | 0-7 | Op_code |- | style="text-align:center;" | 8-15 | Lock_State |- | style="text-align:center;" | 16-63 | Unused |- ! rowspan="3" | 7 | rowspan="3" | EjectReagent | rowspan="3" | This allows you to specity the reagent you want to eject. All reagents of that type will be ejected. The stack will not advance until this is complete | rowspan="3" | 0-53 | style="text-align:center;" | 0-7 | Op_code |- | style="text-align:center;" | 8-39 | Reagent_Hash |- | style="text-align:center;" | 40-63 | Unused |- ! rowspan="2" | 8 | rowspan="2" | EjectAllReagents | rowspan="2" | This instruction will eject all its reagents and pause execution till this is finished. | rowspan="2" | 0-53 | style="text-align:center;" | 0-7 | Op_code |- | style="text-align:center;" | 8-63 | Unused |- ! rowspan="4" | 9 | rowspan="4" | MissingRecipeReagent | rowspan="4" | Contains information about missing reagents for current executing recipe. Appears only when autolathe is trying to execute instruction ExecuteRecipe when flag WaitUntilNextValid is present. | rowspan="4" | 54-62 | style="text-align:center;" | 0-7 | Op_code |- | style="text-align:center;" | 8-15 | Quantity_Ceil |- | style="text-align:center;" | 16-47 | Reagent_Hash |- | style="text-align:center;" | 48-63 | Unused |- ! colspan="6" | <i>Update 0.2.5025.22811 - Fri 02/07/2024</i> <span class="right">[[Autolathe/Internal Memory|/Internal Memory]]</span> |} </div> 

Summary:

Please note that all contributions to Unofficial Stationeers Wiki may be edited, altered, or removed by other contributors. If you do not want your writing to be edited mercilessly, then do not submit it here.  
You are also promising us that you wrote this yourself, or copied it from a public domain or similar free resource (see [Unofficial Stationeers Wiki:Copyrights](/index.php?title=Unofficial_Stationeers_Wiki:Copyrights&action=edit&redlink=1 "Unofficial Stationeers Wiki:Copyrights \(page does not exist\)") for details). **Do not submit copyrighted work without permission!**

To edit this page, please answer the question that appears below ([more info](/Special:Captcha/help "Special:Captcha/help")): 

What machine can you use to craft iron frames?

[Cancel](/Autolathe/Internal_Memory) |  [Editing help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Editing_pages) (opens in new window)

Retrieved from "<https://stationeers-wiki.com/Autolathe/Internal_Memory>"

  * [Privacy policy](/Unofficial_Stationeers_Wiki:Privacy_policy "Unofficial Stationeers Wiki:Privacy policy")
  * [About Unofficial Stationeers Wiki](/Unofficial_Stationeers_Wiki:About "Unofficial Stationeers Wiki:About")
  * [Disclaimers](/Unofficial_Stationeers_Wiki:General_disclaimer "Unofficial Stationeers Wiki:General disclaimer")



  *   * [Powered by MediaWiki](//www.mediawiki.org/)


  *[v]: View this template
  *[t]: Discuss this template
  *[e]: Edit this template
  *[m]: This is a minor edit
  *[N]: This edit created a new page
