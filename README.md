# S.E.A
Various attempts at performing automatic deception detection through text using natural language processing techniques as part of my graduation project titled 'S.E.A : smart employee analyzer' which included a candidate ranker feature that was based on automated deception detection of the job interview.
The attempts include both a traditional machine learning approach as well as a deep learning approach.
Experiments were done on 2 datasets, one was the real-life trial dataset by Michingan uni and the other using The MU3D by Miami uni.
The best accuracy on text was 92%, achieved using a multinomial naïve Bayes model with default parameters, we also achieve a similar accuracy of 91% using an SVM model (C=1, Gamma = 9) and notice that lowering gamma or raising C too much results in a reduced accuracy.
The best accuracy using the deep learning method was 75% using the CNN shown in Fig2 on the Real-life Trial dataset and Adam optimizer.
On the MU3D the best accuracy was 73% also using Multinomial Naïve Bayes with default parameters and an accuracy of 68.7% was achieved using an SVM model (C=1 , Gamma=9).
The deep learning results were less than ideal achieving only 50% using the CNN shown in Fig2 and Adam optimizer. 
Deep learning approaches didn't yeild any ideal results due to the small size of the datasets.
