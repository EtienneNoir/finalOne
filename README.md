OneShot
Project_CSC_Honours

This notebook can also be executed on Kaggle. However, the images used to test the model, including personal images, may not be available due to their private settings.

The model was evaluated with a focus on how faces are typically presented in real-world banking scenarios, simulating practical conditions for better accuracy.

For more information on how to download the Real World Occluded Faces (ROF) dataset, you can visit the following link: https://github.com/ekremerakin/RealWorldOccludedFaces/blob/main/README.md

While this is not an ATM application, the model serves as a proof of concept that could be adapted in the future to enhance verification systems or security measures at ATMs.

By focusing on similarity rather than classification, the model can work with images from different datasets without needing to be re-trained to classify them. Although fine-tuning may still be required, the current version of the model is capable of differentiating less complex images effectively.

The key aspect of this model is measuring image similarity through distance values, which indicate how well the model distinguishes between different or similar images.

Please run the code on Kaggle to be able to have access to the same dataset that I used
