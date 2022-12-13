# dog_unwilling_unable
Data and R scripts for the study entitled: "Unwilling or Unable? Using 3D tracking to evaluate dogs’ reactions to differing human intentions."

## Structure

```
.
├── Exp1 
│   ├── unwilling-unable_analysis.rmd             <-- R markdown file including analyses of video scoring data of Exp 1  
│   ├── data                                      <-- data of video scorings of Exp1 and demographic data
│   ├── functions                                 <-- Functions (e.g. for CI bootstraps) kindly provided by Roger Mundry. 
│   ├── graphs                                    <-- figures based on video scorings of Exp1
│   └── saves                                     <-- results of GLMMs
├── Exp1_3D           
│   ├── 01unwilling-unable_3D_data_processing.Rmd <-- R markdown file including data processing pipeline from raw data 3D data to trial-level data, including scripts for plots of individual trajectories
│   ├── 02unwilling-unable_3D_data_analysis.rmd   <-- R markdown file including analyses of 3D tracking data of Exp 1
│   ├── data                                      <-- aggregated 3D tracking data of Exp1  
        └── raw                                   <-- raw 3D tracking data of Exp1  
│   ├── graphics                                  <-- figures based on 3D tracking data of Exp1
        └── interpolated2                         <-- figures of individual trajectories (based on filtered and interpolated data) 
│   ├── functions                                 <-- Functions (e.g. for tail angle calculation, etc.) kindly provided by Roger Mundry.
│   └── saves                                     <-- results of GLMMs
└── Exp2           
    ├── unwilling-unable_analysis_followup_new.rmd<-- R markdown file including analyses of video scoring data of Exp 2  
    ├── data                                      <-- data of video scorings of Exp2 and demographic data
    ├── functions                                 <-- Functions (e.g. for CI bootstraps) kindly provided by Roger Mundry. 
    ├── graphs                                    <-- figures based on video scorings of Exp2
    └── saves                                     <-- results of GLMMs
```
