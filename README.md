# Multi-Input-Model-for-OCR
Structure of Optical Character Recognition Model in Pytorch

### Assignment Description:
DigiNsure Inc. is an innovative insurance company focused on enhancing the efficiency of processing claims and customer service interactions. Their newest initiative is digitizing all historical insurance claim documents, which includes improving the labeling of some IDs scanned from paper documents and identifying them as primary or secondary IDs.

To help them in their effort, you'll be using multi-modal learning to train an Optical Character Recognition (OCR) model. To improve the classification, the model will use images of the scanned documents as input and their insurance type (home, life, auto, health, or other). Integrating different data modalities (such as image and text) enables the model to perform better in complex scenarios, helping to capture more nuanced information. The labels that the model will be trained to identify are of two types: a primary and a secondary ID, for each image-insurance type pair.

### Approach
Create OCR Model class with convultional layer, sequential layer, and classifier layer. The implementation is very basic; the goal is to understand creating pytorch model class.
