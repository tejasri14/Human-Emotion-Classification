# Human-Emotion-Sentiment-Classification
This project aims to use Kaggle's EEG Brainwave Dataset to classify the moods of two people based on the movie they are watching.

"The data was collected from two people (1 male, 1 female) for 3 minutes per state - positive, neutral, negative. We used a Muse EEG headband which recorded the TP9, AF7, AF8 and TP10 EEG placements via dry electrodes. Six minutes of resting neutral data is also recorded, the stimuli used to evoke the emotions are below

> 1 . Marley and Me - Negative (Twentieth Century Fox) Death Scene > 2. Up - Negative (Walt Disney Pictures) Opening Death Scene > 3. My Girl - Negative (Imagine Entertainment) Funeral Scene > 4. La La Land - Positive (Summit Entertainment) Opening musical number > 5. Slow Life - Positive (BioQuest Studios) Nature timelapse > 6. Funny Dogs - Positive (MashupZone) Funny dog clips"

We use PCA to reduce the dimensionality of the data set and train the data on Classification Algorithms such as Random Forest Classification and XG Boost Classifier.

We take help from the research paper J. J. Bird, L. J. Manso, E. P. Ribiero, A. Ekart, and D. R. Faria, “A study on mental state classification using eeg-based brain-machine interface,”in 9th International Conference on Intelligent Systems, IEEE, 2018 to understand the features of the data.
