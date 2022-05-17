A simple CNN model that recognizes location from a game ELDEN RING by a screenshot.
Currently has 7 locations:  
'Caelid', 'Crumbling Farum Azula', 'Leyndell, Capital of Ash', 'Limgrave', 'Liurnia', 'Mountain of the Giants', 'Round Table Hold'.

Simple sequential CNN with ADAM optimizer.

The data was gathered by me. I recorded a video footage of an in-game character moving around these locations and then split these videos into screenshots with opencv script. Split the data into categories via folders.

The test set consists partially of the data from training/validation sets (randomly selected). The second part is extra screenshots taken by me, deliberately challenging.
The test results and graphs are only shown for these challenging cases.
