# CDC_Health_Clusters
 An unsupervised learning project to identify groups of people with similar health outcomes, prevention practices, and bad habits.
 
 
Heart disease is the leading cause of death in the United States. The disease is largely preventable by monitoring blood pressure, cholesterol, and body weight. However,
these are not the only indicators/risk factors. Addionally, is it possible to narrow down who needs to be targeted for preventative treatment?

This project uses the K-Means clustering algorithm to form four distinct risk groups.


The differences in these groups can be broken down into three categories: negative health outcomes, preventative measures, and bad habits.
Negative health outcomes includes chronic diseases such as diabetes, COPD, and cancer.
Preventative measures include medications and screenings.
Bad habits include lifestyle choices that negatively impact health such as smoking and obesity.


Group 0 is a catchall group for people who don't fit into the other groups.
Group 1 is the healthy group with low prevalence of disease, high prevalence of preventative activities, and low prevalence of bad habits.
Group 2 is the antithesis of Group 1: high rates of disease, low prevalence of preventions, and high prevalence of bad habits.
Group 3 is the uninsured group. They don't partake too much in the bad habits, but don't  have access to the preventative measures, which is perhaps why they have slightly higher prevalence of disease.
