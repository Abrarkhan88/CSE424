Task 4c2
EuroSAT before Pre-Processing
Dataset before pre-processing
github
EuroSAT After Pre-Processing
Pre-processing with EDA
Exploratory Data Analysis (EDA) Steps
PRE-EXPLORATORY ANALYSIS:
Data Distribution in Classes
Analyzing the number of images across different classes.

Visualizing Sample Images
Random visualization of images from each class to ensure data integrity and correct loading.

Pixel Intensity Analysis
Checking pixel intensity (sum, mean, median) of sample images.

Correlation Between Channels
Visualizing and analyzing correlation between RGB channels.

POST-EXPLORATORY ANALYSIS:
Data Distribution in Classes
Ensuring data distribution remains consistent post-processing.

Normalizing and Transforming Images
Normalizing pixel values from 0-255 to 0-1 and applying random transformations (resize, flip, etc.).

RGB Distribution
Visualizing RGB distribution on transformed images.

Image Ratio Distribution
Ensuring image height and width remain constant after transformations.

Correlation Between Channels
Re-checking correlation between RGB channels post-normalization.

Post-Process Pixel Intensity Distribution
Analyzing pixel intensity distribution after normalization.

Data Augmentation
Applying data augmentation techniques using PyTorch’s permute() for tensor manipulation.