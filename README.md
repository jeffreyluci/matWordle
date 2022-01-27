# matWordle
MATLAB implementation of the popular online game Wordle.

MATWORDLE - Independent MATLAB implementation of the popular online game Wordle, written by Josh Wardle. The original game is available at the following URL:

https://www.powerlanguage.co.uk/wordle/

USAGE: matWordle

Unlike the online version of this game, it is possible to play it as many times as you like. The code reads the file words.txt for a list of possible words that you can customize as you like. But, keep in mind that it uses the same list of words to validate guesses. So, if you customize that file, adding words to the original is the recommended course. The default distribution of words.txt is simply the contents of the standard Linux spellcheck dictionary with all proper nouns and words with special characters removed.

If you want to play with a friend, you can share a random number and use it as the sole argument to the function call.

Example: matWordle(265973)

As long as you each use the same random number, the same word will be chosen for each player. The random number must be a non-negative integer (uint class) on the computer you use. For most 64-bit systems, that is anything from 0 to 1.8447e+19.

Future development: 1) In the current version, the game only works in easy mode. As with the original Wordle, this means that all five letter guesses that are real words are acceptable. In the very near future, the hard mode will be an option, wherein any revealed hints must be used in subsequent guesses. 2) It will be possible to supply a secind list of words that can be drawn upon for random words to allow themed word lists, while maintaining words.txt for guess validation. 3) The full source code will be released when both 1 and 2 are complete.

VERSION: 20220125 - Initial release

Please report bugs at: https://github.com/jeffreyluci/matWordle
