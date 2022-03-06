# ANN-to-predict-Match-Winning-Team
This is an ANN (Artificial Neural Network) model which predicts the match winning Team based on the Training data given to it. A multiple layers using Activation functions such as
'linear' and 'relu' is involved in this process along with a number of nodes at each layer. Eight parameters namely 'neutral_venue','team1','team2','toss_winner','toss_decision',
'result','result_margin','eliminator' are used to Train the Network. A Unique ID is assigned for every individual Team. The difference between the predicted value and the Unique ID
of both the Teams involving in a single match is calculated. The one Team's ID which has the less difference with the predicted value is announced(predicted) to be the Winning Team. 
