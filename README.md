# Non-EEG-Signal-Processing
Signal Processing of Non-EEG Dataset for Assessment of Neurological Status collected at Quality of Life Laboratory at University of Texas at Dallas

## Introduction

This database contains non-EEG physiological signals collected at Quality of Life Laboratory at University of Texas at Dallas, used to infer the neurological status (including physical stress, cognitive stress, emotional stress and relaxation) of 20 healthy subjects. The data was collected using non-invasive wrist worn biosensors and consists of electrodermal activity (EDA), temperature, acceleration, heart rate (HR), and arterial oxygen level (SpO2).
Data Collection

The experimental procedures involving human subjects described in this work were approved under UTD IRB # 12-29 by the Institutional Review Board at the University of Texas at Dallas, Richardson, Texas, USA.

The dataset consists of 7* stages/5min for 20 subjects:

1. First Relaxation
2. Physical Stress
3. Second Relaxation
4. Mini-emotional stress*
5. Cognitive Stress
6. Third Relaxation
7. Emotional Stress
8. Forth Relaxation

* Mini-emotional stress/40s was a time period when the Subjects were given the instructions of the next stage and was not originally intended to count. After all, instructions were given for each of the tasks. Unlike the other instruction sets, however, this one created a stress response in many of the volunteers that was obvious to the test administrator as the test was being given.

The current project uses the Raw Data of the experiment that are publically available at:
[Database at University of Dallas](https://personal.utdallas.edu/~nourani/Bioinformatics/Biosensor_Data/)

But this Dataset is also available at:
[Database at Physionet](https://physionet.org/content/noneeg/1.0.0/)

## Instructions

Try running this project locally following the above steps:
1. Clone this repo
2. Open the project folder and place all the CSV files for each subject in it
3. Open the jupyter notebook and start testing!


### Citations:

1. Birjandtalab, Javad, Diana Cogan, Maziyar Baran Pouyan, and Mehrdad Nourani, A Non-EEG Biosignals Dataset for Assessment and Visualization of Neurological Status, 2016 IEEE International Workshop on Signal Processing Systems (SiPS), Dallas, TX, 2016, pp. 110-114. doi: 10.1109/SiPS.2016.27
2. Greco, Alberto & Valenza, Gaetano & lanatà, Antonio & Scilingo, Enzo & Citi, Luca. (2016). cvxEDA: A Convex Optimization Approach to Electrodermal Activity Processing. IEEE Transactions on Biomedical Engineering. 2016. 797-804. 10.1109/TBME.2015.2474131. 
3. S. Begum, "Sensor signal processing to extract features from finger temperature in a case-based stress classification scheme," 2009 IEEE International Symposium on Intelligent Signal Processing, 2009, pp. 193-198
5. Zhu, J., San-Segundo, R. & Pardo, J.M. Feature extraction for robust physical activity recognition. Hum. Cent. Comput. Inf. Sci. 7, 16 (2017). https://doi.org/10.1186/s13673-017-0097-2
6. Khadija El Bouchefry PhD, Rafael S. de Souza PhD, in Knowledge Discovery in Big Data from Astronomy and Earth Observation, 2020.
Eskandar, Sahel & Razavi, Saiedeh. (2020). Using Deep Learning for Assessment of Workers’  Stress and Overload. 10.22260/ISARC2020/0120.



