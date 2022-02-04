# plot.ly-challenge

For this homework assignment, the D3 library was used to read the samples.json file, which included data involving the belly button biodiversity from 2011. In the study, the microbial species are referred to as Operational Taxonomic Units, also known as OTU. The following are the variables that were used to display information in the interactive dashboard:

    -sample values
    -OTU IDs
    -OTU Labels
    -ID
    -ethnicity
    -gender
    -age
    -location
    -bbtype
    
A bubble chart was created where the x-axis was labeled as "otu_ids", y-axis was information derived from the "sample_values", and the text was the "otu_labels" attached to each data point. The size of the bubble in the chart represented the frequency in the sample value. In other words, the bigger the bubble, the higher the sample value. Similarly, the darker the color that is seen from the bubble, the more OTU ID's are shown. This data is visualized by an individual's demographic information, which can be changed under the "Test Subject ID No." dropdown. 

Besides the bubble chart that was visualized, a bar chart was also inserted to see the top 10 OTUs found in an individual. Like the data from the bubble chart, this is subject to change based on each individual ID Number. A screenshot of the interactive dashboard has been provided below: 

![Screen Shot 2022-02-04 at 4 11 05 PM](https://user-images.githubusercontent.com/72631173/152617937-243fa1ae-9c55-43ba-a626-5f2484d7a001.png)


The coding for the data retrieval can be found under the app.js file.
