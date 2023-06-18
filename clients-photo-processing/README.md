# Age prediction by photo

## Project description.
A chain supermarket is introducing a computer vision system for processing customer photos. Photo fixation in the checkout area will help determine the age of customers in order to analyze purchases and offer products that may interest buyers of this age group and monitor the integrity of cashiers when selling alcohol. A model is being built that can determine the approximate age of a person from a photo.
## Tools and technologies
* pandas
* matplotlib
* tensorflow
* numpy
* ResNet
* Pooling
* Adam optimizer
## Conclusion
To train the age recognition model, the ResNet50 architecture with pre-trained weights was taken as a basis, adapted for our regression task: A ResNet backbone with 50 layers and a head with one layer of a global pool and one neuron with 'ReLU' activators. The model showed an average absolute error on the test of 6.3 years, which is a satisfactory result for our task, the retraining of the model was manifested in the number of epochs more than 6.
