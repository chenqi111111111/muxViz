muxViz
======

The following list reflects the possible improvements of muxNet. I am in debt with Mason A. Porter for some of the points below:

- Input one single file listing the edges list corresponding to each layer

- Assign labels to nodes from external file

- Specify more flags for the choice of the community detection algorithm, as for the layouts

- The number of parameters can be so large that could be good to have an external file where to store all of them

- One should be able to color not just by community but by anything the user wants

- The user should also be able to color things across layers. There will be times when that is desirable (e.g. when the nodes are not all the same in all layers).

- It would be nice to have the code also do this with a 'network of networks' layout

- There are open issues with the native RGL device. This is far beyond the scope of muxViz, but maybe someone could find a way to solve them


To the best of my knowledge:

- Transparency for nodes and edges does not work for the current version of RGL 
- Edge bending does not work for the current version of RGL