# Covid19_contact_tracing

To identify infected people, the authorities follow the activity of patients diagnosed in the last 14 days. This process is called contact tracking. Depending on the country and the local authority, the search for contacts is carried out either by manual methods or by numerical methods.

DBSCAN is a density-based data clustering algorithm that groups data points in a given space. The DBSCAN algorithm groups data points close to each other and marks outlier data points as noise.It is good at clustering where there is high density areas.

In Singapore's context , we can get the information on places visites by individuals from the Trace Together App. I will use a hypothetical dataset  in this task is a JSON data , which constitutes the longitude and latitude of an individual. This could be one of the places which he has visited recently.

I will crate a model for contact tracing using the DBSCAN model which will generate clusters, which will help identify infections by filtering the data in the clusters.

To find people who may be infected by someone who has been diagnosed with Covid19, we can call the get_infected_names function. The function will return a list of individuals which we can contact for contact tracing purposes.
