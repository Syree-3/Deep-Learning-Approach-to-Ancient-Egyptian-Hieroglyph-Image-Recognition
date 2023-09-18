In this GitHub project, I leveraged Convolutional Neural Networks (CNNs) in Python to classify ancient Egyptian hieroglyph images. The dataset comprised 4,210 annotated hieroglyph images from the Pyramid of Unas. The objective was to build an image classifier capable of recognizing and predicting Gardiner labels for various hieroglyphs.

**Steps in the Code:**

Data Loading and Preprocessing: The project began by loading and preparing the dataset for training.

**Data Augmentation:** To enhance dataset diversity and model robustness, I applied image data augmentation techniques.

**Model Building and Training:** Two models were developed and trained. The first was a custom CNN, while the second employed transfer learning with VGG16.

**Model Evaluation:** Performance evaluation, including accuracy, was conducted on a validation set.

**Model Saving**: Trained models were saved for future use.

**Testing:** I loaded and tested the saved models on sample images to predict hieroglyph classes.

**Results:** Both models achieved nearly 100% accuracy, showcasing strong hieroglyph classification abilities. Further testing on larger datasets may provide a more realistic accuracy estimate.

The project highlighted the significance of Gardiner's Sign List as a reference in studying Egyptian hieroglyphs. The classifier aimed to recognise hieroglyphs and predict their Gardiner labels, including S29, M17, X1, and G43. It's important to note that only a fraction of the dataset was utilised for training.

For detailed implementation and code, refer to the accompanying GitHub repository.

