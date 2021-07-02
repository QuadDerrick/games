# games
phantasia  -  a game from the freebsd-games package made by Ted E. @ AT&T in 1986.
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
If you want to do it the manual way, download bsd-games , configure it up for only compiling phantasia, config ALL prefix options for phantasia's internal files, compile it with clang in termux. Termux also has some prefix arrangments to be made before you can start compiling stuff, google it or ask in termux irc channel, they are good helpers =)

Enjoy.
