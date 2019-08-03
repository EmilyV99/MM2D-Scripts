///////////////////////////////
//                           //
// Majora's Mask 2D - Readme //
//      Version: Demo 5      //
//      ZC Ver: 2.55 A29     //
//                           //
///////////////////////////////

Current script source: https://github.com/venrob/MM2D-Scripts/tree/BACKUP/DEMO/Demo5

//////////////////
//  Setup Menu  //
//////////////////
This menu opens after the title screen, on starting a new save.
After you close this menu, it will NEVER open again, unless you
begin a new save file.

~~~SETUP~~~
Begin Game:
	End the setup menu, and start playing!
	This is the only way to close this menu.

Options:
	Open the Options menu. This menu can be opened during gameplay,
	by pressing whataver control you bind it to (default 'TAB')

Razor Sword Never Breaks:
	The 'Razor Sword' becomes a permanent item, rather than a temporary
	item, if this option is 'True'
	DEFAULT: 'False'

Skip Beaver Race:
	If this option is 'True', the item at the Beaver Race will be given
	to you when you enter, instead of requiring playing the swimming
	minigame first.
	DEFAULT: 'False'

~~~RANDO~~~
Randomizer:
	If this option is 'On', the game will be randomized.
	Any further options relating to the randomizer will be unselectable
	(greyed out) if this option is set to 'Off'.
	DEFAULT: 'Off'

Seed:
	The seed for use in the randomizer. Selecting this option opens the
	'Seed Selector' submenu.
	DEFAULT SEED: Randomly generated on quest init.

~~~RANDFLAGS~~~
Start with Song of Soaring:
	If this option is 'True', you will begin the game knowing the
	Song of Soaring.
	DEFAULT: 'False'

//////////////////////////
//  Seed Selector Menu  //
//////////////////////////

In this menu, there are 2 buttons, 'Random' and a seed number.

Selecting 'Random' will randomize the seed.

Selecting the seed will open an input prompt. In this input prompt,
you may type a seed manually. (Use 'Enter' to confirm)
If the manually entered seed is too large, it will be allowed to
overflow, creating a number that is in the valid range.

Exit this menu with 'Backspace' or the 'B' Button.
Confirm an option in this menu with 'Enter' or the 'A' Button.

Valid seed range: -2,147,473,648 to +2,147,473,647


////////////////////
//  Options Menu  //
////////////////////
This menu opens either from the 'Game Setup' menu, or by using the
chosen hotkey (default 'Tab') at any time.

~~~OPTIONS~~~
Flip Right-Facing Slash:
	If this option is 'On', slashing the sword while facing right will
	slash diagonally right-down, instead of right-up, with all swords.
	DEFAULT: 'Off'

Lens Tint Color:
	This allows you to select (and preview) the color of the tint the
	'Lens of Truth' colors the screen during use.
	DEFAULT: -17r, -48g, +5b

Hide Tint in Menus:
	If this option is 'On', tint effects will be disabled when you open
	a menu. This is recommended to ensure menu visibility.
	DEFAULT: 'On'

Menu Scroll Speed:
	How fast (relative to the default speed) the menu scrolls between
	tabs when pressing left/right.
	DEFAULT: 1x

Menu Input Hold Delay:
	In menus, pressing a direction will be taken as an input. However,
	holding a button down will ALSO register as an input, every X frames.
	This option sets how many frames that is.
	DEFAULT: 30

~~~CONTROLS~~~
Options Menu:
	This key can be used to open/close the options menu at any time
	during gameplay.
	DEFAULT BINDING: 'Tab'

~~~SYSTEM~~~
Font:
	This is the font used for a number of custom menus. Most ZC fonts
	are available, except those that are non-english, incomplete,
	or too large to work with the menus.
	DEFAULT: 'LTTP SMALL' (FONT_Z3SMALL)

Reset All To Default:
	Selecting this option will reset every option in the Options Menu
	to their default values.


//////////////////////////
//  F6 / End Game Menu  //
//////////////////////////
This menu will open upon pressing 'F6', or selecting the ZC option
'Game>>>End Game'. It will also open when you game over.
Each option in this menu has a requirement for it to be available.
Unavailable options will not be displayed at all.

Continue:
	Continue from most recent continue point.
	Requirement: There is still time before the end of the final day.

Reset Time:
	Save and reset time, as with the 'Song of Time'.
	Requirement: Ocarina and Song of Time have been obtained.

Quit:
	Exit to title screen without saving.
	Requirement: None, this is always available.

Cancel:
	Exit this menu and return to gameplay.
	Requirement: You did not reach this menu through game over.

//End of readme; more documentation will be added in future versions
