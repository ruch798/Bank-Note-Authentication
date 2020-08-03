# Bank-Note-Authentication
Everyday, millions of people use banknotes to make transactions. The security of these banknotes for governments and banks is hence an essential factor to fight against fraud. Nowadays, sometimes it is too hard to spot counterfeit and genuine notes. The aim of this project is to create a support system ready to help organizations to accurately classify fraudulent/forged notes.

The Bank Note Authentication data set involves predicting whether the bank notes were forged or authentic based on the data which is extracted from the images of bank notes specimens. For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained. Wavelet Transform tools were used to extract features from images.

It is a multiclass classification problem. The number of observations for each class is balanced. There are 1382 observations/instances with 4 input variables and 1 output variable. 
- variance of Wavelet Transformed image (continuous)
- skewness of Wavelet Transformed image (continuous)
- curtosis of Wavelet Transformed image (continuous)
- entropy of image (continuous)
- class (integer) (It can have two values: 0 (false) and 1 (true))
