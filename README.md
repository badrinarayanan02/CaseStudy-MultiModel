## Fashion Product Recommendation System ##

Fashion Product Recommendation System that utilizes a combination of deep learning, natural language processing (NLP), and computer vision techniques. 

### Deep Learning ###

Model Architecture: The system employs pre-trained convolutional neural network (CNN) models such as DenseNet121 and VGG16 for image feature extraction.

Feature Extraction: The last few layers of the CNN models are removed, and a GlobalMaxPooling2D layer is added to extract image embeddings, capturing high-level visual features from product images.

Recommendation System: These image embeddings are used to calculate similarity between products using cosine similarity or linear kernel, aiding in the recommendation of visually similar products.

### NLP (Natural Language Processing) ###

Text Preprocessing: NLP techniques are applied to preprocess textual data such as product names and descriptions. Tasks include tokenization, stop word removal, and lowercasing to clean and normalize text data.

Feature Extraction: Preprocessed text data is vectorized using techniques like TF-IDF (Term Frequency-Inverse Document Frequency), converting text into numerical representations that capture word importance.

Multimodal Fusion: Extracted text features (TF-IDF vectors) are concatenated with image embeddings to create a multimodal representation of products, combining visual and textual information.

### Computer Vision ###

Image Preprocessing: Computer vision techniques are applied to preprocess images before feeding them into CNN models. Tasks include resizing, normalization, and augmentation to ensure consistency in image sizes and formats.

Feature Extraction: Deep learning models like DenseNet121 and VGG16 extract meaningful features from input images, learning to capture visual patterns and characteristics.

Recommendation System: Extracted image embeddings represent visual features of products, enabling calculation of similarity scores between products and recommending visually similar items

## Image Recommendation ##

![productsRec](https://github.com/badrinarayanan02/CaseStudy-MultiModel/assets/139948861/5e435223-2879-45c1-85ec-93d69c486fea)


### Conclusion ###

In summary, the Fashion Product Recommendation System leverages deep learning for image feature extraction, NLP for text preprocessing and feature extraction, and computer vision techniques for image preprocessing and feature extraction. By combining these technologies, the system creates a powerful multimodal representation of products, enabling accurate and effective product recommendations based on both visual and textual information.
