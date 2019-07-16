# Problem Statement:

You are walking up the steps of the Empire State Building. You start at step 0. At every step, you roll a dice, then based on the outcome, you walk up 1 step if you get (1/2) or come down one step if you get (3/4/5). If you get 6, you have another chance to throw the dice and the next random roll will be the number of steps you will be walking UP. But you are clumsy too. There's a 0.01% chance that you will fall and start back at Step 0. The rolling of dice happens a hundred times. The bet is that you will reach the step 60.
Here, we will generate random walks based on random rolls of dice. For now, we will be stimulating 500 random walks and then take the final step reached and use the mean() function of the numpy package to compute the probabilty of reaching the 60th step