# Retina Pathology Diagnosis
#### Introduction to Deep Learning, University of Colorado, Boulder

This project attempts to classify optical coherence tomography (OCT) images of the retina.  OCT is a non-invasive imaging technique that uses light to generate cross-sectional scans.  When applied to the retina, a number of pathologies can be identified.  Traditionally, diagnoses have been made manually by a qualified medical professional.  However, with the power of neural networks, it should be possible to automatically detect the health of the retina.  If such automatic diagnosis accuracy is comparable with a human, then automating this task could help reduce the costs associated with identifying retinal issues.   

In addition to attempting to achieve a high classification accuracy on this task, I would also like to explore the use of transfer learning to speed up training on neural network image classification.  The Keras module offers a number of out-of-the-box neural network architectures with training weights that have already been optimized on the ImageNet dataset.  While the ImageNet dataset is composed of everday objects (not scans of retinas), it may be possible to leverage the existing learning for improved performance and faster training.  As the training time for state-of-the-art neural networks can be weeks, using pre-trained models could make the most powerful classfication accessible.  It would just be necessary to train the lower levels of the model, and then do a short fine-tuning of the model with a very low learning rate.  

The data for this project has been obtained from the following dataset:
> Kermany, Daniel; Zhang, Kang; Goldbaum, Michael (2018), “Large Dataset of Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images”, Mendeley Data, V3, doi: 10.17632/rscbjbr9sj.3

The images were initially used for research conducted by Daniel S. Kermany and other researchers at the University of California San Diego and the Guangzhou Women and Children's Medical Center.  Their results were published in the 2018 article, "Identifying Medical Diagnoses and Treatable Diseases by Image-Based Deep Learning."
