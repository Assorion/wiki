+++
title = "Philosophy"
+++

Assorion has a rather unique philosophy, compared to most other FNF engines. 
Assorion has always been about minimalism, rather than bloat.

Features such as a mods folder, cutscene support, DiscordRPC, in-built editors, etc are 
features that add complexity to the source code, and would slow Assorion down. We wish to work 
on an engine where the focus is on modding the **source code**, and where modding the source 
code is easy without having to constantly fight the engine to add features.

If a modder desires to add said features then there should be no code to obfuscate how the 
engine works. As such, adding unique gimmicks at first can be very difficult; Over time after 
gaining an understanding of Assorion, adding gimmicks will be very easy.

# Principles

Here are the principles of Assorion's management that has to be outlined:

#### 1. Assorion is small at it's core

Joke assets are fun! And so are easter eggs!

However there should be no assets that are not required, and any modder should remove assets that they themselves are not using. 
Most modders will leave base assets in (though that should never be done!) and those can take up quite a bit of storage space, 
thus the only assets are the ones required for the game to function, and for the demo and tutorial songs, everything else is cut.

Easter eggs are also not going to be accepted in to Assorion, as adding code or assets for one is not very efficient, as a modder 
will either have to remove all of the code for an easter egg or will have to just keep it in. Ultimately it is not worth it.

#### 2. Assorion will keep clean code

Let's break the third-person barrier, I (Rapid / Antivirus) believe in "Firmcoding". Where the logic is entirely coded in the 
executable of the game, but still easy to maintain / mod. 

It's very important to make the code as clean and as easy to work on as possible. If a modder wants to add a feature, they should 
not dig through thousands of lines of code in order to add a simple feature. It may take a bit for said modder to add one, however 
it will be far easier than having to comb through other parts of code (that may or may not be related) just to make it work.

Another important part of the code is "maturity". The base game has a lot of cursing and/or not very well named variables and functions. 
Assorion has made an effort to not only make the code easier to read, but to be able to guess what a variable or function is used for 
based on it's name. 

Assorion does not rely on any C / C++ code for the engine, and only uses Flixel / Lime / OpenFL dependencies. This means that Assorion 
has a low chance of memory leaking (if it does that's due to a Lime or OpenFL bug). This also can allow Assorion to be portable without 
too much compiler logic.

#### 3. Assorion is not familiar

Assorion does not care for the compatibility (or familiarity) of the base game or other engines.

Truth is, most of the original FNF code is not very dynamic or flexable. Assorion's code is far different from the base game's, therefore, 
getting familiar with the code will take some time. The engine handles charts, characters, notes, health / scoring, etc differently. Though 
the new implementation has the future in mind; You could easily do a fair bit more than what was originally allowed.

This does unfortunatly have the side effect of being difficult to port mods to, as Assorion is not a drop-in replacement. 

# Finishing Statement

If the person reading this disagrees with any of the points made, that is totally fine!

Assorion is a different engine, with different goals. If the person reading this feels that this engine would be to difficult to work on, 
then do not retrofit Assorion engine to your use case, as it will not work!

> "Assorion Engine is designed for minimalists, not Windows users"  - Rapid / Antivirus