# [2019-08-26]
## Fixed
 - Character Create: Fix page not working due to incorrect order of routes.

# [2019-08-24]
## Added
 - Home Page: Add an introduction about what the site is.
 - Realm View: Add guild listing onto realm view pages.
 - Realms: Add the new realms from: https://www.wowhead.com/news=294640/more-new-classic-wow-realms-coming-august-26th
 - Add region index pages ([eu](https://wowtracker.xyz/classic/eu), [us](https://wowtracker.xyz/classic/us), [oceanic](https://wowtracker.xyz/classic/oceanic)) which list known servers.

## Changed
 - Character View:
   * Change url structure to /classic/{region}/{realm-slug}/character/{character-name}
   * Change character profession progress from profession 1/2 to the actual profession name.
 - Guild View: Change url structure to /classic/{region}/{realm-slug}/guild/{guild-name}

# [2019-08-19]
## Added
 - Character Edit: Ability to change professions and levels.
 - Guild Roster: Show character professions on the roster.

## Fixed
 - Guild View: Bug with character_class when character is invited to guild.
 - My Characters: Fix guild tag after character name.
