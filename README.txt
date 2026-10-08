LastChance item icons for Unturned UI

LastChance.NpcUi configuration:
<IconUrl>https://raw.githubusercontent.com/XXX-TYPE/LastChance-Item-Icons/main/icons/{itemId}.png</IconUrl>

The plugin replaces {itemId} with the numeric item ID. The configuration uses one URL template for the whole icon collection.

Images: PNG with transparency, maximum dimension 256 pixels.
Actual item images: 1275.
Transparent fallbacks for absent/invisible models: 24 (listed in missing-models.json).
Unique item IDs covered: 1297.
Total image size: 8.92 MiB.

icons/ contains the primary image for each ID. Duplicate source IDs 12036 and 25546 have additional images in variants/. A numeric ID cannot distinguish those source definitions; the primary images use the first source folder in lexical order.

The plugin already requests client-side caching and does not force refresh. The first download depends on the player's network; subsequent views may use the client cache. No game models or original asset bundles are hosted here.

Public read access. No collaborators have been added; modification is through owner XXX-TYPE.
