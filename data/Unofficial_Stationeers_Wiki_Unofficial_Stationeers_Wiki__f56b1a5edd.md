__

# [ Unofficial Stationeers Wiki Unofficial Stationeers Wiki](/Main_Page)

__

  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Pressure_Regulator "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Pressure_Regulator "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Pressure_Regulator&action=info "More information about this page")



  * [Log in](/index.php?title=Special:UserLogin&returnto=Pressure+Regulator&returntoquery=action%3Dedit%26section%3D1)



  * [ ![Unofficial Stationeers Wiki](/resources/assets/stationeers-wiki.png)](/Main_Page)
  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Pressure_Regulator "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Pressure_Regulator "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Pressure_Regulator&action=info "More information about this page")



_  Actions_

  * [Page](/Pressure_Regulator "View the content page \[c\]")
  * [Discussion](/index.php?title=Talk:Pressure_Regulator&action=edit&redlink=1 "Discussion about the content page \[t\]")
  * [Edit](/index.php?title=Pressure_Regulator&action=edit "Edit this page")
  * [History](/index.php?title=Pressure_Regulator&action=history "Past revisions of this page \[h\]")



## Editing Pressure Regulator (section)

##### 

**Warning:** You are not logged in. Your IP address will be publicly visible if you make any edits. If you **[log in](https://stationeers-wiki.com/index.php?title=Special:UserLogin&returnto=Pressure_Regulator)** or **[create an account](https://stationeers-wiki.com/index.php?title=Special:CreateAccount&returnto=Pressure_Regulator)** , your edits will be attributed to your username, along with other benefits. 

Anti-spam check. Do **not** fill this in!

==Description== <blockquote><q>Controlling the flow of gas between two pipe networks, pressure regulators shift gas until a set pressure on the outlet side is achieved, or the gas supply is exhausted. The back pressure regulator, by contrast, will only operate when pressure on the intake side exceeds the set value. With a max pressure of over 20,000kPa, it requires power to operate.</q><br> '''- Stationpedia'''</blockquote> The standard Pressure Regulator is an active powered device for controlled transfer of substances between the two pipe networks. Pressure Regulator will use the gas from Input pipe network to pressurize the Output pipe network until a target pressure defined by the valve setting is reached or exceeded, or unless the input pipe runs dry. When being placed, hologram indicators will display the Input pipe arrow inward, the Output pipe arrow outward, and the power socket on its side. It has a pressure control valve, which defines the target pressure. The most common use for a standard Pressure Regulator is to place one ahead of a [[Gas Tank Storage]] unit to safely fill the inserted [[Gas Canister]] or [[Gas Canister (Smart)]] with gas input without overpressurizing it. Similar principle can be used to maintain the desired pressure level in any pipe network or room. The maximum pressure setting is 60795 kPa - a critical pressure limit for a pipe network before it begin to take damage. To calculate the moles per tick, use the following equation: n = (P * V) / (R * T) Where: * P = Min(Input pressure, 101.325) * V = (OutputPipeVolume / InputPipeVolume) * 100 * n = Moles per tick * R = Gas constant (8.3144) * T = Input temperature {{Data Network Header}} {{Data Parameters| {{Data Parameters/row|Power|Boolean|w=0|Can be read to return if the Pressure Regulator is correctly powered or not, set via the power system, return 1 if powered and 0 if not|multiple=2|0|Unpowered|1|Powered}} {{Data Parameters/row|Error|Boolean|w=0|1 if device is in error state, otherwise 0|multiple=2|0|<p></p>|1|Error}} {{Data Parameters/row|Lock|Boolean|Disable manual operation of the Pressure Regulator.|multiple=2|0|Unlocked|1|Locked}} {{Data Parameters/row|Setting|Integer|A variable setting that can be read or written.|0.0 to 60795.0}} {{Data Parameters/row|Maximum|Float|w=0|Maximum setting of the Pressure Regulator}} {{Data Parameters/row|Ratio|Float|w=0|Context specific value depending on device, 0 to 1 based ratio|0.0 to 1.0}} {{Data Parameters/row|On|Boolean|The current state of the Pressure Regulator.|multiple=2|0|Off|1|On}} {{Data Parameters/row|RequiredPower|Integer|w=0|Idle operating power quantity, does not necessarily include extra demand power}} {{Data Parameters/row|PrefabHash|Integer|w=0|The hash of the structure}} {{Data Parameters/row|ReferenceId|Integer|w=0|Unique Reference Identifier for this object}} {{Data Parameters/row|NameHash|Integer|w=0|Provides the hash value for the name of the object as a 32 bit integer.}} }} [[Category:Atmospherics]] 

Summary:

Please note that all contributions to Unofficial Stationeers Wiki may be edited, altered, or removed by other contributors. If you do not want your writing to be edited mercilessly, then do not submit it here.  
You are also promising us that you wrote this yourself, or copied it from a public domain or similar free resource (see [Unofficial Stationeers Wiki:Copyrights](/index.php?title=Unofficial_Stationeers_Wiki:Copyrights&action=edit&redlink=1 "Unofficial Stationeers Wiki:Copyrights \(page does not exist\)") for details). **Do not submit copyrighted work without permission!**

To edit this page, please answer the question that appears below ([more info](/Special:Captcha/help "Special:Captcha/help")): 

What machine can you use to craft iron frames?

[Cancel](/Pressure_Regulator) |  [Editing help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Editing_pages) (opens in new window)

Retrieved from "<https://stationeers-wiki.com/Pressure_Regulator>"

  * [Privacy policy](/Unofficial_Stationeers_Wiki:Privacy_policy "Unofficial Stationeers Wiki:Privacy policy")
  * [About Unofficial Stationeers Wiki](/Unofficial_Stationeers_Wiki:About "Unofficial Stationeers Wiki:About")
  * [Disclaimers](/Unofficial_Stationeers_Wiki:General_disclaimer "Unofficial Stationeers Wiki:General disclaimer")



  *   * [Powered by MediaWiki](//www.mediawiki.org/)


  *[v]: View this template
  *[t]: Discuss this template
  *[e]: Edit this template
  *[m]: This is a minor edit
  *[N]: This edit created a new page
