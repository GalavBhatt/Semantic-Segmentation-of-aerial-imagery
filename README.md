# Semantic-Segmentation-of-aerial-imagery
Semantic segmentation is performed in order to classify different attributes associated with the image.
###### The dataset consists of aerial imagery of Dubai obtained by MBRSC satellites and annotated with pixel-wise semantic segmentation in 6 classes. The total volume of the dataset is 72 images grouped into 6 larger tiles. The classes are:
###### Building: #3C1098
###### Land (unpaved area): #8429F6
###### Road: #6EC1E4
###### Vegetation: #FEDD3A
###### Water: #E2A929
###### Unlabeled: #9B9B9B

# Use patchify....
###### Tile 1: 797 x 644 --> 768 x 512 --> 6
###### Tile 2: 509 x 544 --> 512 x 256 --> 2
###### Tile 3: 682 x 658 --> 512 x 512  --> 4
###### Tile 4: 1099 x 846 --> 1024 x 768 --> 12
######  Tile 5: 1126 x 1058 --> 1024 x 1024 --> 16
######  Tile 6: 859 x 838 --> 768 x 768 --> 9
######  Tile 7: 1817 x 2061 --> 1792 x 2048 --> 56
###### Tile 8: 2149 x 1479 --> 1280 x 2048 --> 40
###### Total 9 images in each folder * (145 patches) = 1305
###### Total 1305 patches of size 256x256

# Final Result
![Final_output](https://user-images.githubusercontent.com/60823367/134293829-309a1a96-38b1-4694-931e-3d19f7257666.png)
![Final_output](https://user-images.githubusercontent.com/60823367/134293161-30c5f8b7-ba30-441c-b8fc-27c924a132ea.png)
