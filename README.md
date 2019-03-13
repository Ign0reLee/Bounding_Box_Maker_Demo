# How to Use it Bounding_Box_Maker_Demo

# NOTE

I wanted to create my own data for object detection, but I created this code because it was difficult to find code or programs that support these features.

I know this will inevitably cause some problems, but I will keep this code public. I have decided to write some notes on this.

This code is incredibly simple and inconvenient because it is quickly created by the student you are learning.

Rather than trying to get a sense of how perfect the code is, we've created it to get the functionality we need in a simple step.

Therefore, we will continue to update these sections in the future. If you have a need or an inconvenience, please suggest it with your ID. I would appreciate that.

# Enviroment

python 3.6.7

opencv-python 3.4.3.18

jupyter 1.0.0

notebook 5.6.0

numpy 1.15.2

# Install Requirement

pip install jupyter

pip install opencv-python

pip install tkinter

pip install numpy


# How to use it

Run on jupyter notebook

python -m notebook --notebook-dir [Your Path]

If you can run, you can look two button, named fileload and quit

File load : load your data image and you can see your data display

Quit : end this program

All data save as your Path/data/data’s parents folder/data’s folder/data’s name.txt
If you want to change your save folder, look inside code and change parents_filenames and child_filenames

After loading the file, if you have confirmed that the image is displayed on the screen, set the mouse to the end point from the desired starting point.

Clicking the left mouse button on the image will become the starting point of the rectangle.

While holding down the button, scroll to the desired point and release the button.

 Now you can should see a blank text box on the Jupyter notebook screen.

In the text box, enter the label of the part you have set and press Enter

You should now see a red square on top of the image.

Repeat the above steps as many times as you like.

Finally, If you want to save and exit, press the ESC key.

# Precautions

Once set, the rectangle can not be erased. Please work again from the beginning or subtract the square at the saved file.

Since the rectangle follows the Opencv style, you should always set it from left to right down.

It's not a definite bug yet, but if you often go out of the way too edge , squares can bounce in image.
