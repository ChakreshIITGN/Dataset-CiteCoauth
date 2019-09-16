# Dataset-CiteCoauth
Edge list data for all the graphs used in our recent project

Papers are represented by their Paper Id's as in the APS dataset
Authors are represented by their Unique Id's for ex - An author "Chakresh Singh" would have an ID as "w2d4" etc. 
These ID's are consistent and were given after naming disambiguation.

There are 3 Folder in the directory. 
1. bipartite_graphs : Links are between papers and their authors - this would be the interlayer connections

2. citation_graphs : Links are between papers. This would be a directed network. 

3. Coauth_graphs : Links are between authors. Edgeweights are calculated using Newman Projection method for the bipartite graphs. 

## NOTE

1. All the graphs are constructed cumulatively
2. ' ' separator
