watch & summary 5 points - https://www.youtube.com/watch?v=SmE4OwHztCc&ab_channel=JSConf


Summary
This video is about how does a browser render a website.

1.PARSING

Tokenizer-takes each character anf figures out the tokens.
parse tree-takes the parse tree and converts into dom tree
There are certain situations where the parsing halts in case of script during network latency.Link and style that could halt JS execution.
speculative parsing-will look ahead.
parsing is forgiving in nature and can also be interupted.  

2.RENDER/FRAME TREE

Combines the two object models.
This is the actual thing that tou see on the screen.
It has multiple trees-
RenderObjects,renderstyles,renderlayers,lineboxes

3.LAYOUT

Its a recursive process
Traverse render tree
nodes position and size and layout its children

4.PAINT SETUP
Will take the layed out render trees
Creates layers
Incremental process


