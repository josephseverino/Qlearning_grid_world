# Qlearning_grid_world

<span style="font-family:Papyrus"> The Q Learning algorithm is so far the most upowerful algorithm to-date being used to solve complex Monte carlo Processes. Similiar to Monte Carlo Prediction and Temporal Difference, Q learning uses the state-action space to estimate the values and update the Q function (value function). The true difference comes with the ability for Q Learning to look-ahead to future state-action spaces and determine the best action for the given policy for all possible state-actions. One importatnt thing to notice is how much information the Q value will contain in a given enviroment. Since Q learning requires caluculating all possibilities of future states-actions, this algorithm has the potential to exhaust your memory pretty quickly in a large enviroment. Thus, they have developed Deep Q Learning to solve this problem. Basically, they use a Deep Nueral Net to apoximate the Q function and call it a day. This technique was used by Google's DeepMind to win against a human in the game Go. For this experiemnt, I will play with different values of the discount rate and learning rate to see how it changes the Q learning algorithm. 
</span>


<span style="font-family:Papyrus"> 
</span>


<p align="center">
  <img src="qlearninggraph.png" )
</p>
