# AI_course_project

The goal of this project is to provide a automatic deep lean-ing network to remove the 
EOG (eye movement) artifactsfrom EEG data. We use a semi-simulated EEG dataset in which 
artifact-freeEEG signals are manually contaminated with ocular artifacts,using a realistic
head model. In this dataset, 54 EEG samples were recorded from 14 male and13 female subjects
during a closed-eye and opened-eye experiment. As a result, the obtained EEG is free of 
ocular artifact. This experiment is run by 19 electrodes. We propose customized 
U-Net structure to denoise the contaminated signal. The U-net structure a fully Convolutional 
decoder-encoder Neural Network. Our network adopts basic concepts from U-Net for 1D time-series segmentation by 
mapping a whole sequence to a dense segmentation.