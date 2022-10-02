# Quandle
A quantum variant of wordle.

This is the project submitted to [Quantum Game Jam 2022](https://itch.io/jam/quantum-game-jam-2022/rate/1707734). During Quantum Games Hackathon, a few more features were added: "quantum" anagrams & redesigned UI. 

#Credits
Game design & coding & UI & background music: Raycosine.
The game is also uploaded to my github page: http://raycosine.github.io/Quandle.html and on itch.io: https://raycosine.itch.io/quandle. (mobile friendly)
Use SOWPODS as the word list (not all words are English words!!) 
Fonts (public domain) & sound effects (under CC0 license) are from the Internet. Detailed info can be found on the index page.

# How to play

You'll immediately know how to play quandle if you already know some basic quantum knowledge and wordle! Watch the [Game trailer](https://www.youtube.com/watch?v=q_zJioewPww) on YouTube.

## Daily & Practice
Consider |a>, ..., |z> as the basis "single-character" states. An n-letter "word state" looks like |qubit>, and any state on superposition can be written in the same way as quantum states: |qubit>+|qudit>, |qu>(|b>+|d>)|it>, ...For simplicity, the coefficients are not considered in this game.

The goal is to find the classical description of an n-letter word state on the superposition of k unknown words. For the example above, we need to find out the two words 'qubit' and 'qudit'.

If you choose 'Daily', the word state for each day is fixed.

## Anagram
You are now given all the superpositions that are anagrams: For example, 'propitiousness' and 'superpositions'. But the amplitudes are unknown. No worries, they'll be unnormalized, bounded integers. You can now modify the amplitudes to find a state close enough!

## Share your result
Whether you win the game or not, you can click the share button to place your result in clipboard and get a image as well.

## Comments
Leave comments in the Github thread!
