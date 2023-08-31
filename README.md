# UEFA Champions League Draw Simulator

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JanVanHaaren/champions-league-draw-simulator/blob/main/champions-league-group-stage-2324.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JanVanHaaren/champions-league-draw-simulator/blob/main/champions-league-group-stage-2223.ipynb)

This repository contains [Jupyter Notebook](https://jupyter.org) files that simulate the group stage draw procedure for the 2023/2024 UEFA Champions League and the 2022/2023 UEFA Champions League.

## Description

The notebooks leverage a simple constraint solver to decide on the possible groups that each club can be drawn into.
1. Clubs from the same association need to be drawn into different groups;  
2. Clubs that are paired based on TV audiences need to play on different days;
3. Clubs from given associations need to be drawn into different groups (e.g., Ukraine and Belarus).

Initially, I tried to model the entire draw procedure as one constraint satisfaction problem. However, I struggled to find an appropriate representation that allowed me to break the symmetries and to efficiently obtain all possible solutions to the problem.

If you spot any mistakes or have suggestions to improve the approach, then please [get in touch](https://twitter.com/JanVanHaaren) with me.

## References

### UEFA Champions League 2023/2024
* [Group stage draw pots confirmation](https://www.uefa.com/uefachampionsleague/news/0284-18dd7960fa09-4e1923dabdbf-1000--champions-league-group-stage-draw-pots-confirmed/)
* [Group stage draw](https://www.uefa.com/uefachampionsleague/draws/2023/2001775/)
* [Regulations](https://kassiesa.net/uefa/files/2023-24-uefa-cl-rules.pdf)

### UEFA Champions League 2022/2023
* [Group stage draw pots confirmation](https://www.uefa.com/uefachampionsleague/news/0278-15f3603078f7-909c4310d18c-1000--champions-league-group-stage-draw-pots-confirmed/)
* [Group stage draw](https://www.uefa.com/uefachampionsleague/draws/2023/2001673/)
* [Regulations](https://kassiesa.net/uefa/files/2022-23-uefa-cl-rules.pdf)