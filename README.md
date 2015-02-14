#KAINET: KAA Artificial Intelligence Network for Exploration, with Techtree

*An addon for Kerbal Space Program which modifies the technology tree to allow (and require) players to refrain from using any Kerbals during their career.*

Public outcry over accidents involving losses of life has driven many space programs to adopt risk-averse stances, reducing the number of crewed missions and intensely studying and validating the crewed missions and vehicles remaining.  We at KAA Aeronautics and Astronautics have decided to support these efforts by creating a space program that has no Kerbal involvement whatsoever.  Presenting KAINET, the KAA Artificial Intelligence Network for Exploration, with Techtree!

https://github.com/Kerbas-ad-astra/KAINET/blob/master/KAINET%20logo.png?raw=true

KAINET (rhymes with "Skynet") was inspired by an idle thought of mine: "What would it take to make a space program with no Kerbals in it?"  The more I thought about it, the more challenging I realized it would be.  For all of our jokes about their lack of common sense, Kerbals are handy critters to have around -- they can repack parachutes, pick up science, transfer supplies, and repair broken landing gear.  Unless there's a way for spacecraft to do the same things themselves, (not to my knowledge), the only way to "repair" things is to put it on a module that can be removed and replaced.  This has to be done using docking ports, since no Kerbals means no Kerbal Attachment System.  No Kerbals also means no building rockets with Extraplanetary Launchpads, so spare parts have to come all the way from Kerbin.  I guess this means the Kerbal universe is safe from self-replicating machines for the time being, though taniwha did mention having ideas for a separate mod enabling robots to build things when I brought this up in the EPL thread...

Anyway, since tech-tree mods seem to be all the rage these days, I figured I'd put together a little tech tree and career tweak to enforce these restrictions.  This patch will suppress any part with non-zero crew capacity, as well moving the Stayputnik to Start and the QBE to Stability (and tweaking their entry costs accordingly).  It also suppresses contracts involving flags, station and base construction, and surveys.  (I've decided to leave rescue contracts alone, because command chairs are not suppressed.)  I thought fiddling with the contracts was going to be really hard, but Arsonide put FinePrint's contracts in the same config node system as everything else, so thanks a million!

For extra immersion, go into your settings and disable the space center crew.

##Dependencies

Depends on [Module Manager](http://forum.kerbalspaceprogram.com/threads/55219) to function.

##Download and install

* Download from CurseForge
* Download from KerbalStuff
* Download from GitHub

From there, just unzip the "KAINET" folder into your GameData directory.

##Recommended addons

* [Contract Configurator](http://forum.kerbalspaceprogram.com/threads/101604) and [InitialContracts](https://kerbalstuff.com/mod/577/InitialContracts) to get rid of the initial altitude-record contracts which require a Kerbal, and replace them with similar contracts that don't.
* Flag Decals pack from [SciFi Shipyards](http://forum.kerbalspaceprogram.com/threads/37908) for flags that don't require Kerbals (including a folding flag).  Sadly, they don't act as flags for the purposes of contracts, nor do they appear as flags on a map, nor can they be given plaques, but they look cool!
* [Infernal Robotics](http://forum.kerbalspaceprogram.com/threads/37707) for articulation bits to help with assembly and "repair".  Its [model rework](http://forum.kerbalspaceprogram.com/threads/65365) is really slick as well.
* [Ship Manifest](http://forum.kerbalspaceprogram.com/threads/62270) to allow "unkerbed" (:wink:) transfer of science.
* Starwaster's [Probe Science patches](http://forum.kerbalspaceprogram.com/threads/56137) to allow probe cores to do more science themselves.  If these patches are present, and specifically are in a folder by the name "StarwasterSciencePatches" (as they are in the package by default), then this patch will alter survey contracts instead of suppressing them, to allow probes to perform their equivalent experiments.

##Version history

* 1.0 (2015 Feb 14): You're looking at it!

##Known and anticipated issues

Do note that this patch will apply to all saves on its install!  It won't destroy any ships in flight or in the editor that have crewed parts, but you won't be able to make any new ones!

##Roadmap

I'm pretty happy with this patch as it is, but if you want to see any changes, suggest them here or contribute to the GitHub repository.  Is there a way to get rid of those initial contracts without depending on Contract Configurator?  I'd look at how Contract Configurator does it, but (a) I'm worried that it will require a custom DLL and (b) Contract Configurator's license is incompatible with KAINET's (in addition to being [generally inappropriate for a software project](https://wiki.creativecommons.org/Frequently_Asked_Questions#Can_I_apply_a_Creative_Commons_license_to_software.3F) -- if Contract Configurator were released under the GPL, I would be totally fine with using some of its code and then inheriting that license).

I'm also working on a series of modular vehicles that can be suitable for KAINET missions.  I'll probably put up a thread about them in The Spacecraft Exchange as they're made.

##Source

The source for this addon is hosted on GitHub.  (The whole thing is pretty much its own source.)

##License

This addon is copyright 2015 Kerbas_ad_astra.  Configuration files are released under the [Apache 2.0 license](https://www.apache.org/licenses/LICENSE-2.0).  All other rights reserved.
