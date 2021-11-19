---
title: Monte-Carlo Snake
date: 2020-05-07T13:00:00.000Z
draft: false
featured: false
tags:
  - "#Snake#ReinforcementLearning#MonteCarlo"
external_link: https://github.com/eliavmor-tau/SnakeGame
links: []
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
---
A simple reinforcement learning (snake) game that I wrote for fun while exploring RL during my Master. The learning algorithm of the snake is based on Monte-Carlo using every visit update. More details can be found in the code!

The project is composed of two main scripts:

* scripts/snake.py - Contains the snake logic (Monte-carlo, Q-learning, train/test loop). In order to train and test your algorithm please change the relevant parameters under the **main** section.
* scripts/SnakeGame.py - The actual snake game - (based on OpenAI Gym API <https://gym.openai.com/envs/#classic_control>).

Feel free to add you own algorithm and test it using the SnakeGame class in SnakeGame.py! 

Enjoy!

[GitHub repository](https://github.com/eliavmor-tau/SnakeGame)