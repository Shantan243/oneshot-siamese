# oneshot-siamese
Experiment leverages oneshot technique on realtime indutrial dataset with the help of siamese network. Objective is to classify and label the unknown image which model was not seen before inhand.
A Siamese neural network (sometimes called a twin neural network) is an artificial neural network that uses the same weights while working in tandem on two different input vectors to compute comparable output vectors. Often one of the output vectors is precomputed, thus forming a baseline against which the other output vector is compared
In this PoC, we have used an Automobile tool parts with 4 Label_names and steel surface defects datasets with 10 label_names (Multi -Label).
Automobile dataset is of Royal-enfield's (Private dataset, source cannot be referenced here.) while steel defects dataset(GC10-DET) is at https://www.kaggle.com/datasets/zhangyunsheng/defects-class-and-location
Labels are "Crease, cresentgap, Inclusion, oil spot, punching hole, rolling-pit, silk_spot, welding_line, waist_welding, waterspot"
With this experiement, we have achieved 83% accuracy in finding the label with one-shot training per label while the usual supervised DNN has acheived only 25% accuracy.
Please find PPT for better understanding.
source code for Supervised DNN and Oneshot - Siamese network is uploaded.
You may please try this with any kind of CV classification usecases
