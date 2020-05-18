# AI_course_project

The goal of this project is to provide a automatic deep learning network to remove
EOG (eye movement) artifacts from EEG data. We use a semi-simulated EEG dataset in which 
artifact-free EEG signals are manually contaminated with ocular artifacts, using a realistic
head model. In this dataset, 54 EEG samples were recorded from 14 male and 13 female subjects
during a closed-eye and an opened-eye experiments. This experiment is run by 19 electrodes. 
We propose customized  U-Net structure to denoise the contaminated signal. The U-net structure
a fully Convolutional decoder-encoder Neural Network. Our network adopts basic concepts from 
U-Net for 1D time-series segmentation by mapping a whole sequence to a dense segmentation.
