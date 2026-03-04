# Image Basics 10 Assignment

## Overview
In this assignment, you will be enhancing the code related to basic image manipulation techniques. By the end of this task, you’ll have a deeper understanding of how to manipulate images using Python.

## Learning Objectives  
- Implement image loading from a file.  
- Modify the image by applying a filter.  
- Save the modified image to a new file.

## Your Coding Environment  
You will be using Jupyter Notebook on StudySite.ai. Your interface includes:  
- **Editor Tabs**: Where you can edit your code cells.  
- **Run Button**: After editing your cells, use this button to execute the code.  
- **Commit Button**: Use this button to save your progress.  
- **Autograder Feedback**: View the success (✅) or failure (❌) of your implementation based on the tests provided.

## Workflow  
1. Edit the code as instructed below.  
2. Click the **Run Button** to see your changes in action.  
3. Click the **Commit Button** to save your work.  
4. Check the autograder for feedback on your implementation.

## Implementation Instructions  
1. **Load Image**:  
   Add the following code to load an image from a file named 'input_image.jpg':  
   ```python  
   from PIL import Image  
   image = Image.open('input_image.jpg')  
   ```  

2. **Apply Filter**:  
   After loading the image, apply a grayscale filter using:  
   ```python  
   gray_image = image.convert('L')  
   ```  

3. **Save Image**:  
   Finally, save the modified image as 'output_image.jpg':  
   ```python  
   gray_image.save('output_image.jpg')  
   ```  

## Example Usage  
Once implemented, running your notebook should load, modify, and save the image as intended. Make sure you have an image file named 'input_image.jpg' in the same directory.

## Hints & Tips  
- Ensure you have the Pillow library installed, as it’s required for image processing.  
- Check for typos or incorrect paths when loading or saving images.  
- Verify that 'output_image.jpg' is being saved in the expected directory.