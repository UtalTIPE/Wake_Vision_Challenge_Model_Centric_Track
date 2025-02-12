Participant name: Yanis MAC

Because of hardware limitations, I focused on training a new model without playing too much with the hyperparameters.  
I trained a few different models from the initial one, on a small subset that represents 10% percent of the original dataset, changing different parameters for each of them, then after a few epochs (around 5) I simply took the best one in view of its performance and size.

Changes:
 - Increased number of filters in the model architecture
 - Replaced Conv2D with SeparableConv2D to keep same efficiency with smaller model size

After training on the small subset, I trained the model during 5 epochs on the whole dataset
