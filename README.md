
# brr 

## the perfunctory prose proliferator 

programmery provided by the passionately proficient proprietor of [viewsourcecode.org](https://viewsourcecode.org/snaptoken/kilo/01.setup.html) 

amateurishly adapted and apprehensively altered by Maxwell Letterlock (max at letterlock dot eu) 

brr is a text editor that adapts the permanency of writing by hand or on a typewriter in order to allow the user to produce text with as few edits as neccesary, hopefully curbing the urge to constantly edit whatever they have written down.

it consists of an (intentionally) minimal featureset: 

- it cannot edit saved files except to add to them
- it cannot remove text past what it itself has added
- after five seconds of no input, it will autosave the file upon the next keypress 

brr was adapted from the code of [kilo](https://github.com/antirez/kilo) using the guide linked above. 

it is my first ever project, i have never programmed a thing in my life, let alone using c, any weirdness in the code is probably because of that. 

feel free to modify and change it in any way, bring up issues and suggest changes or clean up my code with pull requests. 

if you do tidy something and submit a pull, i would very much appreciate it if you would explain your thought process, so i can learn! 

### compiling 

brr *should'nt* have any dependencies and *should* compile on any system without problems, but i have no clue what i'm doing, so... no promises. :^) 

i don't currently have any plans to package brr in any way, because, well, i haven't researched how to yet.

### todo 

- add line numbers in margins
- implement ability to change settings in a config file 

#### possibly 

- only allow brr to open named files or prompt for filename on init
- work on single line typewriter style (scroll editor when out of bounds of one line instead of entire screen)
