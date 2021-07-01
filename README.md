# games
phantasia  -  a game from the freebsd-games package made by Ted E. @ AT&T in 1986.
ported to andorid with clang in termux in 2021. 

Install :

1 download and install termux with a writeable home directory configured.

2 mkdir p

3 cd p

4 wget https://github.com/QuadDerrick/games/blob/main/phantasia.zip?raw=true

5 unzip phantasia.zip\?raw\=true (type unzip p and push tab to autocomplete filename if needed)

6 chmod a+x the phantasia file

7 ./phantasia

note, use the directory name "p" as instructed, the binary is compiled to run under this directory.
If you want to do it the manual way, download bsd-games , configure it with only compiling phantasia, 99 prefix options for phantasia's internal files, compile it with clang in termux. Termux also has some prefix arrangments to be made before you can start compiling stuff, google it or ask in termux irc channel, they are good helpers =)

Enjoy.
