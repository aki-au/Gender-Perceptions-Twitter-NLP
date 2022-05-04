Some datasets

1. Final dataset that contains tweets information. user information, as well as M3 inferred demographic information (age, gender, is-organisation)
https://drive.google.com/file/d/1Ty2VvcnzpvQd7SawIHWS2o43Qtlcjc0z/view?usp=sharing

2. Previous dataset with Bert embedding, much larger
https://drive.google.com/file/d/1-5iq0lgA6VRYlNlPXu4tca9jqGcTwcv5/view?usp=sharing

3. Cluster Labels, 3 clusters (using Bert embedding)
https://drive.google.com/file/d/1t3getmzKdb8_cF44lnlZn5Ah-cjGQCEr/view?usp=sharing

4. Matched a state label for each tweet using their twitter geo-id.
Surprisingly, we couldn't get the state label from twitter api directly but can get a geo-id for each tweet.
Each geo-id corresponds to a location, while it can be either a point or an area. 
For areas, GIS techniques are used to find out the "centers" of the areas, and then geo-join is applied with the states shape files to determine what states do the centers belong to.
https://drive.google.com/file/d/1pG3r9TeNVsIeh8fp4PF-WtHT99SriN3_/view?usp=sharing
