## How To Paste
My all in one guide that help you make your first working paste

> Learning C++ basics 
- It is more than essential that you know basic c++. It might not make sense at first but as you paste and use the things you learn it will make sense.
- start by watching a basic course https://www.youtube.com/watch?v=vLnPwxZdW4Y
- everyday watch this playlist and try to learn something new https://www.youtube.com/watch?v=18c3MTX0PK0&list=PLlrATfBNZ98dudnM48yfGUldqGD0S4FFb
- if you prefer to read instead of watch then you can go to learncpp.com
- learn pointers!

> Drivers?
- All of the information your cheat is taking in is done by reading memory from fortnite
- Fortnite has a kernel level anti cheat which means you wont be able to read and write from ring 3 (ring 3 is where your cheat is) https://cdn.discordapp.com/attachments/966163192663396453/977177591276523540/unknown.png
- to read and write you will need to do it from kernel, so u need a kernel driver 
- your driver must also be albe to communicate with your cheat so the cheat can recive the information that the driver has read. This is known as your communication method and the most effective way for the anti cheat to detect your driver. But it is also only one of the many ways they can detect your driver. One method of communication that you have probaly heard before is Iotcl. Iotcl is actaully agood communication method because most legit(drivers that arent used by cheats) are using iotcl. 
- drivers are used by externals to read and write memory, drivers are also used by internals because injectors use drivers. You do not need a driver to read and write for internals, you can just use pointers. 
- Other features your driver will need is getting the base address and proccess id. 

> The Cheat?
- I will be teaching you guys about externals since they are basic to understand and paste.
- It is important that you know a tad bit of unreal engine. You need to know the difference between Actor, Pawn, And Player and how the camera works. You can watch this short video to learn the basics of unreal engine: https://www.youtube.com/watch?v=QJpfLkEsoek
- Your cheat will need 4 things. You will first need a renderer to draw, I think the best one and most common one is imgui. Second you will need an overlay, this will be a transparent window that goes over fortnite that you can draw on. The third thing you need is an actorloop, this will be a for loop that goes through all of the players and draws boxes around them and does the aimbot. The forth thing you need is an cache, this will make an vector of players and filter out the players from the actors that your actorloop can loop through. 

> How To Make It Ud?
- Dont go chasing water falls
- Never buy any sources or drivers, ik your not going to listen to me and your going to have to learn the hard way.
