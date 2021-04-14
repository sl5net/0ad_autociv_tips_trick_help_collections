### you can't remember the hotkeys?
try this:

FirstLetter of the Building (press several times for toggling)
 ==> build the Building

Ctrl+FirstLetter of the Building
 ==> selects Building or the Buildings

ALT+FirstLetter of the Creature
 ==> selects Creature or Creatures

### exceptionally other spellings:

### this selects all >D<angerous E. archer-,war-,hero-Elephant,... (not Support&Elephant):
hotkey.autociv.session.entity.by.class.select.(Elephant)&!Support = "Alt+D"

### this selects only Support&Elephant (not all Elephant):
hotkey.autociv.session.entity.by.class.select.(Support&Elephant) = "Alt+E"

### select Barracks + ElephantStable + Stable) "Ctrl+X" (remember X like nearly everythink)
hotkey.autociv.session.entity.by.class.select.(Barracks|ElephantStable|Stable) = "Ctrl+X"

### this selects only nowoundedonly using mouse (May think about oK. he is ok or so):
hotkey.autociv.selection.nowoundedonly = "K"

### this selects only woundedonly using mouse (think about: Lie down to bed better to geht healty again):
hotkey.selection.woundedonly = "L"




### Howto find the names? i use create map scenario editor

BTW cant find WarElephant into the scenario editor



### this user.cfg

replace beetween:

starts with:

 autociv.gamesetup.countdown.enabled = "false"

end ends with:

lobby.history = "150"

lines later like: lobby.login
or not included. take yours.


#### user.cfg in ubuntu snap:

~/snap/0ad/201/.config/0ad/config/user.cfg

#### user.cfg in windows?:


### Problems:

no known problems at the moment 20210331205937

# interesting

## selects not tower:
hotkey.autociv.session.entity.by.class.select.(Defense_tower|Sentry_tower|Temple) = "Ctrl+T
## selects (senty-)/towers:
hotkey.autociv.session.entity.by.class.select.(Temple|Tower)&!Ship = "Ctrl+T"


