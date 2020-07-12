# Branching process descriptions of information cascades on Twitter

The files in this repo were used in the analysis of _Branching process descriptions of information cascades on Twitter_. An arXiv preprint can be found [here]().

## File descriptions

The file `full_data_Marref_github.csv` contains all trees from the Marref dataset.

The `file young_data_Marref_github.csv` contains the filtered set of trees from the Marref dataset, where the trees selected have their "birth" time (i.e., the timestamp of the seed node) occurring in the first half of the time window for data collection.

The file `full_data_URLs_github.csv` contains all trees from the URLs dataset.

The file `young_data_URLs_github.csv` contains the filtered set of trees from the URLs dataset, where the trees selected have their "birth" time (i.e., the timestamp of the seed node) occurring in the first half of the time window for data collection.

## File structure

Each file contains 4 columns, with each row corresponding to one node in a tree. 
* Column 1 contains a node index for a child node (i.e., a retweeting event).
* Column 2 contains the corresponding index for the parent node (i.e., the event that is rewteeted).
* Column 3 contains the tree identifier number.
* Column 4 contains the generation number of the node.

The seed node of each tree is labelled as node 1, and nodes in subsequent generations are labelled as nodes 2, 3, etc. 

**Timestamps for tweets are not included here, to ensure anonymity.**
