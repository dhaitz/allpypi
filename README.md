# graph-layout-computation

This repository just takes an data input file (a csv file) and computes layout of the graph.

Originally from https://github.com/anvaka/allpypi.

## How to generate graph?

##### 1. Clone repository

    git clone https://github.com/anvaka/allpypi
    cd allpypi
    npm install


#####2. Add Data
Add file in `data/links.csv`. Should contain links as comma-separated entries. 
Nodes without links should have a ` null` (note the preceding whitespace).

Example:

	node1,node2
	node3,node10
	node4, null

Apart from `links.csv`, there should be no other files in the `data/` subfolder.


##### 3. Compute Graph
Now you can compute the layout:

    node index.js


Once the layout is computed, you can visualize it with `anvaka/pm` visualization (see
[README.md](https://github.com/anvaka/pm) for details)

## License

MIT
