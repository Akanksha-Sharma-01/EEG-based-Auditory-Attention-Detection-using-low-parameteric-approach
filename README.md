# EEG-based-Auditory-Attention-Detection-using-low-parameteric-approach
It is a project done for course EE535P at Indian Institute of Technology (IIT), Mandi.
In multi talking audio environment such as a party, our brain focuses on the voice or sound we want to hear. In such an environment, if we are able to focus on a perticular sound or voice artificially, it can be used to develop hearing aids with better performance. This project deals with it and detects whether the person has heard sound from left or right ear when both the sounds are played simultaneously. 
It is a transformer based model. It takes EEG signals as input and classifies as right or left audio. 
The transformer takes the EEG signal, finds its self-attention in the encoder and generates the representation for classification. The classifier contains FCNN which classifies the EEG signal as right or left audio.
The dataset used is KULeuven dataset (https://zenodo.org/record/3377911#.Y7e_jXZBzIX)
