# Visualizing a Large Dataset
Visualizing a larget dataset for the Marvel Comic-book Universe. 
- The graphs in this project were made using using Gephi.
- This project aimed to analyse the most popular character's in the Marvel Comic-book Universe.
- This coursework scored 92/100.
- A summarised Network Analysis can be found at : ./Marvel_Dataset_Visualization_Poster.pdf
- A detailed analysis and comparison to a random graph can be found at: ./Report_comparison_to_a_random_graph

# Overall Proposal and Dataset:
The Marvel comic book universe dataset obtained contains 6421 nodes where each node represents a character in Marvel’s entire comic book universe which is made up of multiple comic book franchises. The graph consists of 167112 edges where each edge represents whether 2 characters have appeared in the same comic book together. The largest yellow node represents Spiderman and the yellow cluster represents Spiderman’s comic book franchise. Similarly the blue cluster represents the X-men franchise and the 4 orange nodes on the right represents the Fantastic Four franchise and so on. 

# Algorithm Information and The Problem to be Solved: 
Given Marvel wants to create a new comic book franchise including the top 5 popular characters in their entire comic book universe. I used the K-Means clustering algorithm to divide the data into clusters to detect communities and then used different colours to represent each community. I then calculated the betweeness centralities of each node and made the nodes with higher betweeness centralities larger to easily identify the most popular characters/nodes. From the graph I found the following characters amongst the most popular: Spiderman, Captain America, Ironman, Scarlet Witch, Thor and the members of the Fantastic Four franchise. 


Dataset: https://www.kaggle.com/csanhueza/the-marvel-universe-social-network?select=hero-network.csv
