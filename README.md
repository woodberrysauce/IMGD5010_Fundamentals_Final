# IMGD5010_Fundamentals_Final

I made a maze. The rules of this game are very simple. Just walk to the end like a normal maze. The difference is that you can see a circle of light around the player. What I want to express is that the player plays the role of this little ball and uses the flashlight to illuminate the surroundings to explore the dark maze. But because your field of vision is very limited, it is difficult to reach the lower right corner directly.

So this is what I wanted to make at the beginning, a "quantum maze". Although the final effect makes me feel a little rudimentary, in the first version I tried to use shaders but it was always unsuccessful and disrupted my other functions. However, you can see that the most important mechanism was still made by me. Every time the player turns off the flashlight, the maze will change. This may help you reach the end or hinder you from reaching the end.

Although it is very rudimentary, this is what I want to express about the quantum maze. Of course, I don't actually understand quantum, and I haven't really studied quantum. So I may have made some mistakes. People who know can tell me where I am wrong. This is just a reference to people's general understanding of the word.


That is to say, the maze regenerates when the flashlight is turned off, either due to time limits or player input. Although I haven't added a countdown or automatic flashlight off, the position of goal does not change when the flashlight is turned off. So now this mechanic just makes the game easier

“Quantum Maze” means the maze go into uncertainty when not being observed, echoing ideas from quantum measurement theory, so I feel it will be interesting.

After adding more things, This mechanic may introduces both aesthetic and a gameplay complexity. Players must make progress within a short window of visibility, and guess the unseen structure of the maze. The prototype includes basic movement, visibility masking, and trying to add random maze structure generation.
