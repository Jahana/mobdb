# MobDB
MobDB is an addon that displays monster information onscreen, in the same vein as ibar.  For most users, you should not need to do anything besides loading the addon.<br><br>

## /mobdb (/md) config ##
You can type this command to edit the appearance of mobdb and change the tokens, either for a specific character or for all characters.  The 'Edit Tokens' button will allow you to change the display strings.

### Usable Tokens
- `$name` - The name of your current target.
- `$ph` - ⭐ Displays if selected target is a placeholder for a NM. ⭐
- `$index` - The zone-specific index of your current target.
- `$hexindex` - The zone-specific index of your current target, in hex notation.
- `$hexid` - The game-specific id of your current target, in hex notation.
- `$id` - The game-specific id of your current target.
- `$zone` - Your current zone\'s name.
- `$job` - Your current target\'s job if available, ??? if not.
- `$level` - Your current target\'s level if available, ??? if not.
- `$joblevel` - Format [Lv33-37] [Lv33-37 WAR] [WAR35/SAM18] depending on available information.  Nothing if not available.
- `$position1` - Position in the format "(X, Y) Z:Z" with 2 decimal places.
- `$position2` - Position in the format "(X,Y) Z:Z" with no decimals.
- `$position3` - Position in the format "X:X Y:Y Z:Z" with 2 decimal places.
- `$position4` - Position in the format "X:X Y:Y Z:Z" with no decimals.
- `$strength` - Graphical display of weapons and elements the mob is strong against.
- `$weakness` - Graphical display of weapons and elements the mob is weak against.
- `$physical` - Graphical display of weapon types the mob is strong or weak against.
- `$magical` - Graphical display of elements the mob is strong or weak against
- `$physmagic` - Graphical display of elements and weapons the mob is strong or weak against.
- `$immunity` - Graphical display of debuffs that a monster is immune to.'
- `$hpp` - The target\'s current HP percentage.
- `$dynamic` - Dynamic if the monster is a custom spawn, Static if it is a normal spawn.
- `$aggro` - Graphical display indicating whether the target aggros, links, is a NM, and how it detects you.
- `$speed` - Entity speed, displayed in format 100%% 125%% etc.
- `$speedrelative` - Entity speed, displayed in format +12.5%% -12.5%% etc.'
- `$debugflags` - Show all flags for debug purposes.'
- `$debugimmunity` - Show all immunity icons for debug purposes.'
- `$direction` - Show the cardinal direction in which the target resides.'
- `$notes` - Any notes saved on the target in the database.  Multiple notes always take a new line.

## Bugs - If you find bugs in PH Data, or Dynamis Mob Naming, please create an issue with the details.
