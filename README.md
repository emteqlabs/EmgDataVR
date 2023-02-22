# EmgDataVR

This is the official repository for the paper [“Facial EMG sensing for monitoring affect using a wearable device”](https://www.nature.com/articles/s41598-022-21456-1). It contains the code and the dataset used for the analysis presented in the paper. The EmgDataVR dataset was created by [Emteq Labs](https://www.emteqlabs.com/).

# Description
- For data collection, we used the [emteqPRO system](https://www.emteqlabs.com/emteqpro/), consisting of a VR sensor mask insert with a Pico Neo 2 Eye VR headset.
- The data used for the analysis were collected from a group of 38 healthy volunteers (14 females and 24 males, with a mean age of 33.4 ± 13.6)
- The affective stimuli database used in the study contains a total of 25 videos. A combination of video stimuli was selected from the public video library by [Samson et al.](https://www.tandfonline.com/doi/abs/10.1080/02699931.2015.1031089?journalCode=pcem20) and from a study by [Gnacek et al.](https://gnacek.com/affective-video-database-online-study), and seven new videos were introduced.
- Each participant's data is stored in a separate .csv file that contains the EMG contact (impedance), EMG Filtered, and EMG Amplitude (RMS) sensor data, followed by   labels representing the type of an affective video that the participant was watching, and the participant’s arousal and valence ratings.
- The total duration of the collected data is around 8.5 hours. 

# Download
The EmgDataVR dataset and the code for replicating the data preprocessing steps and generating the statistical results presented in the paper can be downloaded at the following [link](https://www.kaggle.com/datasets/emteqlabs/emgdatavr).

The affective stimuli database can be downloaded [here](https://drive.google.com/file/d/1Qr6N2b4kf0FW7rJNfdUYR1lF7AElET-5/view?usp=sharing).
Please acknowledge the use of the database in any future publications by citing also the original sources:

- *Samson, AC, Kreibig, SD, Soderstrom, B, Wade, AA, & Gross, JJ, (2016), Eliciting positive, negative and mixed emotional states: A film library for affective scientists. Cognition and Emotion, 30(5), pp. 827-856, (2016).* 

- *Gnacek M., Mavridou I, Seiss E, Kostoulas T, Balaguer-Ballester E., Nduka C. "AVDOS -Affective Video Database Online Study.” 2022, In: 10th International Conference on Affective Computing and Intelligent Interaction (ACII), Japan, 18-21 October, p:8, (2022).* 


# Contact 
For any information about the **EmgDataVR** feel free to contact us at ivana.kiprijanovska@emteqlabs.com

# Citation
If you find the data useful, please acknowledge the use of this dataset in any future publications by referencing the paper:  
[**Facial EMG sensing for monitoring affect using a wearable device**](https://www.nature.com/articles/s41598-022-21456-1)  
*Gjoreski, M.; Kiprijanovska, I.; Stankoski, S.; Mavridou, I.; Broulidakis, J.; Gjoreski, H.; Nduka, C.*  
Nature Scientific Reports 12, 16876 (2022). https://doi.org/10.1038/s41598-022-21456-1


