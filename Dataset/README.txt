https://www.kaggle.com/datasets/tanlikesmath/the-oxfordiiit-pet-dataset

Resized & moved to a subfolder per class.

With the help of this source, https://github.com/ml4py/dataset-iiit-pet/tree/master, I found 5 corrupted images, that could not be reconverted to a format that tensorflow accepted. They were deleted.
Abyssinian_34.jpg
Egyptian_Mau_139.jpg
Egyptian_Mau_145.jpg
Egyptian_Mau_167.jpg
Egyptian_Mau_177.jpg

There are 3 .mat files, they were converted to jpg (or duplicate .mat were present?).
Abyssinian_100.mat
Abyssinian_101.mat
Abyssinian_102.mat

There are 3 images in RGBA color mode, A is for transparency
Abyssinian_5.jpg
Egyptian_Mau_14.jpg
Egyptian_Mau_186.jpg
Converted to RGB color mode.
