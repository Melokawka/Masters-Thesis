# Camera Movement Classification Using a Deep Learning Model Trained on Synthetic Video Clips 
Table of contents	
Introduction
1.	Definition of the problem	
1.1.	Characteristics of the problem	
1.2.	Limitations of using real-life cinema video datasets	
1.3.	Overview of movie classification and synthetic data generation	
1.4.	Analysis of real-life video HAR datasets	
2.	Theoretical background	
2.1.	Understanding motion using optical flow	
2.2.	Convolutional neural networks, training and hyperparameters	
2.3.	3D convolutional networks	
2.4.	Video Transformers	
3.	Generating and testing synthetic data	
3.1.	Synthetic video clip generator	
3.2.	Synthetic dynamic camera shot dataset	
3.3.	Tests with the use of synthetic data	
Conclusions	
References	
List of figures	
List of tables	
Summary	

# Summary
Dynamic camera shot classification is a field that due to copyright and the significant data requirement of modern Deep Learning
can benefit greatly from synthetic data generation. 
The thesis modeled camera movement in a way that allows it to be generated synthetically. 
For this purpose an open-source Unity application was designed and implemented, 
enabling customizable parameterization of generated video clips and scenes. 
The large potential of synthetic generators to introduce multi-modality of data is considered and might lead to the built application
eventually being useful even outside of dynamic camera shot classification. 
The synthetic clip generator was used to generate a compact prototype of synthetic dynamic shot dataset. 
The choice of dataset generation parameters was discussed and both the parameters 
and generated data were evaluated using video Deep Learning methods like 3D convolutions and the Video Transformer. 
An approach to automated rating of synthetic data quality was proposed.
