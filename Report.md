<h3>Buisness Case </h3>
Clustering different neighbourhood of toronto so that if one is willing to shift to a different one can choose one which is most similar to one he is prenstely living in .Also a person can make a customised neighbourhood (by specifying his requirements) and we can list the neighbourhood in order which matches his neeeds most.

<h3>Data Used</h3>
We would be using  neighbourhood, postal code ,and coordinates of toronto from wikipedia. Also we will use the venues details within 500m of every neighbourhood from the Foursquare Api.

<h3>Methodology</h3>
1.Intially I collected data for the Neighbourhood postal code names and borough
2.Then we also got the coordinates for each postal codes
3.Further we colled the venues detail within 500m of the neighbourhood coordinates.
4. One hot encoding was done with respect to the Venue category
5. We summarrised the presence of every category for each neighbourhood 
6.Further we found the top 10 most frequently present categories in each neighbourhood and used them as a data set 
7. We applied Kmeans clustering with n=4 

<h3>Results</h3>
For predicting we asked user for present postal address and printed the neighbourhood in the same cluster

<h3>Discussion</h3>
We could also have displayed this list of neighbourhood in a sorted order with respect to the most similar neighbourhood being at the top

<h3>Conclusion</h3>
Hence we are succesfully able to predict a neighbourhood which user might like to shift to matching his needs.
