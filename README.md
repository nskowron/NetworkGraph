# NetworkGraph

Rendering of (random, possibly infinite) graph of a network, experiments on it's reliability and a simple GUI overview.
---
## Dependencies
### General
- `sudo apt install socat maven default-jdk python3 libgmp-dev`
- cabal - can be installed from here: https://www.haskell.org/ghcup/

### External Libraries
- `pip install numpy networkx` in a venv or globally, then run.sh also needs to be ran from venv
- `cd Generating`
- `cabal build` - just once, where the .cabal file is - automatically downloads dependencies
- java dependencies will be automatically downloaded by maven on the first run