# The 

## Short summary
The 

## Aims and objectives

The 


## People 

**Nayomi Kasthuri Arachchi** : 
**Alex Butterworth**
**Felix Needham-Simpson**




## Data
The project employed the datasets below:
#### The Electrical Age 
Digitised and OCR captured version of the first two volumes of the historical magazine/journal The Electrical Age. This was provided to the Congruence Engine Project by the archives of the Institute of Engineering & Technology.

#### Images of domestic appliances from department store catalogues (archive.org)
Historical catalogues of department stores were identified on archive.org. Relevant pages and images were then downloaded from the sources.

#### Images of domestic appliances from Science Museum Group archives
The Science Museum Group archives include a large collection of trade literature produced by companies that were involved in the manufacturing of domestic appliances. The companies that frequently advertised in The Electrical Age were identified in this collection, and the relevant images of domestic appliances in these collections were photographed. 


## Method

We have been examining the usefulness of the Visual Geometry Group’s Image Classification Engine for the purposes of detecting domestic appliances in ads found in historical journal and magazines. Visual Geometry Group's (VGG) Visual Image Classification Engine (VIC Engine) is an image classification engine that trains Support Vector Machine (SVM) classifier on-the-fly, using a set of given training images, either as files or fetched online via e.g. Google images. VGG's key objective in developing VIC was a sustainable approach in the face of growing size of datasets and the data annotation needs that it implies.

The initial tests were carried out via the following method:
1a) Images of domestic appliances were identified in The Electrical Age. Two versions of these images were prepared: one where the ads were cropped out from among the text, and one where the entire page was present.
1b) Additional images of domestic appliances for comparative tests were identified in the following magazines and journals:  Life, Good Housekeeping, The Woman Engineer. Additional images were collected from the Science Museum Group online collections. 
2) Where needed, the relevant images of advertisements were cropped from the digitised full-page that they were featured on.
3) Using this dataset of images, an initial test was carried out to assess the performance of the VIC Engine without having to carry out any additional training. Two different training models were tested: rcnn resnet 2 and ssdmobilenetv2.
4) We then undertake a manual visual comparison of the identifications produced.

## Key initial findings
1)	The initial tests showed that objects were identified with higher accuracy on images featuring no texts and illustrations in colour. Objects were also identified with higher accuracy in more contemporary images. 







## Licence 
This work is licensed under a [Creative Commons Attribution 4.0 License - CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
