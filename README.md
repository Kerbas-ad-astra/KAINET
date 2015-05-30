#No Astronauts Need Apply: Kerbal-less Space Program

*An addon for Kerbal Space Program which modifies the technology tree to allow (and require) players to refrain from using any Kerbals during their career. Formerly known as KAINET: KAA Artificial Intelligence Network for Exploration, with Techtree.*

The public has had enough of disaster-prone missions and "space cowboy" agencies whose ambitions are larger than their capabilities.  KSC administrators' protests that new safety regulations would cause crewed missions to become impractically expensive have fallen on deaf ears.  With heavy hearts, they have updated their hiring notices to reflect the new reality: *No Astronauts Need Apply.*

![No Astronauts Need Apply logo](https://github.com/Kerbas-ad-astra/No-Astronauts-Need-Apply/blob/master/No%20Astronauts%20Need%20Apply%20logo.png)

"No Astronauts Need Apply" was inspired by an idle thought of mine: "What would it take to make a space program with no Kerbals in it?"  The more I thought about it, the more challenging I realized it would be.  For all of our jokes about their lack of common sense, Kerbals are handy critters to have around -- they can repack parachutes, pick up science, transfer supplies, and repair broken landing gear.  Unless there's a way for spacecraft to do the same things themselves (not to my knowledge), the only way to "repair" things is to put it on a module that can be removed and replaced.  This has to be done using docking ports, since no Kerbals means no Kerbal Attachment System.  No Kerbals also means no building rockets with Extraplanetary Launchpads, so spare parts have to come all the way from Kerbin.  I guess this means the Kerbal universe is safe from self-replicating machines for the time being, though taniwha did mention having ideas for a separate mod enabling robots to build things when I brought this up in the EPL thread...

Anyway, since tech-tree mods seem to be all the rage these days, I figured I'd put together a little tech tree and contract tweak to enforce these restrictions.  This patch will suppress any part with non-zero crew capacity, as well moving the Stayputnik to Start and the QBE to Stability (and tweaking their entry costs accordingly).  It also suppresses contracts involving flags, station and base construction, and surveys.  (I've decided to leave rescue contracts alone, because the capsule itself can be rescued in various ways.)  I thought fiddling with the contracts was going to be really hard, but Arsonide put FinePrint's contracts in the same config node system as everything else, so thanks a million!

For extra immersion, go into your settings and disable the space center crew.

##Dependencies

Depends on [Module Manager](http://forum.kerbalspaceprogram.com/threads/55219) to function.

##Download and install

* Download from [CurseForge](http://kerbal.curseforge.com/ksp-mods/227824-no-astronauts-need-apply)
* Download from [KerbalStuff](https://kerbalstuff.com/mod/592/No_Astronauts_Need_Apply)
* Download from [GitHub](https://github.com/Kerbas-ad-astra/No-Astronauts-Need-Apply/releases)

From there, just unzip the "NoAstronautsNeedApply" folder into your GameData directory.  (Delete the "KAINET" folder if you have it from a previous install.)

##Recommended addons

* Flag Decals pack from [SciFi Shipyards](http://forum.kerbalspaceprogram.com/threads/37908) for flags that don't require Kerbals (including a folding flag).  Sadly, they don't act as flags for the purposes of contracts, nor do they appear as flags on a map, nor can they be given plaques, but they look cool!
* [Infernal Robotics](http://forum.kerbalspaceprogram.com/threads/37707) for articulation bits to help with assembly and "repair".  Its [model rework](http://forum.kerbalspaceprogram.com/threads/65365) is really slick as well.
* [Ship Manifest](http://forum.kerbalspaceprogram.com/threads/62270) to allow "unkerbed" (:wink:) transfer of science.  (This mod's config includes a patch that allows all probe cores to become science containers, so science results can be drained from heavy experiments.)
* Starwaster's [Probe Science patches](http://forum.kerbalspaceprogram.com/threads/56137) to allow probe cores to do more science themselves.  If these patches are present, and specifically are in a folder by the name "StarwasterSciencePatches" (as they are in the package by default), then NANA will only suppress survey contracts whose "experiments" require a crew (i.e. Crew Report, EVA Report, Surface Sample).

##Version history

* 1.0 (2015 Feb 14): Initial release.
* 1.0.1 (2015 Feb 15): Tweaks after some initial playtesting and revision.
	* Z-100 batteries moved earlier, into "Survivability".
	* Made the contract config patches less brittle -- no longer dependent on the order of blocks in Contracts.cfg.
* 1.1 (2015 May 30): Updated for 1.0.
	* Also, renamed from "KAINET" to "No Astronauts Need Apply".  It's more descriptive, and I want to use the KAINET name and flag for something else...

##Known and anticipated issues

* This patch will apply to all saves on its install!  It won't destroy any ships in flight or in the editor that have crewed parts, but you won't be able to make any new ones!

##Roadmap

I'm pretty happy with this patch as it is, but if you want to see any changes, suggest them here or contribute to the GitHub repository.

I'm also working on a series of modular vehicles that can be suitable for NANA missions.  I'll probably put up a thread about them in The Spacecraft Exchange as they're made.

##Source

The source for this addon is hosted on [GitHub](https://github.com/Kerbas-ad-astra/No-Astronauts-Need-Apply).  (The whole thing is pretty much its own source.)

##License

No Astronauts Need Apply is copyright 2015 Kerbas_ad_astra and is released under the [Apache 2.0 license](https://www.apache.org/licenses/LICENSE-2.0).  All other rights reserved.
