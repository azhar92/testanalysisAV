# testanalysisAV
A tool to perform quick analysis to evaluate the behavioral safety of AVs


Input:

1) Vehicle dynamic parameters from OxTS IMU in csv format

Output:

1) summary of the analysis based on the objective metric for behaviourial safety of AV for urban based conditions

Methodology

1) Data preparation
2) Application of objective metrics 
3) Display the necessary outputs
4) Create report
5) Automate  


**Data preparation**

1) Read OxTS data
2) Clean/smooth/filter the data, following the automotive standards/best practices

    i) Identify the filter and optimzize its relevant parameters for the revelant dataset e.g cut-off frequency and order of frequency
    
    ii) Finalize the configurations

**Application of metrics**

1) Build the relationship with the data and the application of objective metrics

    i) Identify the features of the data that corresponds with the metrics e.g. maximum,minimum, feature of the graph, delta/gradient..
    
    ii) implement functions for each criteria
    
    iii) Report the summary
    
**Display the necessary outputs**

1) Display the metrics in appropriate visualisation
2) Display the important values
