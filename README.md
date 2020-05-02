# DogsVsCats-Classification-convolutional_neural_network
A convolutional neural network for classification of the Dogs and Cats dataset provided by microsoft.

## Getting the data
The data can be found at [Cats-vs-Dogs|Kaggle](https://www.kaggle.com/shaunthesheep/microsoft-catsvsdogs-dataset) or [here](https://www.microsoft.com/en-us/download/details.aspx?id=54765)
After downloading unzip the files and transfer them to your current working directory
Set the flag`REBUILD_DATA` to `True`.

Now on the first run it will generate a `.npy` file and can be set to false because we have transferred the data into this file.

## Training and Testing
Just run the train function changing the `EPOCHS` size to your desired epochs. Also note the model name and file name if you want to plot the data and assign it to a variable in the last block.

## Plotting the data
With the model name and file name variables as arguements run the `create_acc_loss_graph()` and the plot will be generated.
