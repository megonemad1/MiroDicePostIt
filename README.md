# MiroDicePostIt
creating dice rolling in miro

## lines
dice icon on context menu of lines can be used to work out the longest edge distance between the start and end points. this is mesured in squairs on the miro grid, and displayed in 1squair and 5ft mesurements

## dice notation
dice notation found in most text compatable widgets can be rolled. dice notation should be between brackets (). also dice variables can be created with `/\w[\w\d]*=(\+|\-)?\d+/` patten. for exsample str1=+3 is valid. variables can be used in dice notation with the # prefix eg (1d20+#str1) is valid. dice variables included with dice widgets will be added to the total.

## dice widgets
dice can be draged on from the botom bar menu. using the context menu dice button you can roll them. their style is randomised on creation as well as slight bius twards rolls making each dice uneque. 

## selection
you can roll multiple dice by selecting multiple rollable widgets and using the context menu dice.
