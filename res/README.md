This folder contains the dataframes of vertices and edges necessary to build for type of graph:

1. __nn__: The graph built with the nearest neighbour approach
2. __unw_dir__: The unweighted graph with no directed link bridge -> crossroads
3. __w_undir__: The weighted graph with link going both ways bridge <-> crossroads
4. __w_dir__: The weighted graph with directed link bridge -> crossroads

For a more detailed description of the networks, and insights on the results obtained check:

Up to now, the _res/_ folder contains the dataframe of vertices and edges needed to reconstruct the graphs used for the Monza application, whose main results can be found in 
> Arosio, Marcello, Luigi Cesarini, and Mario L. V. Martina. 2021. "Assessment of the Disaster Resilience of Complex Systems: The Case of the Flood Resilience of a Densely Populated City" Water 13, no. 20: 2830. [https://doi.org/10.3390/w13202830](https://doi.org/10.3390/w13202830)


The columns for the vertices dataframes are:

**name:** alphanumeric ID, with the abbreviation of the type of vertices (e.g., res_1 stands for first  residential vertices )  
**OBJECTID_:** univocal numerical ID of the vertices  
**Type:** type of vertices depending on the categories identified. (see papers)   
**n:** total number of vertices for the given category  

The columns for the edges dataframes are:

**from:** name of the node where the edge starts.  
**to:** name of the node where the edge ends.   
**Type_link:** type of link depending on the categories of the from-to node. (i.e., Residential -> Industry. Also, see papers).     
**weight:** when applicable, the weight of the given edge. (see papers for the procedure of assignment of the weights.)

