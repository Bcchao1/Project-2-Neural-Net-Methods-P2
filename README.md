# Project-2-Neural-Net-Methods-P2


Image Style Transfer
Part2. Fast Style Transfer

For part two, we trained three style transfer models with Conan7882’s style transfer. After determining the weight values of the “style” and “content”, we plugged in our reference image for the styles. After commencing ‘py fast.py --train‘, the algorithm would train the newly generated model using the reference image and a generic image of a cat. 

The repo of the source code: https://github.com/conan7882/fast-style-transfer 

The github repo for part 2 is 


Example Output: [image available in project Google doc in submissions folder]



Instructions:

Install Necessary software and correct versions
Python 3.7.5
Nvidia CUDA
Tensor Flow
Tensor Flow CV
Set up
Open “fast.py” in visual studio
For training the model:
Adjust the style weight by tweaking the default value on line 38.
Adjust the content weight by tweaking the default value on line 40.
Change the default image name ‘x.jpg’ to the image you want to reference in the training. (Line 45)
For generating images
Load the correct style by referencing the index file on line 47. (e.g. ‘matrix_step_71’ )
Select the content image that you want to put through the style transfer by referencing the file name and location on line 49. (e.g. ../data/hawk.jpg’) 
Running the code
Open and direct CMD or Powershell to “experiment” in the project folder (e.g. X:/Winter2021/202/P2/Fast-style-transfer/experiment)
To Generate and Image
Enter:	‘py fast.py --generate_image’
The model will export to data/out/fast
To Train a new model
Enter:  ‘py fast.py --train’
The image will export to the data folder
Rules and Constraints: 

For training the model: 
The primary rule we manipulated was the main style image we reference in the model learning process. (e.g. 2 matrix themed, 1 food themed)
The primary constraint we manipulated was the style and content weighting of values for the learning model.
For generating images
The main rule included only entering pictures of birds to by stylized.
Constraints include the type of model/ image filtering we used to generate the new image.


Explain Process in creating a good output: 

We found that output images are more aesthetically pleasing when the input content image is composed of a subject (e.g. a bird) in the foreground with a contrasting background behind. Furthermore a style weight value of around “20” and a content weight of around “13” produces the best looking images, in our opinion. Such weighting values in the image generation allow for recognizable outputs while maintaining nice style transfers. 
