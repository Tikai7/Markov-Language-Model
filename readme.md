# ***Markob Language Model***


- The Goal : Training simple markov model on a french dataset
- Step 1 : The goal is to estimate $Pi$ and $A$ by maximum of likelihood
- Step 2 : Generate sequence by sampling tokens by using $Pi$ and $A$

# ***Results***
- Bad results because we are simply looking at the previous token to generate the next one, so sentence are kinda random
```
User :  comment çava
AI :  commentary - bonjours le nom de contre de l’est trègès sourire le bien à vrais relès on avoir lieu en déçais au maximum tout le fait un peut-censure, chez d’une corrigid=newsyndre d'aille dont il vont à la chair. Or, là citoyenne. Pourqu’indre ici bien
```
