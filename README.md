
# HomeworkWeek6

For our assignment 6, we are to explore R and its many great services such as organizing, displaying, and statistically analyzing a given dataset.

In this repository, I have uploaded three files to assess Homework 6:

1. HTML file
2. link to RPubs document
3. .Rmd file for the R notebook created

The HTML file will provide graphical displays of a dataset used to navigate R. The last graph which is an interactive graph is not availabe via the HTML file. Therefore, you can refer to the RPubs link to see a hoverable, interactive graph of the dataset applied in Homework 6.

__Part 1: Getting data__

We'll start by using a dataset provided and named "gene_dist*head.tsv". Also, we'll need to install some libraries such as 'plotly' and 'dplyr' for working with this dataset. This will allow us to read the dataset in as a dataframe with columns and rows pre-labelled. 

__Part 2: Navigating the gene dataset__

Now that we've uploaded our data into a dataframe, we can visualize our data by clicking on it in the Global Environment panel on the right hand side. 

![Text](Users/maiacorpuz/Desktop/TRGN-510/images_Week_6_Rmd/mygenesdataframe.png, "Screenshot")

We can then get a summary of the data now that we've loaded in a data frame which is structured for R to navigate.

![Text](/Users/maiacorpuz/Desktop/TRGN-510/images_Week_6_Rmd/summaryofmygenes.png, "Screenshot2")

__Part 3: Graphing the gene dataset__

To practice creating graphical displays of this dataset in a new context, we can use the libraries 'plotly' and 'ggplot2'. First we should define a subset of the data based on interest in defining autosomes. We'll plot this as a bar graph to see features of these autosomes based on transcript_type: CDS, exon, gene, etc for the y-axis and chromosome number as the x-axis.

![Text](/Users/maiacorpuz/Desktop/TRGN-510/images_Week_6_Rmd/autosomes.png "Screenshot3")

Another graphical display of this bar graph is to create polar coordinates. You'll be able to visualize the higher counts of each transcript type contained within all autosomes defined.

![Text](/Users/maiacorpuz/Desktop/TRGN-510/images_Week_6_Rmd/polarcoordinate.png "Screenshot4")

Finally, to scale back to the bar graph data displayed, we can make the graph not only interactive but also more informative by introducing a hoverable option. 

![Text](/Users/maiacorpuz/Desktop/TRGN-510/images_Week_6_Rmd/interactive.png "Screenshot5")

By the end of this assignment, we should have some background in utilizing R to organize, interpret, and find significance in a dataset.
