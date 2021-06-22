Final work of Image Processing (SCC0251) of the Computer Science course at USP São Carlos.  

Bruna Magrini da Cruz  
Gabriel Francischini de Souza  
Julia Carolina Frare Peixoto    
Marcus Vinicius Medeiros Pará    

# Skin Detection in Face Images

## Definition and Objective

In Skin Detection, the aim is to find skin tone pixels and regions in an image or a video. This process is usually used to detect regions with human faces or limbs on images, to be then be analyzed by a skin classifier (that will tell if the pixel is a skin or nonskill pixel) and human presence or recognition on videos.

With this brief definition in mind, <ins>this project goal is to detect a person's skin in an image that contains a face and return an image with just the skin.</ins>
We are not considering aspects of segmentation (faces covered by a mask), recognition (defaced faces by distortions) or any kind of lossy data. So any skin detected with these obstacles on the face will be just a gain for the main objective. It is worth to mention that we are using the CelebA dataset and in this dataset every image contains only one face, so multiple faces is not something we are dealing with. We are also using OpenCV library.

On the instructions below it is described how we collected the images from the dataset and the step-by-step on how to detect the skin:

## Input images

The application input is images of faces. 

The source of the images is the CelebFaces Attributes Dataset (CelebA). CelebA is a large-scale face attributes dataset with more than 200K celebrity images, each with 40 attribute annotations. 

The images in this dataset cover large pose variations and background clutter. CelebA has large diversities, large quantities, and rich annotations, including:
- 10,177 number of identities;
- 202,599 number of face images;
- 5 landmark locations, 40 binary attributes annotations per image.

The complete list of facial attributes provided by CelebA is:
![Complete list of facial attributes provided by CelebA](./images/dataset/CelebA-FacialAttributes.png)

Some examples of CelebA images are:
![CelebA images examples](./images/dataset/Example.png)

More information about CelebA can be found on: https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html and https://www.kaggle.com/jessicali9530/celeba-dataset/version/2.

## Steps

## First results
