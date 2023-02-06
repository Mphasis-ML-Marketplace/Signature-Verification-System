# Signature-Verification-System
This solution extracts closed region of signature  and validate it with original signature using Structural Similarity Index.

## Product Overview

This solution demonstrates an end-to-end signature verification system. The solution eliminates the need to manually verify the signature, reducing the occurrence of human error and fraud during the authentication process. It extracts the signature from the scanned input image and validate it with the original signature stored in the database. It then produces a confidence score based on Structural Similarity Index(SSIM) to indicate the signature’s level of authenticity. A SSIM score close to 1 indicates authentic pair of signatures. 

## Product Highlight 

* This solution implement neural networks to extract signature from the input image. The extracted signatures are then compared with the original signatures stored in the database using Structural Similarity Index(SSIM) to access the differences between the extracted signature and the reference signature  using a variety of known properties of the human visual system. The system will give a SSIM score between 0 to 1. A SSIM score close to 1 indicates that the two signatures are very similar while a SSIM score close to 0 indicates signatures are very different.   
* The solution accepts images in both .jpg as well as .png format and can extract signatures even if there are no contours present  to identify them. Currently, the solution will work on scanned images only.  
* Mphasis DeepInsights is a cloud-based cognitive computing platform that offers data extraction & predictive analytics capabilities. Need customized Machine Learning and Deep Learning solutions? Get in touch!

## Amazon Marketplace Link
The product can be found [here](https://aws.amazon.com/marketplace/pp/prodview-w7czyu3coxbke).
