# VK-social-graph

A small VK application written on Python that generates the graph (network) of friends. Sample output is provided below (networkx is used to draw the graph):

![Alt text](Graph.png?raw=true)

There is an option to display user names along the vertices, but the figure becomes a mess once there are more than ~200 friends. 

The instructions are provided in the comments in the notebook.

Note: only user's friends' names and connections between them are included in the graph, but the actual user is not there. This is due to abundance of edges that include the user -- without them it is easier to observe "clusters" of friends.
