__

# [ Unofficial Stationeers Wiki Unofficial Stationeers Wiki](/Main_Page)

__

  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/User:TheNicestGuy/Science "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/User:TheNicestGuy/Science "Recent changes in pages linked from this page \[k\]")
  * [User contributions](/Special:Contributions/TheNicestGuy "A list of contributions by this user")
  * [Logs](/Special:Log/TheNicestGuy)
  * [View user groups](/Special:UserRights/TheNicestGuy)
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Printable version](/index.php?title=User:TheNicestGuy/Science&printable=yes "Printable version of this page \[p\]")
  * [Permanent link](/index.php?title=User:TheNicestGuy/Science&oldid=9679 "Permanent link to this revision of the page")
  * [Page information](/index.php?title=User:TheNicestGuy/Science&action=info "More information about this page")



  * [Log in](/index.php?title=Special:UserLogin&returnto=User%3ATheNicestGuy%2FScience)



  * [ ![Unofficial Stationeers Wiki](/resources/assets/stationeers-wiki.png)](/Main_Page)
  *   * Navigation
  * [Main page](/Main_Page "Visit the main page \[z\]")
  * [Recent changes](/Special:RecentChanges "A list of recent changes in the wiki \[r\]")
  * [Random page](/Special:Random "Load a random page \[x\]")
  * [Help](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")
  * Toolbox
  * [What links here](/Special:WhatLinksHere/User:TheNicestGuy/Science "A list of all wiki pages that link here \[j\]")
  * [Related changes](/Special:RecentChangesLinked/User:TheNicestGuy/Science "Recent changes in pages linked from this page \[k\]")
  * [User contributions](/Special:Contributions/TheNicestGuy "A list of contributions by this user")
  * [Logs](/Special:Log/TheNicestGuy)
  * [View user groups](/Special:UserRights/TheNicestGuy)
  * [Upload file](/Special:UploadWizard "Upload files \[u\]")
  * [Special pages](/Special:SpecialPages "A list of all special pages \[q\]")
  * [Printable version](/index.php?title=User:TheNicestGuy/Science&printable=yes "Printable version of this page \[p\]")
  * [Permanent link](/index.php?title=User:TheNicestGuy/Science&oldid=9679 "Permanent link to this revision of the page")
  * [Page information](/index.php?title=User:TheNicestGuy/Science&action=info "More information about this page")



_  Actions_

  * [User page](/User:TheNicestGuy/Science "View the user page \[c\]")
  * [Discussion](/index.php?title=User_talk:TheNicestGuy/Science&action=edit&redlink=1 "Discussion about the content page \[t\]")
  * [Edit](/index.php?title=User:TheNicestGuy/Science&action=edit "Edit this page \[e\]")
  * [History](/index.php?title=User:TheNicestGuy/Science&action=history "Past revisions of this page \[h\]")



#### User

## TheNicestGuy/Science

### From Unofficial Stationeers Wiki

##### 

_Stationeers_ models many of the real universe's physical laws, to simulate the behavior of things like gases, electricity, and stationeers. This is a reference guide to the underlying physical science concepts, and notes on how _Stationeers_ is faithful or unfaithful them. 

## Contents

  * 1 Measurement
  * 2 Mass
    * 2.1 Direct Measurement
    * 2.2 Implications
  * 3 Moles
    * 3.1 Moles Versus Mass
    * 3.2 Direct Measurement
    * 3.3 Implications
  * 4 Volume
    * 4.1 Direct Measurement
    * 4.2 Implications
  * 5 Temperature
    * 5.1 Direct Measurement
    * 5.2 Implications
  * 6 Pressure, Absolute
  * 7 Pressure, Differential
  * 8 Phase
  * 9 Metallurgy
    * 9.1 Implications
    * 9.2 Comparison to Real Formulas
  * 10 Physiology
  * 11 Botany
  * 12 Ornithology
  * 13 Energy



## Measurement[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=1 "Edit section: Measurement")]

_Stationeers_ measures most properties using units standardized in the [International System of Units](https://en.wikipedia.org/wiki/International_System_of_Units "wikipedia:International System of Units") ("SI"). This applies to the HUD and other visual displays, but it also applies to values used in logic circuitry, which is important to logic-based math. 

## Mass[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=2 "Edit section: Mass")]

Or, Take This Blob and Shove It. 

**[Mass](https://en.wikipedia.org/wiki/Mass "wikipedia:Mass")** measures an amount of matter, in terms of its relationship to forces (e.g., gravity), inertia, and acceleration. _Stationeers_ uses the SI unit **gram** (g) for mass. 

The laws of science make two major statements about mass that are relevant to stationeering. First, the amount of force it takes to accelerate an object is directly proportional to its mass. Big things are harder to push, stop, or steer. Second, mass cannot be created nor destroyed, even when it undergoes drastic chemical and physical changes. This second rule is broken in relativistic situations, such as nuclear reactions. 

### Direct Measurement[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=3 "Edit section: Direct Measurement")]

_Stationeers_ probably uses mass extensively behind the scenes, within the physics engine to calculate the movement of objects. In the player interface, however, only certain substances are given mass measurements: 

  * [Ingots](/Category:Ingot "Category:Ingot")
  * The input contents of crafting machines, and the ingredients of their recipes
  * [Reagent Mix](/Reagent_Mix "Reagent Mix")
  * The products of a [Reagent Processor](/Reagent_Processor "Reagent Processor") (except [Soy Oil](/Soy_Oil "Soy Oil"), which is measured by volume)



### Implications[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=4 "Edit section: Implications")]

It's hard to say how faithful _Stationeers_ is to the laws of mass, force, and acceleration. For example, it seems unlikely, but not impossible, that the physics engine calculates the total mass of a Stationeer and all of the objects they carry, applying that to the results of player movement. 

To be tested: Ships and rovers? 

_Stationeers_ is generally very faithful about conservation of mass. The smelting of alloys, for example, always produces the same mass as the ingredients put in. There is an exception due to odd behavior of the [Centrifuge](/Centrifuge "Centrifuge"); see Metallurgy. 

There are currently no nuclear reactions in _Stationeers_ to violate the conservation of mass legitimately. (Despite the name, the [Nuclear Cell](/Battery_Cell#Nuclear_Cell "Battery Cell") is really just a super-capacity energy storage device; it does not consume fuel.) 

## Moles[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=5 "Edit section: Moles")]

Or, Will It Blend? 

In chemical terms, ["amounts" of substance](https://en.wikipedia.org/wiki/Amount_of_substance "wikipedia:Amount of substance") are not measured as mass, but as counts of particles. In _Stationeers_ , the particles in question are always molecules, and the game relates these counts using the SI unit **mole**. A mole is 6.0 × 1023 molecules (the Avogadro number). It is abbreviated as **mol** ; _Stationeers_ also uses **kmol** (one thousand moles) and **Mmol** (one million moles). 

### Moles Versus Mass[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=6 "Edit section: Moles Versus Mass")]

Although there is a direct relationship between moles and mass, the reason to use moles is because it makes chemistry equations less awkward. Take, for example, the combustion of hydrogen: 

2H2 \+ O2 → 2H2O + a bunch of heat 

That is, two molecules of hydrogen-hydrogen react with one molecule of oxygen-oxygen, producing heat and two molecules of water. This can scale up to larger amounts, of course, and to apply real amounts of substance to this equation, you can do it very simply as long as everything is expressed in moles. 

2mol H2 \+ 1mol O2 → 2mol H2O 

To express the same thing with mass, you would have to account for the very different mass per molecule of hydrogen gas, oxygen gas, and water. 

4.032g H2 \+ 31.999g O2 → 36.031g H2O 

The numbers add up (because mass is conserved), but they're odd-looking, and they obscure the fact that the reaction takes more hydrogen than oxygen, molecule for molecule. 

### Direct Measurement[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=7 "Edit section: Direct Measurement")]

_Stationeers_ measures all [gases and other bulk fluids](/Category:Gas "Category:Gas") in moles, so you will see molar readings on, for example, [Pipe Analyzers](/Pipe_Analyzer "Pipe Analyzer") and a [Handheld Tablet](/Handheld_Tablet "Handheld Tablet") running the Atmos Analyzer [Cartridge](/Cartridge "Cartridge"). These fluids are found in: 

  * The [atmosphere](/Atmosphere "Atmosphere") (if any)
  * Enclosed spaces such as rooms
  * [Pipes](/Pipe "Pipe")
  * Pipe-fitted devices such as [Furnaces](/Furnace "Furnace") and [Tanks](/Tank "Tank")
  * [Portable Tanks](/Portable_Tank "Portable Tank")
  * [Gas Canisters](/Gas_Canister "Gas Canister")



### Implications[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=8 "Edit section: Implications")]

The game does not include a reference to the [molar masses](https://en.wikipedia.org/wiki/Molar_mass "wikipedia:Molar mass") of these fluids, but it should not normally be necessary. Ratios of one substance to another can be crucial (e.g., for [Fuel](/Fuel "Fuel")), but these are always calculated by mole (see [stoichiometry](https://en.wikipedia.org/wiki/Stoichiometry "wikipedia:Stoichiometry")), not by mass or volume. As such, when you set the mix ratio on a [Pipe Gas Mixer](/Pipe_Gas_Mixer "Pipe Gas Mixer"), that's a ratio of moles as well. 

The game is **not faithful** to molar chemistry when it comes to the substance called "[Volatiles](/Volatiles "Volatiles")". Volatiles behave in some chemical contexts like pure hydrogen gas (and are sometimes labeled "H2"), but when burned they behave more like a [hydrocarbon](https://en.wikipedia.org/wiki/Hydrocarbon "wikipedia:Hydrocarbon"). 

## Volume[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=9 "Edit section: Volume")]

Or, You Know Where You Can Put That? 

**[Volume](https://en.wikipedia.org/wiki/Volume "wikipedia:Volume")** is, simply, the amount of space occupied by a three-dimensional shape. If a substance can compress (like a gas), and a container is rigid, then the volume will remain constant even as you pump mass/moles into or out of the container. 

_Stationeers_ uses the SI unit **liter** (L) for volume. Some spaces are more practical to measure in thousands of liters; 1,000 L can be referred to as 1 kL (kiloliter), but it would more commonly be called a **cubic meter** (m3). 

### Direct Measurement[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=10 "Edit section: Direct Measurement")]

_Stationeers_ calculates a volume for everything that can contain gases/fluids. 

  * Enclosed spaces such as rooms
  * [Pipes](/Pipe "Pipe")
  * Pipe-fitted devices such as [Furnaces](/Furnace "Furnace") and [Tanks](/Tank "Tank")
  * [Portable Tanks](/Portable_Tank "Portable Tank")
  * [Gas Canisters](/Gas_Canister "Gas Canister")



The exception is the global atmosphere, which is not contained and can be said to have infinite volume[verification needed]. 

### Implications[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=11 "Edit section: Implications")]

The volume of plumbing and other components is not usually made obvious by the player interface, but it is a real and essential factor in calculations of pressure and other properties. Say you produce X mol of gas, and you connect it to a [Tank](/Tank "Tank") for storage, with no active pumping components between. The more [Pipes](/Pipes "Pipes") present between the source and the Tank, the lower the total pressure, because each Pipe adds 100L of volume. 

Here are some important reference volumes. 

  * One large grid cube: 8,000 L (= 8 m3 = 2 meters per side)
  * [Gas Canister](/Gas_Canister "Gas Canister"): 64 L
  * [Portable Tank](/Portable_Tank "Portable Tank"): 790 L
  * [Small Tank](/Tank#Small_Tank "Tank"): 6,000 L
  * [Large Tank](/Tank#Large_Tank "Tank"): 50,000 L
  * [Furnace](/Furnace "Furnace") chamber: 1,000 L
  * A Stationeer's lungs: 6 L



## Temperature[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=12 "Edit section: Temperature")]

Or, Will That Cook Me? 

**[Temperature](https://en.wikipedia.org/wiki/Temperature "wikipedia:Temperature")** is the measurement of how hot or cold matter is. The precise thermodynamic definition is complex, but it can be roughly summarized as the amount of energy embedded into a substance. Temperature has a very direct effect on pressure, and vice versa. 

Thermal energy moves around by three major methods. In **conduction** , heat transfers directly through matter, tending to bring regions of high and low temperature into equilibrium. (Think "burned by a hot pan".) In thermal **radiation** , heat generates electromagnetic emissions that can be transmitted even across a vacuum, then absorbed by other matter causing it to heat up in turn. (Think "sunshine is warm".) In **convection** , conduction heats a portion of a fluid, creating local pressure changes which cause the fluid to move; it carries the heat with it. (Think "hot air rises".) 

### Direct Measurement[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=13 "Edit section: Direct Measurement")]

_Stationeers_ measures temperature on two scales. Fluids within plumbing (e.g., pipes, tanks, furnaces) are measured in **kelvin** (K), where 0K represents the theoretical complete absence of thermal energy ("[absolute zero](https://en.wikipedia.org/wiki/Absolute_zero "wikipedia:Absolute zero")"). Fluids in enclosed spaces or in the atmosphere are measured in **degrees Celsius** (°C), where 0°C is the freezing point of water at standard atmospheric pressure (101.325 kPa). One kelvin is exactly equal to one degree Celsius, so you can easily convert from K to °C by subtracting **273.15**. (This is why ices placed in a [Furnace](/Furnace "Furnace") will change to gas on their own if the Furnace is above 273K, and otherwise just sit there.) 

### Implications[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=14 "Edit section: Implications")]

_Stationeers_ clearly models heat conduction in general. For example, a Pipe will gradually conduct heat between its contents and the surrounding matter to reach equilibrium, and this exchange rate is greatly increased by adding a [Pipe Radiator](/Pipe_Radiator "Pipe Radiator"). It also models the reality that forcibly "pumping" heat from one volume to another (e.g., with an [Air Conditioner](/Kit_\(Atmospherics\)_Air_Conditioner "Kit \(Atmospherics\) Air Conditioner") or an [EVA Suit](/EVA_Suit "EVA Suit")) requires the use of energy, and also that excess heat is not simply destroyed in this process—it still has to be disposed of somehow. 

To be tested: Do different materials have different conductivity? 

To be tested: Is thermal radiation modeled? Try in a vacuum. 

To be tested: Can fluid flow be induced with heat alone? 

## Pressure, Absolute[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=15 "Edit section: Pressure, Absolute")]

## Pressure, Differential[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=16 "Edit section: Pressure, Differential")]

## Phase[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=17 "Edit section: Phase")]

## Metallurgy[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=18 "Edit section: Metallurgy")]

Or, He Who Smelted 

### Implications[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=19 "Edit section: Implications")]

[Ores](/Category:Ore "Category:Ore") are not measured by mass, but each unit of ore always produces one gram of product (not counting any gas byproducts) when smelted. 

The [recipe for an alloy](/Furnace#Recipes "Furnace") is given as ratios between ingredients, not as exact amounts. These are ratios of mass, not of moles or volume. While this measuring method is faithful to real-world metallurgy, the formulas themselves are simplified (or totally different) from their real counterparts, as shown in the table below. 

The total count of the ore units output from a [Centrifuge](/Centrifuge "Centrifuge") always equals the mass in grams of the mix put in. This is **not faithful**[verification needed], because all ores in the game explicitly include impurities. The implication is that the Centrifuge somehow reintroduces the original impurities, and in fact this can be exploited to create those impurities from nothing, if you find them useful. 

### Comparison to Real Formulas[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=20 "Edit section: Comparison to Real Formulas")]

Alloy  |  Stationeers Formula  |  Real Formula  |  Remarks   
---|---|---|---  
Steel  |  75% iron + 25% carbon  |  mostly iron + < 2.2% carbon + others  |  Real steel comes in many varieties for different purposes, all with different iron-carbon ratios and additives. Stainless steel, tool steel, and spring steel name just a few wide classes.   
Electrum  |  50% silver + 50% gold |  20%~80% silver + 20%~80% gold  |  Real electrum is one of Earth's few naturally-occurring alloys. Natural deposits vary widely in their ratios, and other elements can be included.   
Invar  |  50% iron + 50% nickel  |  64% iron + 36% nickel  |  Real invar is used when an object needs to precisely keep its size and shape as its temperature changes.   
Constantan  |  50% copper + 50% nickel |  about 55% copper + 45% nickel  |  Real constantan is used when an object needs to precisely keep its electrical resistivity as its temperature changes.   
Solder  |  50% iron + 50% lead  |  varies  |  In the real world, "solder" describes many different materials that are very different from one another in composition. They all melt at low temperatures, solidify at room temperature, and are used to bond objects together, but the varieties used for electrical circuits, plumbing parts, and jewelry are each tailored for their applications. "Classic" solder is a mixture of lead and _tin_ , but modern solder often contains no lead (as it's toxic). Iron is not a typical solder ingredient. (However, the tool used to melt and apply solder is generally called an "iron", whatever it's made of.)   
Astroloy  |  50% iron + 25% copper + 25% cobalt  |  mostly nickel + 17% cobalt + 15% chromium + molybdenum, aluminum, titanium, and others  |  Real Astroloy was developed for specialized aerospace uses, such as jet engine turbines.   
Hastelloy  |  50% nickel + 25% silver + 25% cobalt  |  C-276 formula: mostly nickel + > 17% molybdenum + > 14.5% chromium + iron, tungsten, cobalt, and others  |  The various real formulas for Hastelloy are all nickel based. They are used in chemical processing systems for their corrosion resistance.   
Inconel  |  50% nickel + 25% gold + 25% iron  |  625 formula: mostly nickel + > 20% chromium + > 8% molybdenum + niobium, tantalum, and others  |  The various real formulas for Inconel are all nickel-chromium based. They are used because they are self-protecting against corrosion and oxidation at high temperatures, along with being physically strong.   
Waspaloy  |  50% nickel + 25% lead + 25% silver  |  mostly nickel + 19% chromium + 13% cobalt + molybdenum, titanium, aluminum, and others  |  Real Waspaloy is used in demanding high-temperature applications, such as jet engines.   
Stellite  |  50% cobalt + 25% silver + 25% silicon  |  Stellite 1 formula: mostly cobalt + > 28% chromium + > 11% tungsten + carbon, silicon, iron, nickel, and others  |  Real Stellite is used for hard-wearing applications, such as power tool faces and cutlery.   
  
## Physiology[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=21 "Edit section: Physiology")]

## Botany[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=22 "Edit section: Botany")]

Or, Sow What? 

## Ornithology[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=23 "Edit section: Ornithology")]

Or, Layers Upon Layers 

## Energy[[edit](/index.php?title=User:TheNicestGuy/Science&action=edit&section=24 "Edit section: Energy")]

Retrieved from "[https://stationeers-wiki.com/index.php?title=User:TheNicestGuy/Science&oldid=9679](https://stationeers-wiki.com/index.php?title=User:TheNicestGuy/Science&oldid=9679)"

  * This page was last edited on 27 September 2020, at 09:59.
  * [Privacy policy](/Unofficial_Stationeers_Wiki:Privacy_policy "Unofficial Stationeers Wiki:Privacy policy")
  * [About Unofficial Stationeers Wiki](/Unofficial_Stationeers_Wiki:About "Unofficial Stationeers Wiki:About")
  * [Disclaimers](/Unofficial_Stationeers_Wiki:General_disclaimer "Unofficial Stationeers Wiki:General disclaimer")



  *   * [Powered by MediaWiki](//www.mediawiki.org/)


  *[v]: View this template
  *[t]: Discuss this template
  *[e]: Edit this template
  *[m]: This is a minor edit
  *[N]: This edit created a new page
