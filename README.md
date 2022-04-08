# Hangman   
Console Ruby game. When you start the game, the computer guesses a random word from [/data/words.txt](https://github.com/Kucherjashka/hangman/commit/3f020f2bc890b379ee763ec02314881fc7aa1af9).

You need to guess the chosen word by entering Russian letters one by one. Guessed letters will be shown above the gallows drawing, hidden letters are displayed with "__". The erroneous letters are shown below the drawing of the gallows. In this case, the letters already entered earlier are not taken into account, the letters "e" and "ё" are considered one letter, as well as the letters "и" - "й". There are 7 errors allowed in the game. Each time you make a mistake, the error counter will increase by 1 and the gallows pattern will change depending on how close you are to losing. If you lose, the hidden word will be shown.


# Language:
- Russian


# System requirements:
- installed Ruby
- MacOS, Linux, WSL


# How to run:
- save file 8ball.rb on your computer.
- open Terminal at directory where you save programm file.
- type: 'ruby 8ball.rb'
- play


# Rules:  
You have to guess the word.   
Enter letters one by one until you win or loose.   
You can make only 7 mistakes.  
Ё == Е, Й == И  
Repeats not considered as a mistake.  


# New word add:  
You can change guessed words.   
Just add or delete words in file [/data/words.txt]
Each word have to be typed with CapsLock.  
Each word have to be typed on new string.  
