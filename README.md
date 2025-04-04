# Automatic Speech Recognition (ASR) System

In this task, we made a prototype of an ASR application for an airport virtual assistant using Python. The software package we used was Vosk.

The Vosk ASR system was configured with pre-trained language models for English, Spanish, and Italian. Before conducting the tests with our various audio files, we preprocessed them first to try to reduce as much background noise as possible. To address this, we applied the noise reduce library, which reduced the ambient noise in the audio files without compromising much speech clarity. We also ensured consistent audio levels using librosa for accurate recognition. Lastly, we adjusted the audio files to 16000 Hz as it is compatible with Vosk’s models.