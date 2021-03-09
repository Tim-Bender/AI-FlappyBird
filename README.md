# AI-FlappyBird

> <h4>This project was made to demonstrate the power of the NEATS neural network when applied to
> simple games such as flappy bird.</h4>
> </br>
> The goal of this project was to achieve a generation of birds which passed the 1000th' pipe,</br>
> and the brilliant NEATS engine destroyed that goal and pushes past 5000, embarrassing any human player.
> </br>
![Ai Flappy Bird](flappybirdai.png?raw=true "Environment Variables")</br>
>
> # Pygame</br>
> In order to implement NEATS on flappy bird, the game itself was first implemented using</br>
> the legendary module, pygame. Running at 30fps, I did my best to replicate the</br>
> physics and feel of the original game. From there it was time to implement our neural netowrk.
>
> # NEATS</br>
> The NEATS neural network was implemented using generational learning.</br>
> Only the best members of each generation are chosen to go on. Birds are rewarded for reaching</br>
> further in the level, and receive a huge boost to their fitness when they pass through a pipe.</br>
> </br>
> </br>
> ![Ai Flappy Bird](flappybirdai2.png?raw=true "Environment Variables")</br>
>
> After several generations, the birds have finally learned to navigate through this simple game,</br>
> and given time these super birds can become near perfect and achieve scores in the thousands.
