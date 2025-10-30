__

# [ Unofficial Stationeers Wiki Unofficial Stationeers Wiki](/Main_Page)

__

  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Atmospheric_Components_Quick_Reference "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Atmospheric_Components_Quick_Reference "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Atmospheric_Components_Quick_Reference&action=info "More information about this page")



  * [Log in](/index.php?title=Special:UserLogin&returnto=Atmospheric+Components+Quick+Reference&returntoquery=action%3Dedit)



  * [ ![Unofficial Stationeers Wiki](/resources/assets/stationeers-wiki.png)](/Main_Page)
  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/Atmospheric_Components_Quick_Reference "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/Atmospheric_Components_Quick_Reference "Recent changes in pages linked from this page \[k\]")
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Page information](/index.php?title=Atmospheric_Components_Quick_Reference&action=info "More information about this page")



_  Actions_

  * [Page](/Atmospheric_Components_Quick_Reference "View the content page \[c\]")
  * [Discussion](/index.php?title=Talk:Atmospheric_Components_Quick_Reference&action=edit&redlink=1 "Discussion about the content page \[t\]")
  * [Edit](/index.php?title=Atmospheric_Components_Quick_Reference&action=edit "Edit this page")
  * [History](/index.php?title=Atmospheric_Components_Quick_Reference&action=history "Past revisions of this page \[h\]")



## Editing Atmospheric Components Quick Reference

##### 

**Warning:** You are not logged in. Your IP address will be publicly visible if you make any edits. If you **[log in](https://stationeers-wiki.com/index.php?title=Special:UserLogin&returnto=Atmospheric_Components_Quick_Reference)** or **[create an account](https://stationeers-wiki.com/index.php?title=Special:CreateAccount&returnto=Atmospheric_Components_Quick_Reference)** , your edits will be attributed to your username, along with other benefits. 

Anti-spam check. Do **not** fill this in!

This is a quick reference to the various components of a piped-fluid network. {| class="wikitable sortable" |- ! Component !! Kit !! Inputs !! Outputs !! One-way? !! Switched? !! Compressor? !! Volume !! Max. Pressure !! Max. Power !! Primary Function |- | [[Pipes|Pipe]] (various shapes) || [[Pipes|Kit (Pipe)]], also craftable at [[Autolathe]] || colspan="2"|2-6 generic || No || No || No || 100 L || 60 MPa || - || Provide a pathway. |- | [[Pipe Label]] || [[Pipe Label|Kit (Pipe Label)]] || colspan="2"|clamp-on || - || - || - || - || - || - || Visually label pipes. |- | [[Pipe Valve]] || [[Pipe Valve|Kit (Pipe Valve)]] || colspan="2"|2 generic || No || Manual only || No|| ? || ? || - || Open/close flow manually. |- | [[Pipe Digital Valve]] || [[Pipe Digital Valve|Kit (Digital Valve)]] || colspan="2"|2 generic || No || Yes || No || ? || ? || 25W || Open/close flow using [[Kit (Logic I/O)|logic circuits]]. |- | [[Pipe Volume Pump]] || [[Pipe Volume Pump|Kit (Volume Pump)]] || 1 || 1 || Yes || Yes || Yes, adjustable || varies? || ? || 800W, varies || Pump fluid at adjustable rate. |- | [[Pressure_Regulator#Pressure_Regulator|Pressure Regulator]] || [[Pressure Regulator|Kit (Pressure Regulator)]] || 1 || 1 || Yes || Yes || Yes || ? || 20 MPa<sup>5</sup> || 100W || Achieve target pressure at output. |- | [[Pressure_Regulator#Back_Pressure_Regulator|Back Pressure Regulator]] || [[Pressure Regulator|Kit (Pressure Regulator)]] || 1 || 1 || Yes || Yes || Yes || ? || 20 MPa<sup>5</sup> || 100W || Achieve target pressure at input. |- | [[Pipe Meter]] || [[Pipe Meter|Kit (Pipe Meter)]] || colspan="2"|clamp-on || - || - || - || - || - || - || Visually show pipe's pressure. |- | [[Pipe Analyzer]] || [[Pipe Analyzer|Kit (Pipe Analyzer)]] || colspan="2"|clamp-on || - || - || - || - || - || 5W || Sense pipe's pressure, temperature, and composition, for visual display and logic circuits. |- | [[Pipe Gas Mixer]] || [[Pipe Gas Mixer|Kit (Gas Mixer)]] || 2 || 1 || Yes || Yes || Yes<sup>1</sup> || ? || ? || 100W || Mix fluids: Combine two input mixes into one output mix, at an adjustable ratio. |- | [[Kit (Atmospherics) Filtration|Filtration]] || [[Kit (Atmospherics)]] || 1 || 2 || Yes || Yes || Yes || ? || ? || 5W || Sort fluids: Separate an input mix into a pure output and a "leftover" output. |- | [[Kit (Atmospherics) Electrolyzer|Electrolyzer]] || [[Kit (Atmospherics)]] || 1 || 1 || Yes || Yes || Yes || ? || ? || 1,400W || Create fuel: From input [[water|H<sub>2</sub>O]], output mixed [[Oxygen|O<sub>2</sub>]] and [[Volatiles]]. |- | [[Kit (Atmospherics) Air Conditioner|Air Conditioner]] || [[Kit (Atmospherics)]] || 1 || 2 || Yes || Yes || Yes || ? || ? || 7,000W, varies || Heat or cool a fluid: From input, split heat between right-temperature and wrong-temperature outputs. |- | [[Wall Cooler]] || [[Wall Cooler|Kit (Wall Cooler)]] || 1 space || 1 || Yes, for heat<sup>2</sup> || Yes, for heat<sup>2</sup> || Yes, for heat<sup>2</sup> || ? || ? || ? || Cool a space: Actively remove heat from a space into a pipe. |- | [[Wall Heater]] || [[Wall Heater|Kit (Wall Heater)]] || colspan="2"|1 space || - || - || - || - || - || 1010W || Heat a space: Convert electric power into heat. |- | [[Pipe Radiator]] || [[Pipe Radiator|Kit (Pipe Radiator)]] || colspan="2"|clamp-on || - || - || - || - || - || - || Heat/cool: Passively exchange heat between a pipe and a space. |- | [[Active Vent]] || [[Active Vent|Kit (Active Vent)]] || colspan="2"|1 generic, 1 space || Yes, reversable || Yes || Yes || ? || ?<sup>3</sup> || 100W || Pump pressure between a space and a pipe. |- | [[Passive Vent]] || [[Passive Vent|Kit (Passive Vent)]] || colspan="2"|1 generic, 1 space || No || No || No || - || - || - || Equalize pressure between a space and a pipe. |- | [[Gas Tank Storage]] || [[Gas Tank Storage|Kit (Canister Storage)]] || colspan="2"|1 generic || No || No || No || 64 L<sup>4</sup> || 101 MPa<sup>4</sup> || - || Small storage: Attach pipes to [[Gas Canister]]s (removable, inventory-portable fluid storage). |- | [[Tank Connector]] || [[Tank Connector|Kit (Tank Connector)]] || colspan="2"|1 generic || No || No || No || 790 L<sup>4</sup> || 10.1 MPa<sup>4</sup> || - || Medium storage: Attach pipes to [[Portable Tank]]s (removable, draggable fluid storage), and also to [[Portable Air Scrubber]]s and [[Portable Air Conditioner]]s. |- | [[Tank|Small Tank]] || [[Tank|Kit (Tank)]] || colspan="2"|1 generic || No || Logic only? || No || 6 kL || 60 MPa || - || Permanent, high-capacity fluid storage. |- | [[Tank|Large Tank]] || [[Tank|Kit (Tank)]] × 5 || colspan="2"|1 generic || No || Logic only? || No || 50 kL || 60 MPa || - || Permanent, super-capacity fluid storage. |- | [[Furnace]] || [[Furnace|Kit (Furnace)]], craftable at [[Autolathe]] || 1 || 1 || Yes || No || No || 1 kL || ? || - || Smelt ores, but can also melt/sublimate Ices directly into a pipe. |- | [[Advanced Furnace]] || [[Advanced Furnace|Kit (Advanced Furnace)]], craftable at [[Electronics Printer]] Mk. II || 1 || 1 || Yes || Yes || Yes, adjustable || 1 kL? || ? || ? || Smelt ores and sublimate Ices, with active, adjustable pumping on input and output. |} '''Kit:''' The item used to build the component. These are the names as they appear in fabrication lists, which does not always match the true name of the item. Except where noted, all of these items are manufactured with a [[Hydraulic Pipe Bender]]. '''Input/Output:''' "Generic" connections are pipe fittings that are not explicitly for input or output. "Space" indicates an interface to fluids that are not contained in pipes (e.g., the atmosphere or the contents of a room). "Clamp-on" components have no fittings of their own; they clamp onto an existing Straight Pipe. '''One-way:''' Does the component prevent fluid from flowing the wrong way, from output to input? '''Switched:''' Does it prevent all flow when switched off or unpowered? Except where noted, switched components can be switched either manually or using [[Kit (Logic I/O)|logic circuits]]. '''Compressor:''' Will it actively increase pressure in the output and decrease pressure in the input? If no, the component only allows pressure to change toward equilibrium between input and output, or it does not enable any pressure changes. '''Max. Pressure:''' The component will begin to fail when pressure exceeds this. More precisely, this is the maximum ''difference'' in pressure between the component's internal volume and the surrounding space. Some components list "60 MPa" because attached pipes will fail, even if the true limit of the component itself is unknown. Even where a higher limit is known (e.g., canisters), this limitation still holds and places a practical maximum on most setups. '''Note 1:''' While the Pipe Gas Mixer will actively compress from output to input, it will stop when either input is empty, to preserve the mix ratio. '''Note 2:''' The Wall Cooler's one-way, switched, and "compressor" qualities apply only to the heat exchange. It does not directly affect the pressure or flow in its attached pipe. '''Note 3:''' The Active Vent will ''fail'' at ? MPa. The pressure at which it will stop pumping is configurable through the data network and defaults to 0 Pa for Inward mode and 101 kPa (1 standard atmosphere) for Outward mode. '''Note 4:''' These Volume and Max. Pressure ratings reflect the limits of the removable canisters and tanks. Note that the 101 MPa limit of a Gas Canister is considerably higher than the 60 MPa overall limit of a pipe network. '''Note 5:''' These Pressure limits are what max can be set on the regulators. Regulators themselves have no inner atmosphere and thus no inner pressure that would break them. 

Summary:

Please note that all contributions to Unofficial Stationeers Wiki may be edited, altered, or removed by other contributors. If you do not want your writing to be edited mercilessly, then do not submit it here.  
You are also promising us that you wrote this yourself, or copied it from a public domain or similar free resource (see [Unofficial Stationeers Wiki:Copyrights](/index.php?title=Unofficial_Stationeers_Wiki:Copyrights&action=edit&redlink=1 "Unofficial Stationeers Wiki:Copyrights \(page does not exist\)") for details). **Do not submit copyrighted work without permission!**

To edit this page, please answer the question that appears below ([more info](/Special:Captcha/help "Special:Captcha/help")): 

What machine do you use to smelt ore?

[Cancel](/Atmospheric_Components_Quick_Reference) |  [Editing help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Editing_pages) (opens in new window)

Retrieved from "<https://stationeers-wiki.com/Atmospheric_Components_Quick_Reference>"

  * [Privacy policy](/Unofficial_Stationeers_Wiki:Privacy_policy "Unofficial Stationeers Wiki:Privacy policy")
  * [About Unofficial Stationeers Wiki](/Unofficial_Stationeers_Wiki:About "Unofficial Stationeers Wiki:About")
  * [Disclaimers](/Unofficial_Stationeers_Wiki:General_disclaimer "Unofficial Stationeers Wiki:General disclaimer")



  *   * [Powered by MediaWiki](//www.mediawiki.org/)


  *[v]: View this template
  *[t]: Discuss this template
  *[e]: Edit this template
  *[m]: This is a minor edit
  *[N]: This edit created a new page
