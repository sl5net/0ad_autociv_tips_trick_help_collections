you cant remember the hotkeys?
try this:

FirstLetter of the Building (press several times for toggling)
 ==> build the Building

Ctrl+FirstLetter of the Building
 ==> selects Building or the Buildings

ALT+FirstLetter of the Creature
 ==> selects Creature or Creatures

ä exceptionally other spellings

# this selects all >D<angerous E. archer-,war-,hero-Elephant,... (not Support&Elephant):
hotkey.autociv.session.entity.by.class.select.(Elephant)&!Support = "Alt+D"

# this selects only Support&Elephant (not all Elephant):
hotkey.autociv.session.entity.by.class.select.(Support&Elephant) = "Alt+E"

# Howto find the names? i use create map scenario editor

# what i was not able to do (i tried):

cant find WarElephant into the scenario editor

cant select only WarElephant

sytaxError:

hotkey.autociv.session.entity.by.class.select.(War_Elephant) = "Alt+E"
hotkey.autociv.session.entity.by.class.select.(WarElephant) = "Alt+E"


# this user.cfg

starts with:

 autociv.gamesetup.countdown.enabled = "false"

end ends with:

lobby.history = "150"

lines later like: lobby.login
or not included. take yours.

# Problems:

no known problems at the moment 20210331205937
