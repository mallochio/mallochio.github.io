---
layout: page
title: Reinforcement Learning Across Timescales
description: Creating agents that are agnostic to changes in their operating frequency.
img: /assets/img/rl1.png
importance: 1
---

<ins>Abstract</ins>: This project addresses a fundamental problem faced by many reinforcement learning agents. Commonly used reinforcement learning agents can be seen to have deteriorating performances at increasing frequencies, as they are unable to correctly learn the ordering of expected returns for actions that are applied. We call this the disappearing reinforcements problem. Moreover, truly multi-task reinforcement learning is only possible when agents are able to operate across frequencies, as different platforms operate at different frequencies. Most algorithms from control theory working on similar tasks, on the other hand, show improved performances when their operating frequencies are increased. This suggests that addressing disappearing reinforcements should enable reinforcement learning agents to have improved performance and generalization ability across timescales and tasks. In this project, we show that disappearing reinforcements is an effect seen independent of the function approximator used in reinforcement learning, and is instead of a more fundamental nature. We explore both theoretically and empirically the relationship between agents and their performances at increasing frequencies. We show that two specific types of agents from literature address the problem, and we benchmark the agents' performances with novel benchmarking measures inspired from control theory. Finally, we create a novel agent we call the dueling advantage learner, by combining both approaches from the state-of-the-art. We then benchmark the different agents across frequencies and tasks, and our agent is seen to outperform each of the individual approaches on the majority of the tasks.

<iframe src="http://docs.google.com/gview?url=http://example.com/mypdf.pdf&embedded=true" style="width:718px; height:700px;" frameborder="0"></iframe>
