# UCLA STATS 426-final
Stats 426 Deep Learning Final Project: Predicting Genre through Visual Cues: A Deep Learning Approach to Music Genre Classification from Album Cover Art

Leena Kang, Shaina Wang, Emily Kim, Amber Jiang

Abstract: 
Music genre classification has traditionally focused on analyzing audio signals, where models leverage features such as spectrograms to effectively learn patterns associated with different musical styles. However, music is not only defined by sound but also by its visual presentation, particularly through album cover artwork. Album covers often reflect stylistic and cultural elements intended to communicate the mood or identity of the music, suggesting that visual cues may contain signals related to genre. Despite this, the extent to which visual information alone can support accurate genre classification remains unclear.

In this work, we investigate whether modern deep learning models can classify musical genres using only album cover images. We train and evaluate two convolutional neural network (CNN) architectures: a simple custom CNN that serves as a baseline model and a deeper ResNet-50 model implemented in PyTorch. Both models are trained on a dataset of album cover images spanning five music genres, and performance is evaluated using overall classification accuracy and class-wise F1 scores to analyze genre-specific confusion patterns.

Our experiments show that the ResNet-50 model consistently outperforms the baseline CNN, indicating that deeper architectures are better able to extract meaningful visual representations from album artwork. However, overall performance remains limited, suggesting that genre classification based solely on visual features is a challenging task. We also observe signs of overfitting in the ResNet-50 models even with regularization methods, which may be likely due to limited training data and the high variability of artistic styles within genres. These findings suggest that while album cover imagery may contain some genre-related signals, visual features alone may not be sufficient for reliable genre classification without larger datasets or complex approaches.
