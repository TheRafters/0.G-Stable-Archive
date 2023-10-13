# Goals of *Loadout*

## Extension of choice

The primary goal of *Loadout* is to add new gunmods and related equipment in order to extend the choice available to the player. In reality, there are dozens and dozens of items that fit in the same category, differentiated between each other in size, weight, and performance.

This extension of choice must rest on the fact of the added options being distinct from one another. Adding two items which are very similar in their properties does not result in a larger array of choice, by itself. (See non-goals.)


## Reality and groundedness

Items added by the mod must be grounded in reality as much as the game would allow. This extends to their physical properties (`weight`, `volume`, `longest_side`...), class properties (e.g. `sight_dispersion` for sights, `handling_modifier` for grips), names (brand names, in particular), and other descriptors.

The purpose of this groundedness is to make the fictional world of the game feel that much more real. Groundedness aids immersion and imagination, both of which aid investment into the game process.

It should also allow one to scratch that itch that demands a more-accurate reflection of reality in all fictional things that some of us have.


## Cohesiveness with the base game

The previous two goals should not conflict with the mod being easily-added to a playthrough. While it's inevitable that *Loadout*'s groundedness will make it clash with the generic content of the base game in terms of aesthetics (e.g. "suppressor" vs. "SilencerCo Hybrid 46 suppressor"), nothing should prevent the mod's contents from being easily included in a fresh playthrough.

This is most-relevant with balance: in-game properties must be thoughtfully balance between reality and existing balance. For example, in reality, suppressors rarely reduce volume of shot by more than 25 dB. This means that shots are rarely Hollywood-quiet: they're still very much audible, though perhaps with a skewed signature, making recognizing the exact direction of fire and make of the gun more of a challenge. The main purpose of suppressors is to prevent hard to shooter's ears during fire. All of this combined means suppressors cannot be very effective at removing noise during shooting: −45 vs. .223 Remington's computed loudness of 164 is effective, but still realistic and balanced.

This also applies to things like gunmod slots: relying on base-game slots makes the mod significantly less-complex, while also extending the possibility of complete compatibility with mods that add guns of their own.


# Non-Goals of *Loadout*

## Adding every single item of a given class

There are dozens, if not hundreds, of items in any given class (e.g. angled grips, variable-magnification scopes), each performing slightly differently than the other. However, adding every one of them is going to be:

1. **time-consuming**: for some models of items, it takes a lot of time to ascertain certain properties, most often physical dimensions
2. **memory-intensive**: the game must hold these items in memory, potentially bloating safe files
3. **confusing to players**: having too many items to remember, consider, or carry around will be a burden in a game already throwing a lot of knowledge-based survival at the player

Therefore, quality (distinctive properties of an item) should be prioritized over quantity (sheer number of items). In other words: having fewer items that are distinct from each other within their class is preferable to having more items that offer gradual performance difference.


## Changing anything about existing firearms

Making changes to existing guns is outside of the scope of this mod, and thus will not be pursued. While it may be convenient to change available slots here and there, such changes will introduce a lot more complexity in supporting the mod in the future, while reducing compatibility with other mods that add guns.

Should the need arise to bridge functionality between *Loadout* and another mod that changes guns, a patch must be created by the interested party. The contributors of *Loadout* provide no guarantee of a patch for any mod outside of the Frontier Mods ecosystem.


## Adding new firearms

Much like making changes to guns, adding new guns is outside of the scope of this mod.

The only exception to this is adding attachments that behave like guns or melee weapons: if their primary or advertised use is being attached to another weapon, they may be considered gunmods.