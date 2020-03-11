# Networkx-Centrality
NetworkX is a Python library package used to create, manipulate, and study the structure and functions of a complex networks. There are two part in this study. The first is to create a friendship network between cohort mates at the Flatiron School, The second with a much larger scale is to measure the closeness centrality and betweenness centrality among business entities and users. 
Objectives:
  1. For a small cohort mates network at Flatiron School - Data Science Program
       * Create basic network graphs with networkx
       *  Add nodes and edges to networkx 
       *  Visualize network graphs with networkx
  2. In a larger scale, a yelp review file that contains more than 1 million reviews, we
       * Identify business entities and users
       * Create network graph with networkx
       * Add nodes and edges to networkx
       * Visualize network graph with networkx
       * Construct a dataframe that measure degree centrality, closeness centrality,betweenness centrality,and eigenvector              centrality.
    
 Networkx depicts the relationship between cohort mates at Flatiron School- Data Science Program
    ![](Images/Cohort_Mates_Relationship.png)
 Let's take a look at the first 15 rows and the last 10 rows of the "yelp review) file
    ![](Images/first_15_rows.png)
    ![](Images/last_10_rows.png)
 And now we can graph the relationships among business entities and users based on the strong/weakness of the reviews.
    ![](Images/business_users_relationships.png)
    
  Finally, after much work, we have constructed a dataframe/table that summarizes the closeness and betweenness-centrality.
    ![](Images/Users_closeness_measurements.png) 
  
  ##### Notes:
    * Degree centrality is the number of links incident upon a node (i.e., the number of ties that a node has)
    * The closeness centrality (or closeness) of a node is the average length of the shortest path between the node and all         other nodes in the graph.Thus the more central a node is, the closer it is to all other nodes.
    * Betweenness is a centrality measure of a vertex within a graph. Betweenness centrality quantifies the number of times a       node acts as a bridge along the shortest path between two other nodes. It was introduced as a measure for quantifying         the control of a human on the communication between other humans in a social network.
    * Eigenvector centrality (also called eigencentrality) is a measure of the influence of a node in a network. It assigns         relative scores to all nodes in the network based on the concept that connections to high-scoring nodes contribute more       to the score of the node in question than equal connections to low-scoring nodes.
    
    
