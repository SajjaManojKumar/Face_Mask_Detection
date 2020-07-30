###########################################################

Directory consists of the following:

data-----------+
|              | with_mask----+
|              |              | // All images with make.
|              |
|              | without_mask-+
|                             | // All images without mask.
|
face_detector--+
|              | // Face detector which is required.
|
model----------+
|              | // Your out put model will be stored here.
|
output---------+
|              | test_images--+
|              |              | // Output after testing.
|              |
|              | train_output-+
|                             | // Output after training.
|
test_images-----+
|              | // Inputs for testing.
|
detect_mask_image.py  // program to detect face-mask.
|
ReadMe.txt
|
train_model.py  // program to train your model.

###########################################################

****************To run detect_mask_image.py****************
First save image to be tested into test_images dir.
Go to cmd (command prompt) and navigate to main directory.
Then type the following command

python detect_mask_image.py -i test_images/image_name.extention

###########################################################

****************To run train_model.py****************
Go to cmd (command prompt) and navigate to this directory.
Then type the following command

python train_model.py -d dataset_path

###########################################################

Thanks to https://www.pyimagesearch.com/ for teaching me this project.