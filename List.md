# List and Waifu ID Types

Cool, you went ahead and claimed yourself a waifu. Now how do you see em'? Use the list command.

## The List Command

![list](https://cdn.discordapp.com/attachments/485936130064384001/528455123719028746/unknown.png)

You can pull up your list with ``w.list``. From left to right in one row of the list is:

- your waifu's local ID (see local ID)
- (possibly) your waifu's favorite indicator with a category
- your waifu's rarity/type
- your waifu's name
- your waifu's Japanese name
- your waifu's affection level

## Filtering and Ordering of the List

Want to filter your list down to certain characters? No problem. The list command includes a variety of filters for you convenience. The syntax for filtering is ``w.list [-filter type] [filter value if applicable]``. All of the filters can be viewed by using the help command with "list" as a parameter (``w.help list``), but I will list them here anyway.

- Viewing another user's list (requires their list to be public): ``w.list -user <user mention or tag>``
- Viewing waifus you have that are on another user's wishlist: ``w.list -wishlist <user mention or tag>``
- Filtering by waifu name: ``w.list -name <name>``
- Filtering by rarity/type: ``w.list -type Alpha``
- Filtering by a certain series: ``w.list -series <series name>``
- Filtering by which waifus are interactable: ``w.list -interactable``
- Filtering by which waifus you have favorited (optionally, also by their category): ``w.list -favorite <optional emoji>``
- Order by various waifu attributes: ``w.list -orderby <csi, strength, agility, defense, endurance, affection, name, type, affection, alphabetical>``

## Waifu ID Types

The ID types used by WaifuBot can be confusing at first, but they are very easy to understand.

### Local ID

Local ID is what most of WaifuBot's commands use. A waifu's local ID is found on the leftmost column of the ``w.list`` command. The local ID is bound to an instance of a waifu, and it tends to fluctuate if you trade a lot. Make sure that you always double check the ID from the list before doing commands!

### Global ID

Global ID is your waifu's true ID. You can get it with the ``w.view <local id>`` command. As far as I know, no commands actually use global ID and it is just there for database purposes—it's useless to the average person.

### Character ID

While global ID and local ID is bound to an instance of a waifu (a waifu that you claimed), character ID is bound to a certain character. Think of local ID as a car that you own, and character ID as the car's model. Commands that involve lookups or viewing of character data (not waifu data!) use character ID.

### Series ID

Same as character ID, except for series.