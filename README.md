# CityBlocksJs
City blocks generated in a dumb way

Demo here: https://cgibbs.github.io/CityBlocksJs/

This is a Javascript port of my CityBlocks Python project. All further development of these generation algorithms will be done here, and likely not in the Python repo.

Uses a deque as an A*-style frontier to generate streets outward from the middle of the canvas. It's similar in nature to a tunneling maze generator, but has its own little quirks.
