# Data Science Experiment Instructions - Draft 20240611-a


Please follow the steps below to download the necessary files from GitHub and upload them to the specified Google Drive folder.
There are three runs you will  need  to document. 

### Step 1 Download Files from GitHub

1. Open your web browser and go to the following GitHub repository links:

   Data Prep folder changes :
   - [data_prep_v3.ipynb](https://github.com/RudyMartin/dsai-2024/blob/main/rps-project-updates/data_collection/data_prep_v3.ipynb)
      use this for improved image cleanup
    - [test.zip](https://github.com/RudyMartin/dsai-2024/blob/main/rps-project-updates/data_collection/test.zip)
      to be used if/when student-generated images are not high quality or as base case
    - [train.zip](https://github.com/RudyMartin/dsai-2024/blob/main/rps-project-updates/data_collection/train.zip)
      to be used if/when student-generated images are not high quality or as base case
    - [rps_660pics.zip](https://github.com/RudyMartin/dsai-2024/blob/main/rps-project-updates/data_collection/rps_660pics.zip)
      we used this to show effect of more / better data in the later more advanced experimenting stages
    
    Template folder changes :
    - [2024_project_template_v4edit.ipynb](https://github.com/RudyMartin/dsai-2024/blob/main/rps-project-updates/templates/2024_project_template_v4edit.ipynb)
      use this to demo the process ONLY using your raw data - requires clean versions of the following two files
      (you will need to rename the older utility files before replacing them with these)
    - [dlutils.py](https://github.com/RudyMartin/dsai-2024/blob/main/rps-project-updates/templates/dlutils.py)
    - [kerutils.py](https://github.com/RudyMartin/dsai-2024/blob/main/rps-project-updates/templates/kerutils.py)



4. Download each file by clicking on the "Download" button or by right-clicking the file and selecting "Save Link As...".

### Step 2: Upload Files to Google Drive

1. Open your web browser and go to [Google Drive](https://drive.google.com/).

2. Navigate to the following directory in your Google Drive:

    ```
    dscamp/dscamp_public/project object recognition/2024 Rock Paper Scissors
    ```

3. Upload the downloaded files into the `2024 Rock Paper Scissors` folder they belong in - either templates or data collection. 

    - Click on the "New" button, then select "File upload".
    - Select `2024_project_template_v4edit.ipynb`, `dlutils.py`, and `kerutils.py` from your computer.
    - Do the same with the zip files `test.zip`, `train.zip`, and `rps_660pics.zip`
    - Confirm the uploads. If prompted to replace existing files, confirm the replacement.
    - Remember : Create an rps folder at the /content/gdrive/My Drive folder to hold images


### Step 3: Process Raw Initial Images and Establish Your Baseline Model
1. **Input**: Raw images created with `data_prep_v3.ipynb`
2. **Action**: Run the raw images  you create through the raw model using `2024_project_template_v4.ipynb`
3. **Output**: Use the output and results to adjust and select your testing/training images.
4. **Details**: 
    - Load the raw images into your environment. The new instructions are to create a separate folder for images.
    - Place your clean train images into `/content/gdrive/My Drive/rps/train`
    - Place your clean test images into `/content/gdrive/My Drive/rps/test`
    - Use the raw model to process these images using these locations.
    - Based on the model's output, adjust the images accordingly.
    - Save the adjusted images for the next step.

### Step 4: Process Adjusted Images with Baseline and then Get LLM Suggestions from Confusion Matrix and other data.
1. **Input**: Adjusted images.
2. **Action**: Run the adjusted images through the raw model using `2024_project_template_v4.ipynb`
3. **Output**: Take the output and request suggestions from the LLM model.
4. **Details**: 
    - Load the adjusted images into your environment.
    - Place your clean train images into `/content/gdrive/My Drive/rps/train`
    - Place your clean test images into `/content/gdrive/My Drive/rps/test`
    - Use the raw model to process these images.
    - Take the model's output and formulate a ChatGPT request to get suggestions for further adjustments or improvements.
    - Save the suggestions and outputs for the next step.
    - You will need to document suggestions, actions you took and experience of work with AI as a coding/teaching assistant.

    **Prompt Option 1**:
    ```
    I am a high school student at at data science summer camp working on a CNN model. Can I upload the confusion matrix to obtain options to enhance the model's performance? What else is need for a better evaluation?
    ```

    **Prompt Option 2**:
    ```
    Given the following outputs from classifying jpg images, what additional adjustments or modifications would you recommend to improve accuracy and performance? What are the preferred models for this using Google colab?
    ```

### Step 5: Create New Model Notebook using relevant LLM Chat-generated suggestions
1. **Input**: Adjusted your images, model architecture and processing to include LLM suggestions.
2. **Action**: Create a new model incorporating the hyperparameter suggestions and other changes.
3. **Output**: Final model with enhanced performance.
4. **Details**:
    - Categorize the adjusted data with the suggestions provided by the LLM.
    - Incorporate hyperparameter suggestions as advised by the LLM.
    - Train a new model using an enhanced dataset - possibly including the zip data to enhance comparisons.
    - Evaluate the performance of the new model and continue making further adjustments to improve performance if necessary.

---
### Step 6: Prepare Your Presentation for Project
See class instructor for clear instructions.
Don't forget to include a page highlighting the team and their respective roles
At least two of the team members should present
Suggested roles are: scrum master, coder and presentation designer.
Start the presentation creation process as soon as your team is assembled. This takes time too!


The more-resources folder also contains hints you might use:
Eexample using pre-trained model =  tf_transfer_learning_MobileNetV2.ipynb
Pytorch examples
CIFAR10 based tutorials for multi-class experiments – one student applied this to sign language
New camp video links to reinforce / introduce concepts – also added other data science resources on main readme
Fimally. there are examples of other presentations but make yours unique and informative. Tell a compelling story with data science.
