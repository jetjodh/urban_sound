# urban_sound

- This is an unique approach to classification models for urban sound dataset.

- The original dataset consists of soundclips of.wav format. These clips were plotted and saved as '.jpg' files so that image classification techniques could be applied to this dataset and an inception net architecture model trained on imagenet was retrained on the dataset taking each fold one-by-one as testing dataset. The resulting avergae categorial accuracy is 79.178 % on 10-fold dataset split.

-No image augmentation has been used yet but it can be used to push the accuracy further high which might also possibly reach state of the art results.
