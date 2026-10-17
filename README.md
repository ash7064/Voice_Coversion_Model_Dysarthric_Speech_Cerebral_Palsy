Currently, up to 78% of the 29.6 million people with Cerebral Palsy worldwide have dysarthria, a neuromotor condition that leads to imprecise articulation and decreased
intelligibility of speech. Many of these people face stigmatization and emotional distress due to inability to communicate. 
In order to improve clarity of dysarthric speech, this study aims to create a deep learning model that converts the features of dysarthric speech to normal or control features. 
This study uses control and dysarthric audio samples from the TORGO Database of Acoustic and Articulatory Speech From Speakers With Dysarthria and the 
Dysarthric Speech Database for Universal Access Research to train the models. Audio samples are converted to spectrograms, heat maps of decibel and frequency levels over time, 
before being fed into a UNet and Variational autoencoder, where features of control speakers are matched to features of dysarthric speakers. 
Finally, spectrograms are converted back to audio and fed through Google’s Automatic Speech Recognition to see if intelligibility is improved. 
Successful voice conversion models can be used by dysarthric speakers in their day-to-day lives so that they may be more clearly understood by those around them.



**Still a work in progress.
