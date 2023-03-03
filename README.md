# Pokemon
## 0\. Read Me
The goal of the Data Analysis performed in the python Notebook is to be able to identify what pokemon types are the best from a statistical point of view, both as attackers and defensers  

Using csv inputs containing pokemons ids and type and a type chart, we will : 
1. Load the Data into dataframes with homogeneous formats  
2. Perform a quick run down of the best / worst Monotypes attackers to define the metrics used after
3. feed the type matrix with every possible combination of types  

Then, we will perform an analysis on all dual and monotype combinations, creating a top for 
1. Best type to attack  
2. Best type(s) to defend  
3. Best STAB to attack  
4. Best movepools of 3 / 4 types to hit the most types

Finally, we will consider that types are not identically distributed among pokemon, and thus :
1. Study the distribution of types (most seen, missing types)
1. Recompute the best attacking types weighted by the type of every available pokemon (until Sword/Shield)

The Data by pokemon has been downloaded from csv files available at https://github.com/veekun/pokedex  
The type_chart has been downloaded from the following github: https://github.com/zonination/pokemon-chart
