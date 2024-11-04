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


same neural network forward pass but instead of backprop, implement this

make predictions by initializing weights randomly for the first time
group batches (by grouping common outputs and inputs) - use decision tree to group into batches
get the avg. weights for each group (or tree)
use the avg. weights for next iteration
optimize loss as usual
With this I should be able to train a neural network (give a proper name).

