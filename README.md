# The Monty Hall Problem
<p align="center">
<img width="460" height="300" src="https://user-images.githubusercontent.com/56449109/217280123-14e07152-af6e-4ed9-844f-8480a7b6525d.png">
<br>
<b><i> "It’s a famous paradox that has a solution that is so absurd, most people refuse to believe it’s true."</i></b><br>
</p> 
Suppose you’re on a game show, and you’re given the choice of three doors:<br> 
Behind one door is a car; behind the others, goats. You pick a door, say No. 1, and the host, who knows what’s behind the doors,
opens another door, say No. 3, which has a goat. He then says to you, “Do you want to pick door No. 2?” Is it to your advantage to switch your choice?
<i>(From Parade magazine’s Ask Marilyn column)</i> <br>
Or in a more general way, instead of just 3 doors imagine you're given N doors and the host opens N-2 doors after you make your choice, 
leaving you with the choice that you made initially and just one other. Now, if you/re asked to stay on your choice or switch what will you do? <br>
Do you stay or switch? Which will be the better option? <br>
<i>You should always switch. But why?</i> <br>


## Objective
In this project I simulate the problem and experimentally show how this "counter-intuitive" solution is actually correct. I also tackle some of the other 
questions that arise from the same problem, namely -
1. What will happen if we have N doors and the host opens N-2 doors after we have made our initial choice? How often will we win if we switch? (i.e. what is the probability of winning)
2. What will happen if we have a constant number of doors, say 100, and k (less than 100) doors are opened? How often will we win if we switch? (i.e. what is the probability of winning)

## Result

The theoretical explanation of the correctness
of these results is explained in this <a href="https://www.linkedin.com/pulse/monty-hall-problem-aarat-satsangi/">article</a> authored by me.

<p align="center">
<img width="300" height="300" src="https://user-images.githubusercontent.com/56449109/217319263-d3033a4a-9c1f-479b-b00d-a436c951ebdd.png">  <img width="300" height="300" src="https://user-images.githubusercontent.com/56449109/217319121-a18c104f-726d-41cd-a58c-6fb59836588e.png"> <br>
</p>
<ul>
  <li>As the number of doors N increase the probability of winning also increases. And when N = &infin; the winning probability becomes equal to 1.</li>
  <li>As the number of doors opened k increase the probability of winning also increases but slowly. And when k = 98; the winning probability becomes equal to 0.99.</li>
</ul>
