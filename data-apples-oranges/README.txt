This README contains information about the dataset used in the paper: Counting Apples and Oranges With Deep Learning: A Data-Driven Approach (http://ieeexplore.ieee.org/abstract/document/7814145/)

The dataset is organized as follows:

Images: 
- This contains the source images.
- Contains sub folders for each category of images.
- Contains two categories: Orange and Nightime Apple.
- There are 76 Orange images and 27 Nightime Apple images.

Labels: 
- This contains the labelled image masks. 
- Contains sub folders for each category of images.
- During the labelling process, each image was divided into a grid of windows and cropped.
- The image window grid has 4 rows and 4 columns.
- Each window of the source image was labelled by 3 users. Therefore each source image has 48 labels.
- Finally, each window for a given source image is averaged over 3 labels and grouped together to form the full image label.
- The file name of the label follows this pattern "%IMAGE_CATEOGRY%_label_%SOURCE_IMAGE_NAME%".
- There is one lable image mask for each source image.

Labels_SVG: 
- Contains csv files related to the SVG data for the labels. There is one csv file for each category of images.
- There are two columns in the csv file: Image label file name and SVG information for the label.
- Each row of the csv file contains a label for a window in a given source image.
- Since each image has 48 labels there will be 48 rows for each labelled image.
- This can be used to obtain the counting information of the fruits.


Contact Info:

Steven Chen <chenste@seas.upenn.edu>
Sandeep Dcunha <sdcunha@seas.upenn.edu>
Shreyas Aditya <ashreyas@seas.upenn.edu>
Shreyas Skandan <sshreyas@seas.upenn.edu>
Jnaneshwar Das <djnan@seas.upenn.edu>
