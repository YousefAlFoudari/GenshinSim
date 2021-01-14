# GenshinSim
Ongoing Genshin Impact wish simulator.

Genshin Impact is a free-to-play gacha game developed by miHoYo. From Wikipedia: "Gacha games are video games that implement the gacha mechanic. This is somewhat similar to loot boxes, inducing players to spend in-game currency to receive a random virtual item. Most of these games are free-to-play mobile games, where the gacha serves as an incentive to spend real-world money."

In Genshin Impact, this gacha system is known as "wishing". The player pays a certain amount of virtual currency (Primogems) to obtain a certain amount of random items until the player gets that they want. My simulator aims to accurately replicate that system and to provide the user comprehensive statistical feedback. This project is implemented in Python using Jupyter Notebook.




How it works:

- The user is first asked whether or not they are wishing for a specific item. If so, the next question asks for the name and how many of that item the user wants. The program then simulates repeated "wishing" until the desired conditions are met (i.e. the correct number of desired items are obtained).
- If the user does not wish for a particular item, the program queries the user for how many times they would like to wish, and proceeds to simulate that particular amount of wishes. (1 "wish", or "roll", refers to acquiring 1 random item).
- After the simulation is complete, various statistics such as USD spent, Primogems spent, and items acquired may be viewed. The user is then asked if they would like to run the simulator again.


