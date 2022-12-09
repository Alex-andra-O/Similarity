# Great Minds Think Alike: New Measures to Quantify the Similarity of Recalls <br>

### __Overview__

Study consisted of 2 simulations (see *Simulation*) and 3 experiments. 2 of the 3 experiment are reported in the main body of the manuscript and 1 in the supplementary material. Naming convention is as follows:<br>
__Name in current manuscript = Name in original data set__<br>
Analysis 1 = Experiment 2<br>
Analysis 2 = Experiment 3 <br>
Supplementary material = Experiment 1<br>

To run the code, go to OSF, download the raw data. Store it in the same folder as the code for the respective experiment and run.

### __General comments__

Jupyter lab notebooks of all 3 experiments follow a similar structure. Similarity measures can be found at the top, followed by data preparation, concluded by the analyses that are reported in the manuscript. Detailed attention should be paid to the experimental design as there are small but relevant design differences between the experiments.


### __Data__

Data is available [on OSF](https://osf.io/cdfm7/). Please save the data for each experiment in the `data` folder associated with the corresponding experiment:

```
Similarity
│   README.md
│
└───Experiment1
│   │
│   └───data
│       │   encoding_10_0.dlm
│       │   encoding_10_0.pkl
│       │   ...
│       │   retrieve_10_0_2.dlm
│       │   retrieve_10_0_2.pkl
│       │   ...
│   
└───Experiment2
│   │
│   └───data
│       │   encoding_100_0.dlm
│       │   encoding_100_0.pkl
│       │   ...
│       │   retrieve_100_0_1.dlm
│       │   retrieve_100_0_1.pkl
│   
└───Experiment3
│   │
│   └───data
│       │   encoding_10_1.dlm
│       │   encoding_10_1.pkl
│       │   ...
│       │   retrieve_10_0_1.dlm
│       │   retrieve_10_0_1.pkl
│   
└───Simulation
```

### __Environment__
The most important packages requried and the versions used in our analyses are as follows:

matplotlib==3.3.2\
numpy==1.19.1\
pandas==0.25.1\
seaborn==0.11.1\
pingouin==0.5.2\
scipy==1.3.1
