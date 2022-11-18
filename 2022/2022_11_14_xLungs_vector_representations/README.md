## Lungs vector representations

**Abstract:** It’s well-known that the medical domain datasets contain few labeled instances. Thus, leveraging informative numerical representation of lungs can allow training models which do not require large amounts of labeled samples and still perform well on downstream tasks. In xLungs we try to create lung representations in unsupervised fashion which are later applied for disease classification. We will familiarize you with three attempts for creating vector representations of lungs. First is the Siamese network, which allows us to create embeddings from X-ray images. Another approach that will be introduced is embeddings created from CT scans using the Swin-UNETR model. Finally, we will show you how one can create interpretable features from organ masks (not only created by humans).