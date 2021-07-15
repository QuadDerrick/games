# games
phantasia  -  a game from the freebsd-games package made by Edward A. Estes @ AT&T in 1986.
ported to andorid with clang in termux in 2021. 

Install :

1  download and install the termux app

2 open the app and write "termux-setup-storage" to gain writeable space.

3 mkdir p

4 cd p

5 mkdir phantasia

6 cd phantasia

7 wget https://github.com/QuadDerrick/games/blob/main/phantasia.zip?raw=true

8 unzip phantasia.zip\?raw\=true (type unzip p and push tab to autocomplete filename if needed)

9 chmod +x phantasia

10 ./phantasia

Now your figthing orcs , hob goblins , nazguls , smeagol and the dark lord himself occasionally , and many more.
(see monsters file if you are curious. If you are mean enough, you may become a monster yourself)

Notes, use the directory names "p" and "phantasia" as instructed, the binary is compiled to run under these directorys.
"pkg install wget" installs wget, pkg install unzip also is good if your starting from scratch.
If you want to do it the manual way, download bsd-games , configure it up for only compiling phantasia, config ALL prefix options for phantasia's internal files, compile it with clang in termux. Termux also needs some special tweak with configure, 
./configure --prefix=$PREFIX
If configure script exits without errors, run make. If that exits without errors, execute the phantasia binary.
Enjoy.

Short instructions to play the game:
lkjh to move. kl keys move your characterin + direction on y or x line.(try it out, not too complicated=)
you can also use option "1" in normal mode menu to move manually troughout the maps.
0,0 = kings chamber, you need a crown to enter. once you have a crown you can collect free gold there among other things.
many secret places are stored trough out the waste lands. for friendly tips, first shops are at , i think +400,400 800,800 and 1000,1000. maybe its 2000,2000 , not 1600,1600 like you might expect.. reading source code also is ,, somewhat good for figuring out land of names and shop places and, mosters and , all kinds of usefull fun info in the sources , unlike windows games. As always, reading the manual, man page, is also usefull.
