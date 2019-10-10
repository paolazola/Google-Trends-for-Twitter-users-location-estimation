# Google-Trends-for-Twitter-users-location-estimation
The dataset of the sample of 100 Twitter accounts used in an experiment for location estimation

The repository holds all the files used in the experiments to infer Twitter users home location exploiting the information of Google Trends engine.

In particular, the repository is composed by the followings files:
1) Sample100_groundTruth: the 100 Twitter accounts with verified location (see paper of Zola, P., Cortez, P., & Carpita, M. (2019). Twitter user geolocation using web country noun searches.) and the respective coordinates.
2) Sample100_cumulative_GTCitiesDistrib: for each of the 100 accounts we collected the Google Trends (GT) spatial indication, at city level, for each noun hold in them timeline (up to 3,200 past tweet for each user). We merge all the GT information for a given user obtaining the rapresentation in the file. It is a Python pickle file thus it can be read using the pickle Python module.
3) Random_Data100Sample_nK: different pickle files that extract from each user culumative GT distribution a series of random points (500-1000-2500-5000-10000-15000) in order to perform the coordinate level location estimation from the GT city data. These files are Python pickle file thus they can be read using the pickle Python module.


