# Jogo da Velha (Tic-tac-toe)

Tic-tac-toe is a quite common game in Brazil. I cannot count how many hours I have spent playing it with my grandma during my childhood. At that time, I was playing it was more like doing semi-random moves rather than thinking about possibilities and how to win.

Recently I was talking to a friend who is doing a beginners course on programming, and he was upset that his professor asked the students to implement a bot to play the game. One of the requirements to get full score on the assignment is that the bot should never lose (it does not necessarely have to win).

Since they are freshman at the university, using AI-based approaches like minMax were out of the question.

I started fooling around with some JS code to make it run on the browser and after some hours, I had [my online version of it](https://israelzinc.github.io/jogovelha).

However it was not working as planned, and it took me 5 iterations of fixing bugs and discussing logic with my friend to get it right.

I believe this professor was out of his mind when he asked the freshmen to do it (forgot to mention that the freshmen was also forbidden of using `for` loops because God knows why...).

<!-- Basically my algorithm goes:

1. If bot can win, do it.
2. If opponent will win, blick it.
3. If center is available, play it
4. If corner is available, play it
5. Play in one of the space in between corners -->