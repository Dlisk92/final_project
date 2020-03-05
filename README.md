# final_project

The purpose of this project is to create a profitable betting model for tennis matches.
As it stands currently this is mainly at a proof of concept stage.

## features

Currently the features are very naive and consist entirely of historical stats for each player.
The AUC of the model is currently .65 in total, but for the probabilities I am concerned with the AUC is .77

## odds

Betting is not a game completely concerned with accuracy as odds play the biggest role of profitiability.
At a .90 accurary many bets would have almost no upside in comparison to the risk. 
This is the true problem predictions vs odds not just pure predictions.

## conculsion

For a problem like this an extremely accuracate model presents its own problems. 
As historical betting odds are hard to locate readily it is hard to account for upside vs downside potential. 
The solution to this appears to be to focus on a models less sure predictions which tend to have good odds as odds are determined by sports books moodels.
