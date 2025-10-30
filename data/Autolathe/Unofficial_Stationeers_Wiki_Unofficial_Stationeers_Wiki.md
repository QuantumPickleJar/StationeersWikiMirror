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
  * [Printable version](/index.php?title=Autolathe/Internal_Memory&printable=yes "Printable version of this page \[p\]")
  * [Permanent link](/index.php?title=Autolathe/Internal_Memory&oldid=23786 "Permanent link to this revision of the page")
  * [Page information](/index.php?title=Autolathe/Internal_Memory&action=info "More information about this page")



  * [Log in](/index.php?title=Special:UserLogin&returnto=Autolathe%2FInternal+Memory)



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
  * [Printable version](/index.php?title=Autolathe/Internal_Memory&printable=yes "Printable version of this page \[p\]")
  * [Permanent link](/index.php?title=Autolathe/Internal_Memory&oldid=23786 "Permanent link to this revision of the page")
  * [Page information](/index.php?title=Autolathe/Internal_Memory&action=info "More information about this page")



_  Actions_

  * [Page](/Autolathe/Internal_Memory "View the content page \[c\]")
  * [Discussion](/index.php?title=Talk:Autolathe/Internal_Memory&action=edit&redlink=1 "Discussion about the content page \[t\]")
  * [Edit](/index.php?title=Autolathe/Internal_Memory&action=edit "Edit this page \[e\]")
  * [History](/index.php?title=Autolathe/Internal_Memory&action=history "Past revisions of this page \[h\]")



## Autolathe/Internal Memory

### From Unofficial Stationeers Wiki

##### 

These are all of the [Autolathe](/Autolathe "Autolathe") Internal Memory descriptions in the game. 

### Internal Memory[[edit](/index.php?title=Autolathe/Internal_Memory&action=edit&section=1 "Edit section: Internal Memory")]

These are all valid instructions, that can be written or read with IC10, on Autolathe's stack. 

Op_code  |  Name  |  Description  |  Valid Address  |  Bits  |  Bits Description   
---|---|---|---|---|---  
1  |  StackPointer  |  The current address the stack pointer is pointing to. It cycles through the available addresses (0 through 53) in a single tick, making it look like it is decreasing for external observer.  |  63  |  0-7  |  Op_code   
8-23  |  Index   
24-63  |  Unused   
2  |  ExecuteRecipe  |  This instruction will set the device to the specified prefabhash, and then begin manufacturing it. The final element of the payload is the quantity. So you can ask the device to make 200 ItemSteelSheets and it will do that. The quantity is a byte - so the maximum you can request is 255.  |  0-53  |  0-7  |  Op_code   
8-15  |  Quantity   
16-47  |  Prefab_hash   
48-63  |  Unused   
3  |  WaitUntilNextValid  |  This is a flag that if there is an ExecuteRecipe in the next address, then it will wait until it can be completed. So if you put this before an ExecuteRecipe, the device will sit there till the order can be completed because it is waiting for ingredients.  |  0-53  |  0-7  |  Op_code   
8-63  |  Unused   
4  |  JumpIfNextValid  |  This is another flag that applies to the next address (if it is ExecuteRecipe). If the recipe cannot be completed, then the Fabricator will jump to the specified address.  |  0-53  |  0-7  |  Op_code   
8-23  |  Stack_Address   
24-63  |  Unused   
5  |  JumpToAddress  |  This will jump to a specific address. This will set the stack pointer to the address you specify.  |  0-53  |  0-7  |  Op_code   
8-23  |  Stack_Address   
24-63  |  Unused   
6  |  DeviceSetLock  |  This will set the lock state of the device (true 1, false 0), similar to the "L" IC instruction. Useful if you want to lock the device, do something, then unlock it.  |  0-53  |  0-7  |  Op_code   
8-15  |  Lock_State   
16-63  |  Unused   
7  |  EjectReagent  |  This allows you to specity the reagent you want to eject. All reagents of that type will be ejected. The stack will not advance until this is complete  |  0-53  |  0-7  |  Op_code   
8-39  |  Reagent_Hash   
40-63  |  Unused   
8  |  EjectAllReagents  |  This instruction will eject all its reagents and pause execution till this is finished.  |  0-53  |  0-7  |  Op_code   
8-63  |  Unused   
9  |  MissingRecipeReagent  |  Contains information about missing reagents for current executing recipe. Appears only when autolathe is trying to execute instruction ExecuteRecipe when flag WaitUntilNextValid is present.  |  54-62  |  0-7  |  Op_code   
8-15  |  Quantity_Ceil   
16-47  |  Reagent_Hash   
48-63  |  Unused   
_Update 0.2.5025.22811 - Fri 02/07/2024_ /Internal Memory  
  
Retrieved from "[https://stationeers-wiki.com/index.php?title=Autolathe/Internal_Memory&oldid=23786](https://stationeers-wiki.com/index.php?title=Autolathe/Internal_Memory&oldid=23786)"

  * This page was last edited on 21 October 2025, at 09:08.
  * [Privacy policy](/Unofficial_Stationeers_Wiki:Privacy_policy "Unofficial Stationeers Wiki:Privacy policy")
  * [About Unofficial Stationeers Wiki](/Unofficial_Stationeers_Wiki:About "Unofficial Stationeers Wiki:About")
  * [Disclaimers](/Unofficial_Stationeers_Wiki:General_disclaimer "Unofficial Stationeers Wiki:General disclaimer")



  *   * [Powered by MediaWiki](//www.mediawiki.org/)


  *[v]: View this template
  *[t]: Discuss this template
  *[e]: Edit this template
  *[m]: This is a minor edit
  *[N]: This edit created a new page
