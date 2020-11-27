# Root-Canal-Classification 

1) I have used 2 algorithm to solve this classification problem i.e VGG16(Base Line Model) and VGG19. As, validation data was not provided I used the strategy of hold out validation and out of the entire dataset which was provided I used 80% for training and rest 20% I used it for validation. 

2) I used AUC as a metric for monitoring my algorithm performance.

3) I acheived 89.98% AUC on validation data when I used VGG16 whereas I got 94.23% AUC score on validation data whjile using VGG19 model. Intuitively, AUC gives a score, with higher scores closer to 1 indicating that the different classes can be distinguishable for the model. A lower score closer indicates that the the model cannot distinguish between different classes. 

4) The basic difference between between VGG16 and VGG19 was the nos of layers. VGG16 has 2-64, 2-128, 3-256, 3-512, 3-512 and 3 Fully connected Layer with 4096 neurons. VGG19 has 2-64, 2-128, 4-256, 4-512, 4-512 and 3 Fully connected layers with 4096 neurons. 

5) We could acheive better accuracy in VGG19 becuase it could derive more number of features as compared to our baseline model VGG16.


