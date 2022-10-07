# Description of non-java files used

AdjacencyMatrix.txt - Stores the Adjacency Matrix of the graph
World.txt - Stores the world representation of the graph, which is all 
            paths read from the map, and respective distances, Barriers     
            and Security Levels.
RankedRoutes.txt - Stores the routes ranked in ascending order according to
                    distances, after reading the journey file.
SerializedGraph.txt - Stores the serialized graph object for later use.



# How to Run the program?

NOTE: Only integer values are accepted as inputs to menu choices. String values are accepted
as inputs when asked for filenames, and for node & edge operation inputs.

First user should 1 to load an input file. User gets 2 options: either to load from a pre-saved 
serialized file or to read a given map file.

Parameter tweaks: User is required to enter a scalar factor and the distances of all edges in graph
are either multiplied or divided according to user's input.

As journey details, user is only required to enter the name of the journey file to read.

User is always given the option to save to a txt file, when selecting display graph, display world, 
and display routes options.

When saving the network, the graph object in use is serialized and stored in 'SerializedGraph.txt'.