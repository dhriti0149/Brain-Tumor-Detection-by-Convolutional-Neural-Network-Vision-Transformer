# Brain-Tumor-Detection-by-Convolutional-Neural-Network-Vision-Transformer
Here, I have built a deep learning model to detect if a mass present in a brain MRI image is tumor or not by Convolutional Neural Network & Vision Transformer

Brain tumor is a disease that happens when there is abnormal growth of cells within or around the brain. Based on the type,location,size of the tumor it can affect critical neurological functions. The symptoms of this particular illness may include headache,seizure,weakness,difficulties in walking,loss of vision,speech or hearing.

Magnetic Resonance Imaging (MRI) is an important medical imaging technique. It is a safe medical test that uses strong magnets and radio waves to make clear pictures of the inside of your body. It does not use x-rays or radiation. It's used to look at organs, bones, muscles & blood vessels to predict disorders. MRI can be used to detect suspected tumors in the brain by evaluation of brain abnormalities.

MRI scans has complex visual patterns. Hence, deep-learning can be used for automated image classification and detect the presence of brain tumors.

Here,Convolutional Neural Networks (CNNs) & Vision Transformers (ViTs) are used for a binary classification task:
Yes: Tumor detected in the MRI image
No: Tumor not detected in the MRI image

CNNs are a deep-learning architecture widely used for image analysis. CNNs use convolutional filters to learn spatial features from images, progressing from simpler patterns such as edges and textures to more complex structures. Here, a CNN is used to classify brain MRI images into tumor and no-tumor categories.

Vision Transformers applly the Transformer architecture to images. Instead of processing an image primarily by convolutional filters, a ViT divides the image in smaller patches, converts them to embeddings & uses self-attention to learn relationships between different parts of the image. Here, ViT gives an alternative approach to CNN-based image classification.
