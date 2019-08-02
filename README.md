# Project for CS

For my project for CS 2.2 I will be utilizing the RIOT GAMES API to create a graph based off the 144 characters available in the game. 

The graph will be built based on the different categories that the champions are sorted into, champions that are related will be neighbors to others that are related. I then want to then recommend the path that players should take when wanting to learn a new champion. For example if a player plays the champion Jhin who is an ability based ranged slayer champion and wants to learn to play Irelia an ability based melee bruiser my project would recommend to the player, using a shortest path algorithm, what champs they should learn before jumping to their target champion. In this case a Jhin player might be recommended to learn Lucian and Pantheon before learning Irelia. The more different the champions the longer the path. I also want to give players reccommened champion data using the champions they already play uby finding cliques within the graph. If 140 champions is too large of a data set, I will use 30 instead 
