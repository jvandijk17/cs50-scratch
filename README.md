
# CYBERPUNK

Project Title: CYBERPUNK

# About the Code Smells:
I've tried to make the project cleaner by using a refactor via a function that could parse an entire history string into an array, eliminating repeated blocks of code. However, parsing the string in this way caused the game to take 30 minutes to load due to Scratch's limited features. I've also tried importing the string from a JSON or an external service like a REST API, but that didn't work either. While iterating the string and detecting each character was another option, it would have taken too long (about 5000 characters) due to Scratch's lack of features like the substr, trim, search, and indexOf functions available in most modern languages. Despite the repeated blocks of code and less than ideal logic, I've decided to keep it that way to prioritize game performance and user experience.

# Third-Party Library Usage:
I have used a third party library, created by Will_Wam, to print text on the scratch screen. Needing more styles than the Say block offered to create a more immersive experience, and limited time due to a full-time job as a programmer, I decided to use the library instead of building a text engine from scratch. However, all the logic written around the game was fully coded by me.

Credits:
Will_Wam (TEXT ENGINE LIBRARY AUTHOR): https://scratch.mit.edu/projects/668054871/
