# A24 

this is not totally tested in A25

### todo:

in A24 skirmish cav are called cavalry_javelineer instead of javelinist  

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

### select all military is of course Alt+M but also Alt+X (remember X like nearly everythink)
hotkey.autociv.session.entity.by.class.select.(Soldier|Siege|Dog)&!Ship = "Alt+M", "Alt+X"

### this selects only nowoundedonly using mouse (May think about oK. he is ok or so):
hotkey.autociv.selection.nowoundedonly = "K"

### this selects only woundedonly using mouse (think about: Lie down to bed better to geht healty again):
hotkey.selection.woundedonly = "L"

### dificult to remember: select Siege_Unit :

select https://0ad.fandom.com/wiki/Siege_Unit 's :

rams, not heros, Catapult, Bolt Shooter, Siege Tower

hotkey.autociv.session.entity.by.class.select.Siege = "Alt+V"

suggestion?

### selects diplomacy with Ctrl+< (think about: give out, move resources to your partners):

hotkey.session.gui.diplomacy.toggle = "Ctrl+SYM_100"


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


#### user.cfg in ubuntu maybe:

~/snap/0ad/201/.config/0ad/config/user.cfg

~/snap/0ad/206/.config/0ad/config/user.cfg

.... /0ad/binaries/data/config/user.cfg

~/snap/0ad/206/.config/0ad/config/user.cfg

#### user.cfg in windows:

%appdata%\0ad\config\user.cfg

### Problems:

no known problems at the moment 20210331205937

# interesting

## selects not tower:
hotkey.autociv.session.entity.by.class.select.(Defense_tower|Sentry_tower|Temple) = "Ctrl+T
## selects (senty-)/towers:
hotkey.autociv.session.entity.by.class.select.(Temple|Tower)&!Ship = "Ctrl+T"


### some comments about the cnanges:
little simplification:

hotkey.autociv.session.entity.by.class.select.(Infantry&Archer|Infantry&Slinger|Infantry&Javelineer|Elephant&Archer) = "Alt+A"
hotkey.autociv.session.entity.by.class.select.(Infantry&Soldier)&!Slinger&!Slinger&!Javelineer&!Archer&!Spearman = "Alt+S"
hotkey.autociv.session.entity.by.class.select.(Infantry&Pikeman|Infantry&Spearman|Champion&Fanatic) = "Alt+P"

=>

hotkey.autociv.session.entity.by.class.select.(Archer|Slinger|Javelineer|Archer) = "Alt+A"
hotkey.autociv.session.entity.by.class.select.(Soldier)&!Slinger&!Javelineer&!Archer&!Spearman = "Alt+S"
hotkey.autociv.session.entity.by.class.select.(Pikeman|Spearman|Fanatic) = "Alt+P"


maybe its later not optimal. so here its to easy remember
