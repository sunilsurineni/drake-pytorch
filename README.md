# NNSystem files
 - packaged cpp - cpp version of NNSystem
 - packaged python - python version of NNSystem
 
 


# Layout of other files
  - cpp
    - torchlib\_cpu - a snapshot of the torch compile work I had to do to make a shared lib I could link to drake
    - drake+pytorch - a drake shambala copy I'm using to compile custom drake c++ code with torch 
  - python
    - nn\_system - python code for my neural network drake system, and related code
    - playgrounds - lot of jupyter notebooks that have been solely for experimentation
    - traj - python code useful for setting up trajectories
    - diagrams - diagrams, perf reports, etc... that I've cooked up
    - multiple\_traj\_opt.py - a big file where I've put a lot of my logic for setting up simulataneous, constrained optimization problems*
    - <*all\_other\_files*> - my scratchpad of recent work :p
