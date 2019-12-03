# Deep-Neural-Style-Transfer
The system uses neural representations to separate and recombine content and style of arbitrary images, providing a deep neural algorithm for the creation of artistic images.

# Data-Files
Download  imagenet-vgg-verydeep-16.mat pretrained network from http://www.vlfeat.org/matconvnet/models/imagenet-vgg-verydeep-16.mat

# Running
Run the main file using commmand :
* python main.py -c_i changed_content.jpg -s_i changed_style.jpg -c_w 25 -s_w 25 -n_i 1000

# Arguments
* c_i: Name of Content image. It must be string. Example: changed_content.jpg, default_content.jpg , content_image.png
* s_i: Name of Style image. It must be string. Example: changed_style.jpg , default_style.jpg , style_image.png .
* c_w: Weight of Content image in loss function. It must be integer. Example: 5 , 20 , 50 
* s_w: Weight of Style image in loss function. It must be integer. Example: 10 , 20 , 40
* n_i: How many iterations to train. It must be integer. Example: 500 , 1000 , 2000
