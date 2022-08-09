# Model-Based RL Multi-Tasking with [ReLAx](https://github.com/nslyubaykin/relax)

__Multi-Tasking concept:__

CEM is a derivative-free optimizer which searches for optimal actions by iteratively generating random action sequences and evaluating them with fitted observation and reward models. 
First action from elite (by total rewards sum) sequence is then executed. 

By replacing rewards given with fitted reward model by some user defined function we can alter RL agent's behavior without the need of retraining any model. Thus, achieving multi-task agent. 

__Default Behavior:__

https://user-images.githubusercontent.com/67604207/183721245-b168d62e-38cf-4878-8edf-82d7910fc7d3.mp4

