# Wumpus World Exploration

Create a 2-wheeled agent to explore the Wumpus World on a physical grid.

## Prerequisites
Ensure you have [GCC](https://gcc.gnu.org/) and [MiniSat](http://minisat.se/) installed. On macOS, you can use `brew` to install them:

```bash
brew install gcc minisat


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



# wumpus-world
Creating a 2 wheeled agent to explore the wumpus world on physical grid.

To run code install gcc and MiniSat using brew.

You can then test the connection to MiniSat by executing the following from the command-line:
python wumpus.py -t


1. For manual control of the agent: python wumpus.py
2. For manual control with a knowledge base: python wumpus.py -k
3. For the HybridWumpusAgent (HWA): python wumpus.py -y

