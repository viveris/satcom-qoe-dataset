# satcom-qoe-dataset
On this depot, we give access to the dataset of our paper *Prediction of Youtube QoE over SATCOM*.
If you are interesed in additional data or information, contact matthieu.petrou@viveris.fr.

## Sources of the data
We collected Quality of Experience (QoE) data of YouTube application and information from packet traffic, over emulated satellink link by OpenSAND (https://github.com/CNES/opensand).

## Datasets
The "training" and "test" files were used to train and test our models, respectively. 
Each session can be seperated by the "session" number (first column).
For the QoE metrics:
 - video\_started: When the video has not started yet, the value of "video\_started" is equal to 0, and it is equal to 1 otherwise.
 - stalling: After the video has started, "stalling" is equal to 1 when there is a stalling, and equal to 0 otherwise.
 - resolution: After the video has started, the resolution is equal to:
   - -1: the resolution changed or stalling occured during the last second
   - 0: the resolution played was 144p
   - 0.2: the resolution played was 240p
   - 0.4: the resolution played was 360p 
   - 0.6: the resolution played was 480p 
   - 0.8: the resolution played was 720p 
   - 1: the resolution played was 1080p 

## Licence
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

# satcom-qoe-dataset
