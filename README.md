osx-new-phonetic (чшерти)
================
Bulgaria New Phonetic keyboard layout adapted for macOS, Layout is similar to Windows 7 & Vista sets
----------------
Българска (прБДС 5237 от 2006) Фонетична клавиатура адаптирана за macOS, подоба на тази в Windows 7 & Vista
----------------

> Note: Opening/closing double quotes as well "En Dash" are intentionally omitted as macOS consistent alternative is available using ```[options]``` combos (see last layout bellow)

Inspired by [BDS-bg.org (PDF)](https://bds-bg.org/images/upload/Novini/prBDS_5237(1).pdf) .
If curious about this proposed standard check [Wikipedia topic](https://bg.wikipedia.org/wiki/Фонетична_подредба#Проект_за_стандарт_прБДС_5237:2006_(нова_фонетична_подредба,_подредба_за_устройства_с_малко_клавиши,_и_променена_БДС_5237:1978))

## Install steps

### Step 1. Clone this repo OR download the two files:

```Bulgarian - New Phonetic.icns```

```Bulgarian - New Phonetic.keylayout```

### Step 2. Select and copy (Command + C) the TWO files 

![Copy the two custom keyboard files .keylayout and .icns](<readme_files/Install - Copy the two files.png>)

Navigate to one of two system folders

![Go to a system(hidden) folder on macOS](<readme_files/Install - Go to a system folder.png>)

#### Option 1: For System wide install (requires Admin permissions)

- Copy files to ```/Library/Keyboard Layouts/```

![System location](<readme_files/Install - System location.png>)


#### Option 2: For Current logged users (will be available post login screen)

- Copy files to ```~/Library/Keyboard Layouts/``` note the ```~``` at the start

![Current User location](<readme_files/Install - Current User location.png>)

> Note: Keyboard layout in ~/Library/Keyboard Layouts/ can't be selected on **password dialogs** or on the **login screen**.

### Step 3. Paste (Command + P) the files

![Paste the two files](<readme_files/Install - Paste completed.png>)


### Step 4. !!! Restart !!!!

> This stem is very IMPORTANT! 

> Note: Logging out and back in is not enough.


### Step 5. Enable the new keyboard layout from 
Open ```System Preferences``` and open ```Keyboard``` panel


### Step 6. Add new input source 

- Navigato to the tab called ```Input Sources``` 

- Click the plus button ```+``` at bottom left corner 

![Add Custom Imput Source in macOS](<readme_files/Install - Add Custom Keyboard Layout.png>)

- Then pick language ```Other```

![Pick Bulgarian Phonetic from Other langue option](<readme_files/Install - Pick Bulgarian Phonetic from Other at the end.png>)

- Click ```Add button``` and enjoy


## Keyboard Layouts

### No special keys pressed

![Bulgarian New Phonetic keyboard layout](<readme_files/OSX-BG-New-Phonetic-Layout.png>)

### ```shift``` key pressed

![Bulgarian New Phonetic keyboard layout - SHIFT](<readme_files/OSX-BG-New-Phonetic-Layout-SHIFT.png>)

### ```caps lock``` active

![Bulgarian New Phonetic keyboard layout](<readme_files/OSX-BG-New-Phonetic-Layout-CAPSLOCK.png>)

### ```caps lock``` active and ```shift``` key pressed

![Bulgarian New Phonetic keyboard layout - CAPSLOCK & SHIFT](<readme_files/OSX-BG-New-Phonetic-Layout-CAPSLOCK-SHIFT.png>)

### Special character sequences

Press ``` option + ` ``` modifier

![Bulgarian New Phonetic keyboard layout - Modifier](<readme_files/OSX-BG-New-Phonetic-Layout-Modifier.png>)

... followed by one of keys (in blue)

![Bulgarian New Phonetic keyboard layout - Modifier Set](<readme_files/OSX-BG-New-Phonetic-Layout-Modifier-Set.png>)

### ```options``` key pressed

![Bulgarian New Phonetic keyboard layout - OPTION](<readme_files/OSX-BG-New-Phonetic-Layout-OPTION.png>)

Enjoy!

_LICENSE: MIT_

Made using [Ukelele](https://software.sil.org/ukelele/)

For iconset regeneration: ```iconutil -c icns icon.iconset```