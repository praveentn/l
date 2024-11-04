# l
Typical learning:
- Input data [(x1,x2,x3),(y1)]
1- Initialize weights
2- Activation
3- Compute loss
4- Change weights
- ... back to step 2

Proposed learning:
- Input data [(x1,x2,x3),(y1)]
1- Initialize weights
2- Activation
3- Find best matched input //set some threshold
4- Closer the match -> BETTER
5- Go to step 2

Thinking thinking!

Proposed learning2:
- Input data [(x1,x2,x3),(y1)]
1- Group sets of inputs with same outputs
2- Initialize weights
3- Activation
4- Avg. weights of similar outputs
5- Use these weights -> step 3
