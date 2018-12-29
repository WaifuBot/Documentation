# Claiming

Claiming waifus is one of the core features of WaifuBot. If claims didn't exist, WaifuBot would not exist. Claiming should not be confusing at all: there are instructions on every character spawn for how to claim a waifu. If you're still confused, this page of the documentation is for you.

## Character Spawns

In order to claim a waifu, there must be an active spawn in the channel that you are claiming in. Active spawns look something like this:

![spawn](https://cdn.discordapp.com/attachments/485936130064384001/528448071751827470/unknown.png)

You will need to know the character's full name to claim them—all names are romanized using [MyAnimeList's database standard](https://myanimelist.net/forum/?topicid=128975).
The key pieces of information you will be interested in here are the initials and the spawn image; more experienced users will also be interested in the border color (see Rarity.)

## The Claim Command

![claim](https://cdn.discordapp.com/attachments/485936130064384001/528452428132253708/unknown.png)


To claim the character, use the ``w.claim <name>`` command, where ``<name>`` is replaced by your guess of what the character's name is. An example of a properly executed claim command that is valid for the image above is ``w.claim cirno``. Notice how the "c" in "Cirno" is not uppercase? You don't have to worry about capitalization when typing out names for claims. In fact, you don't even have to worry about diacritical marks while claiming; all diacritics and special unicode is stripped or normalized to standard letters when they are being processed for claims. Names like "Scáthach" become "Scathach".

## Additional Rewards While Claiming

Sometimes claiming will give you a small WeebPoint reward.