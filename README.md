# Pokemon-EDA

![alt text](https://github.com/bwadde01/Pokemon-EDA/blob/master/pokemon_clustering.png)

The following exploratory data analysis was done on Pokemon and their base stats which range from type, hp, attack, legendary status, etc. After cleaning, performing dimensionality reduction, analyzing, and clustering our data, we overlaid the results with images of the Pokemon. The datasets used for this exploratory analysis can be found here: [https://www.kaggle.com/vishalsubbiah/pokemon-images-and-types][ https://www.kaggle.com/abcsds/pokemon]

We initially found that we could not match the Pokemon stats and image datasets on Pokemon ID #s as the same Pokemon may potentially have multiple iterations (Charizard, Mega Charizard, etc.). After matching our two datasets on the name, we found mismatches due to naming conventions and proceeded to reformat names while excluding Mega evolutions.

To visualize the data, we performed principal component analysis (PCA) and leveraged the first two principle components. After mapping the principal components on a scatterplot, we tried to cluster the data to identify typical groupings and found 6 groupings provided the best results. 

Please find our conclusions in our notebook and we hope you enjoy our visualization of how we grouped different types of Pokemon! 
