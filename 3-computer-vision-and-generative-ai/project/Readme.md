# AI Photo Editing with Inpainting

## Project Introduction
In this class, we have seen how generative models can be used in computer vision. We have also learned how to use the Segment Anything Model (SAM) to select subjects in images by providing points and other inputs. 

Let's put this knowledge to good use by building something interesting and fun! 

With our app, we will be able to swap out the background of an image and substitute it with a computer-generated one described through text. For example, an image of a cat can be modified by removing it and placing a crocodile in its place, using the segmentation capabilities of SAM.

## Project Summary
In this project, we are going to build a little app that allows you to select a subject and then change its background, or keep the background and change the subject. 

The process involves:
1. The user uploading an image and selecting the main object by clicking on it.
2. Activating the Segment Anything Model (SAM) to create a mask around the selected object, choosing the most accurate mask generated.
3. The user is shown this result to either accept it or refine the mask further with additional points.
4. Once the mask is finalized, the user provides a text description (and possibly a negative prompt) to specify a new background for the selected object.
5. An infill model then creates this new background, and the final image is displayed.

Optionally, the user can choose to invert the mask and substitute the subject while keeping the background. This app can be used to swap backgrounds, swap subjects, remove objects, and more!

You will be writing the code that powers the main functionality of the app: calling the SAM model and processing its output, as well as using a text-to-image diffusion model to generate the new background or subject.

## Project Instructions
When you start the workspace, you will land in a Jupyter notebook. Follow the instructions contained there step by step, being on the lookout for sections marked by `YOUR CODE HERE`.

The Gradio app that allows for the interactive experience showcased above is already built for you. You will be able to start it from within the notebook. Then, by clicking on a link, you will be taken to a new tab with the Gradio UI available for use.

After completing the code, spend some time playing around in the app. Try to modify the parameters like the Classifier-Free Guidance Scale or the random seed, and see which results you get.

## App Instructions
Once you have completed the exercise, the notebook will generate an app to use the functions you wrote in an interactive way. 

## Project Environment
The environment to fully run the project is already set up for you. It has pre-installed a series of dependencies, including PyTorch, Diffusers, and Gradio.

## Workspace Instructions
Start the workspace and activate the GPU usage. Then follow the instructions contained in the notebook.

If for any reason you run into trouble, you can:
- Restart the notebook and try again. In most cases, this solves the problem.
- Refresh the workspace by using the menu in the lower-left corner and select 'Refresh Workspace'. This will re-deploy your work on a new machine. You won't be losing any progress, but you will have to run the cells from the beginning of the notebook.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- OpenAI for providing the language model.
- Udacity for the course and resources.
