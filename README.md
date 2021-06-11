# CNN_FaceAttributes

This is a multi label classification model for face attribute recognition like
wrinkles, freckles, glasses, hair color and thickness of the hair.
The model was created using a modified VGG16 model and its
original weights. Data used were heavily imbalanced and data
duplication/augmentation was used to create artificial samples
for the less dominant classes. The final model had success in
predicting properly the glasses attribute while the remainder of
attributes were poorly predicted. The model predicted glasses
properly in 8 out of 10 possibilities. 
