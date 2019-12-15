This notebook contains the code for creating a siamese neural network in keras.

It was trained with 10 datasets (LFW, FERET, AT&T...) and tested with 1 dataset (MUCT), resulting in more then 700,000 images (350,000 pairs).

I did considered saving all the imagens in a .h5 file and sharing in this repository, but it was not possible due to the fact that most of these datasets don't allow redistributions.

Each model of the siamese neural network has 8 convolutions. Dropout was also used to avoid overfitting.

The result for this network was 84% accuracy on the MUCT dataset.

The direct visualization of some of the results (distances between faces) can be seen in the end of the notebook.
