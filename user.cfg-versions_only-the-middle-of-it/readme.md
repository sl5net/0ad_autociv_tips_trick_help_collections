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

### this selects all >N<on MilitaryWorker (Wim & Support&Elephant):
nonMilitaryWorker=  "Alt+N" (any suggestions?)

### this selects only Support&Elephant (not all Elephant):
hotkey.autociv.session.entity.by.class.select.(Support&Elephant) = "Alt+E"

### this selects only nowoundedonly using mouse (May think about oK. he is ok or so):
hotkey.autociv.selection.nowoundedonly = "K"

### this selects only woundedonly using mouse (think about: Lie down to bed better to geht healty again):
hotkey.selection.woundedonly = "L"

### wounded needs healer (think about key next to H -> J )

hotkey.autociv.session.entity.by.class.select.Healer = "Alt+H"

hotkey.autociv.session.entity.by.health.wounded.by.class.select.(Cavalry|Infantry|Soldier|Siege|Dog|Elephant|Support) = "Alt+J"

recomandet:

set Optopms>Settings>GameSession>WoundetUnitHealth to 22 or so.

### Howto find the names? i use create map scenario editor

BTW cant find WarElephant into the scenario editor

or look here:

0ad-master/0ad-master/binaries/data/mods/public/maps/random/jebel_barkal.js

https://github.com/0ad/0ad/blob/master/binaries/data/mods/public/maps/random/jebel_barkal.js

## open discussion:

### are this good names/shortcuts?

### select Archer

hotkey.autociv.session.entity.by.class.select.(Infantry&Archer|Elephant&Archer) = "Alt+A"

### select military:
hotkey.autociv.session.entity.by.class.select.(Soldier|Siege|Dog)&!Ship = "Alt+M"

### select ... whats that:
hotkey.autociv.session.entity.by.class.select.(Soldier|Siege|Dog)&!Ship&!Ram = "Alt+S"

### select ... howto select speerman and swordsman?

hotkey.autociv.session.entity.by.class.select.(Infantry&Speerman) = "Alt+S"

hotkey.autociv.session.entity.by.class.select.(Infantry)&!Archer = "Alt+S"


# hotkey.autociv.session.entity.by.class.select.(Soldier|Siege|Dog)&!Ship&!Ram = "Alt+S"


### this is user.cfg location in your linux:

~/snap/0ad/201/.config/0ad/config/user.cfg

#### default.cfg

default.cfg is specified here: https://github.com/0ad/0ad/blob/master/binaries/data/config/default.cfg
On Linux, create:                                          *
; *   $XDG_CONFIG_HOME/0ad/config/local.cfg                    *
; *   (Note: $XDG_CONFIG_HOME defaults to ~/.config)           *
; *                                                            *
; * On OS X, create:                                           *
; *   ~/Library/Application\ Support/0ad/config/local.cfg      *
; *                                                            *
; * On Windows, create:                                        *
; *   %appdata%\0ad\config\local.cfg  

#### starts with:

 autociv.gamesetup.countdown.enabled = "false"

end ends with:

lobby.history = "150"

lines later like: lobby.login
or not included. take yours.

### Problems:

no known problems at the moment 20210331205937

BTW but check config clash with some hotkeys here:

https://trac.wildfiregames.com/wiki/HotKeys

### not pretty:

using Ctrl+O

starts creating Outoist AND open a other GUI window (not wandet at the moment 20210405075333)
