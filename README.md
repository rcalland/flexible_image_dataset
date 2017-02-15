# chainer-flexible-image-dataset
Flexible Image Dataset for Chainer

## Usage
Pass the class a path to a text file which contains image path / label pairs, separated by a space, and each sample on a new line. Images will all be resized using `size` (default is 128x128 pixels).
```
training_data = FlexibleImageDataset(data_annotations, mean=5.43, size=(64,64))
```