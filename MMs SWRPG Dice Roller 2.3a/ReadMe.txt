MMs SWRPG DICE Roller ReadMe


1) Statistics Functionalit Explained
	Success Chance:
		This denotes the chance for the given roll to succeed. To count as a success the player must have at 
		least one more success than the opposing side. Triumph markers are added to the success count.
		Advantage does not factor into this calculation.
		
	Bar Charts:
		The bar charts show the distribution of possible results for each given dice pool.
		The green bar chart for the player side (green, yellow and red die), the red bar chart for the
		enemy/difficulty side (violet, red, black die).
		Force die do not factor into this calculation.
		The value is determined based on this scoring system: 
			Success: 1 point, Advantage: 0.5 points, Triumph: 2 points
		The distribution is given as a percentile value.
		Upon rolling the achieved results are marked as blue.
		The farther right the blue bar is, the "luckier" the roll. (the opposite is true for the red chart)
		
	Due to size restrictions statistics data is only given for pools of up to 20 dice (excluding force dice)
	This data takes up roughly 400 megabytes. It can be found in the folder "DATA"

	Data is no longer loaded in by default. To use statistics functionality the user must toggle the option in the program.
	For slow systems this might lead to slight slowdowns. By untoggling the checkmark again the data can be dumped, thus
	freeing up system resources.


2) Graphics and Symbols
	All used graphics and symbols can be found in the folder "IMG" and its subfolders.
	If so desired the user can easily customize their copy of the program by exchanging pictures in this folder.
	To work properly the following conditions must be met:
		The name of the new file should be identical to the replaced file
			this is case sensitive
		The resolution should be identical to the replaced file
		The filetype should be png

3) Managing and saving dice pools
	The new dice pool manager allows the user to save multiple dice pools and quickly recall them with a click.
	Up to 25 dice pools can be saved at any time.

	How to create a dice pool:
		In the dice pool manager the upper text field on the right hand side can be used to input a category name
			This can be a player name or any other useful category that is desired
		After Inputting the desired name the Category is created by clicking the green plus mark next to it
		Up to 5 Dice pools can now be added to this category.

		To add a dice pool the user can now click on the created category to select it.
		Below the category input field is a small symbol selector and a smaller text input field.
		To differentiate between the dice pools in a category the user can now select a symbol of choice
			alternatively a short string can be put into the text field next to the symbol selector
		Pressing the second green plus mark creates the new dice pool in the selected category.
			The dice pool takes the selected symbol or - if given - the string identifier
			The dice pool saves the current dice upon creation

	How to load a dice pool:
		To restore the number of dice selected at creation simply click on the desired dice pool symbol

	How to change the symbol:
		Select the dice pool that is to be changed, select a new symbol from the symbol selector or input a string
		Then press the "Change Symbol" Button

	How to Change the amount of dice in a saved pool:
		Select the dice pool that is to be changed. This loads the saved pool.
		Adjust the amount of dice by adding or removing dice.
		Then press the "Change Pool" Button

	How to Delete a dice pool:
		Select the dice pool that is to be deleted
		Then press the "Delete Symbol" Button

	Delete a category and all associated dice pools:
		Select the category or any of its dice pools
		Then press the "Delete Row" Button

	How to permanently save my dice pools and restore them at a later time:
		Pressing the "Save to File" Button saves all categories and dice pools to the "userdata.json" file
		This file is preserved even after closing the program.
		At any given time the saved categories and pools can be restored by pressing the "Load from File" Button.

		Warning:
			Only one such file is present at any given time. Pressing the "Save to File" Button will overwrite the old file.
				This is permanent.
			To avoid accidental overwriting or preserve multiple files it is possible to manually make copies of the "userdata.json" file 
			and store it in a compressed state or a seperate folder.
			