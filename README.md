# Manhattan K-Clustering Model
This model groups Manhattan latitude and longitude data points into clusters based upon the most common nearby business venue types. Using this Model, we can identify neighborhoods with similar characteristics. Refer to the [Manhattan K-Clustering Model](https://github.com/derekvogt3/Manhattan-K-Clustering-Model/blob/master/Manhattan%20K-Clustering%20Model%20-%20WeWork.ipynb) for more detail on the model.

# WeWork Location Analysis
Based upon the K-Clustering model developed in the above section, the following map represents all Manhattan WeWork locations grouped by cluster.

![Image of WeWork](https://raw.githubusercontent.com/derekvogt3/Manhattan-K-Clustering-Model/master/Screen%20Shot%202020-03-31%20at%201.17.50%20PM.png)

As seen in the map above, the majority of WeWork locations are grouped together within Cluster \#3 (light blue).

To demonstrate the usefulness of this analysis, I will go through a few scenarios someone could use this information to drive a business decision.

<ins>Scenario 1: WeWork is looking to expand</ins>

In this scenario, you are a part of WeWork's management team looking to expand to a new location. How do you decide which area of Manhattan to expand? Using this model, you can identify a new neighborhood to set up a location. 

The first thing you notice is the majority of locations are grouped as Cluster \# 3 (light blue cluster). As a member of the WeWork management team, you should have financial data for each building. Are the buildings labeled as cluster \#3 more profitable than the other clusters? If so, it make sense to expand to a location near a cluster \#3 datapoint. If not, are there other more profitable locations? Should you look into expanding near those cluster points?

As you can see, you can take this a step further with additional building financial data, but having cluster information can be usefull in identifying potential expansion locations.

<ins>Scenario 2: A competitor is looking to expand</ins>

In this scenario, you are a competitor of WeWork looking to expand. You do not have building level financial data for each WeWork location, but you are going to assume the locations in Cluster \#3 are more profitable than other clusters -- why else would WeWork be so focused on expanding to these areas? However, a new location set too close to a currently established a WeWork may result in over competition. Based on this logic, expanding to a location near Lincoln Center is advisable. It is still within Cluster \#3, but there are no WeWork locations in the area.


As a competitor, you should also have financial data for each of your buildings. You can run this model for any Manhattan address by modifying part 1 above, therefore, competitors can draw their own assumption over more profitable neighborhoods. 

Again, the more information a competitor has, the more useful the clustering analysis is during a decision making process. 


<ins>Scenario 3: A commercial real estate firm is looking to lease office space to WeWork</ins>

In this Scenario, you are a commercial real estate firm looking to sell office space to WeWork. Were do you think they are looking to expand next? From this analysis, it is apparent that they are looking locations within Cluster \#3. If the commercial real estate firm has a location to sell near Lincoln Center, they can use this model to persuade WeWork that expanding to this neighborhood is in WeWork's best interest. 

### Conclusion

By clustering Manhattan neighborhoods based upon the venues in the area, you can identify geographical similarities. Midtown Manhattan and the Financial District are not located near each other, but they share similar characteristics which make those areas potential areas for WeWork expansion. However, Midtown Manhattan and the Upper East Side are relatively close to each other, but will not make for an optimal expansion based upon neighborhood data.

This Model can be tailored to the needs of the user and can be run for any business with multiple locations in Manhattan.
