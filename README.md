# Wumpus World Exploration

Create a 2-wheeled agent to explore the Wumpus World on a physical grid.

## Prerequisites
Ensure you have [GCC](https://gcc.gnu.org/) and [MiniSat](http://minisat.se/) installed. On macOS, you can use `brew` to install them:
```
bash: brew install gcc minisat
```


### Usage:

1. **Manual Control of the Agent**: 
```
python wumpus.py
```

2. **Manual Control with a Knowledge Base**:
```
python wumpus.py -k
```

3. **HybridWumpusAgent (HWA)**:
```
python wumpus.py -y
```





# Example Outcome: Current Wumpus Environment
Scores: <HybridWumpusAgent>=983
  0   1   2   3   4   5    time_step=17
|---|---|---|---|---|---|
| # | # | # | # | # | # | 5
|---|---|---|---|---|---|
| # |   |   |   |   | # | 4
|---|---|---|---|---|---|
| # | W |   | P |   | # | 3
|---|---|---|---|---|---|
| # |   |   |   |   | # | 2
|---|---|---|---|---|---|
| # | < |   | P |   | # | 1
|---|---|---|---|---|---|
| # | # | # | # | # | # | 0
|---|---|---|---|---|---|

DONE.
number_of_clauses_over_epochs: [778, 1169, 1669, 2023, 2314, 2668, 3059, 3559, 4168, 4668, 5168, 5668, 6277, 6777, 7105, 7459, 7750]
belief_loc_query_times: [0.3430659770965576, 0.7054259777069092, 0.851161003112793, 1.0713450908660889, 1.1833479404449463, 1.285254955291748, 1.4193611145019531, 1.557939052581787, 1.7730047702789307, 2.062282085418701, 2.279850959777832, 2.4706509113311768, 2.6951887607574463, 2.970817804336548, 3.1847071647644043, 3.300899028778076, 3.425663948059082]
Final Scores: <HybridWumpusAgent>=983


