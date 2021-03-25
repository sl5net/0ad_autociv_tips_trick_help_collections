you cant remember the hotkeys?
try this:

FirstLetter of the Building (press several times for toggling)
 ==> build the Building

Ctrl+FirstLetter of the Building
 ==> selects Building or the Buildings

ALT+FirstLetter of the Creature
 ==> selects Creature or Creatures

# problems:
## select dog conflicts with Alt+D developer panal so switched to Ctrl+D

hotkey.autociv.session.entity.by.class.select.(Dock|Defense_tower|Dog)&!Ship = "Ctrl+D"
and
hotkey.autociv.session.entity.by.class.select.(Dog)&!Ship = "Alt+D"

# this user.cfg

starts with:

 autociv.gamesetup.countdown.enabled = "false"

end ends with:

lobby.history = "150"

lines later like: lobby.login
or not included. take yours.
