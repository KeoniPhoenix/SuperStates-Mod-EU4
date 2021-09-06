Important Standards when Modding SuperStates Mod for EU4

---Scope of Area---

The mod's scope of area is to defined as the subnational entities of nations with a federal system within the regions of Australia, Oceania, North and South America.  Not all federal nations are included currently (Brazil, Venezeula, Argentina, the long since defunct Federal Republic of Central America; over time these are expected to be added).

Most nations that are added that aren't federal in nature are included as flavor and are only intended to appear as the game progresses (such as the currently implimented Caribbean nations not part of the United States) and others are implimented from the start due to their past association with the United States or other federal nation (UN Pacific Trust Territories in the late 20th century).

The mod will not include any area or nation within Africa, Asia, or Europe.

---Nation Tags--- (country_tags/00_countries.txt)

Nation Tags are required to be unique in order to avoid issues with debugging the mod in game.
However, vanilla tags change from time to time in major updates and may require reassigning mod nations tags.
Mod nations that are in the vanilla game and are to be modified for the mod are to use the vanilla tag to make debugging easier and to keep the tag list in the game short.
Vanilla tags that are introduced due to an update take precedence over mod tags if the new vanilla tag is not in the area covered by the mod.
New tags and reassigned tags for nations wthin the mod area should be checked agaist the master tag list used by the mod and by vanilla before being included.

Too many tags is a performance hit to EU4 as the current game engine is required to assign an AI to each and every tag in the tag list, this is should be as compact as possible to minimize unnecessary assignment of an AI to a tag.

---Provinces---

There are important rules on modding provinces in SuperStates Mod for EU4.

Provinces added to or modified on the map within the Mod's area are a collection of US county-equivalent local governments.  Not every nation (or even US state) follows the same idea as to what is a county or is an equivalent.  GIS maps are heavily used in drawing along modern boundaries of these county-equivalent local government bouandaries.  This tends to make blocky provinces in parts of the map but it is a design decision by the original author, KeoniPhoenix, to make editing the map more consistent and keep it somewhat accurate.

Province and their capital city names in the mod take the following format:  The collection of county-equivalent governments that make up a province are named based on the location of the largest county seat within that collection.  For instance the in Northeastern Illinois, Chicago being the largest city among the counties that make up the province requires the province to be named Cook and the capital city to be named Chicago.

This system breaks down however in some places that use different concepts when creating their local governments (Australia).  In the case of Australia, the province and capital city name are the city name of the metropolitan area.  For instance Sydney is a collection of differently sized local governments but grouped into the geographcial "Sydney" region, much like how the real life Greater London is just called London despite the City Corporation of London being only a square mile and a population of a few thousands.

Some Canadian provinces have only a single level of local government but have different types.  Provinces like Edmonton in Alberta are to be named after their principal cities but other provinces are named after the largest rural municipality that might apply (though for now most are named after principle cities).  Ontario and Quebec use a mixed system of counties and depending on which city can either be a single tier municipality, like Toronto, or a second tier munciaplity like Owen Sound.  Second Tier cities in Ontario and Quebec are to be treated as if they were in the US, and those that are county seats are the capital name and their county name is the province name.

Mexico operates mostly like the US however most of the time the county-equivalent is the only local government in that state, municipalities in Mexico are varied by state just like the United States.  The same rules apply in naming, though most large cities are also their municipality name in most, but not all, instances in Mexico.

---Use of DLC Features---

Some features of DLCs can be implemented within the mod, however the code for them must always restrict it so as to require the DLC in question to be active for the players playing the mod.  This is entirely a liability reduction issue between the Mod authors and Paradox Interactive.

---Mod Distribution---

The mod's official release will always be from the Steam Workshop and while the mod files can be downloaded from GitHub, it requires manual installation which will never be supported except by special extraordinary means.  Support for the mod requires proving the game is within one's Steam library and the discretion of the Mod author, KeoniPhoenix.

---Mod Name---

The names SuperStates and SuperStates Mod and any variants (i.e. "New SuperStates Mod") is retained by the mod author, KeoniPhoenix.  If the mod is forked or modified into a new project, it must use a new name as to avoid issues with this mod project.  If the issue is particularly egregious, official action may be taken.
