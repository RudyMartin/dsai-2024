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
    - [rps_360pics.zip](https://github.com/RudyMartin/dsai-2024/blob/main/rps-project-updates/data_collection/rps_360pics.zip)
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
    - Select `2024_project_template_v4.ipynb`, `dlutils.py`, and `kerutils.py` from your computer.
    - Do the same with the zip files `test.zip`, `train.zip`, and `rps_360pics.zip`
    - Confirm the uploads. If prompted to replace existing files, confirm the replacement.


### Step 3: Process Raw Initial Images and Establish Your Baseline Model
1. **Input**: Raw images created with `data_prep_v2.ipynb`
2. **Action**: Run the raw images through the raw model using `2024_project_template_v4.ipynb`
3. **Output**: Use the output to adjust the images.
4. **Details**: 
    - Load the raw images into your environment. The new instructions are to create a separate folder for images.
    - Place your clean train images into `/content/gdrive/My Drive/rps/train`
    - Place your clean test images into `/content/gdrive/My Drive/rps/test`
    - Use the raw model to process these images using these locations.
    - Based on the model's output, adjust the images accordingly.
    - Save the adjusted images for the next step.

### Step 4: Process Adjusted Images with Baseline and then Get LLM Suggestions from Confusion Matrix and other data.
1. **Input**: Adjusted images.
2. **Action**: Run the adjusted images through the raw model again.
3. **Output**: Take the output and request suggestions from the LLM model.
4. **Details**: 
    - Load the adjusted images into your environment.
    - Place your clean train images into `/content/gdrive/My Drive/rps/train`
    - Place your clean test images into `/content/gdrive/My Drive/rps/test`
    - Use the raw model to process these images.
    - Take the model's output and formulate a request for the LLM model to get suggestions for further adjustments or improvements.
    - Save the suggestions and outputs for the next step.

    **Prompt Option 1**:
    ```
    Here are the outputs from a raw model processing a set of adjusted images. Can you suggest further adjustments or improvements to enhance the model's performance?
    ```

    **Prompt Option 2**:
    ```
    Given the following outputs from processing adjusted images with a raw model, what additional adjustments or modifications would you recommend to improve accuracy and performance?
    ```

### Step 5: Create New Model with Adjusted Images Data and relevant LLM Suggestions
1. **Input**: Adjusted data and LLM suggestions.
2. **Action**: Create a new model incorporating the hyperparameter suggestions.
3. **Output**: Final model with enhanced performance.
4. **Details**:
    - Combine the adjusted data with the suggestions provided by the LLM.
    - Incorporate hyperparameter suggestions as advised by the LLM.
    - Train a new model using this enhanced dataset.
    - Evaluate the performance of the new model and make further adjustments if necessary.

---
### Step 6: Prepare Your Presentation for Project


This page aims to provide clear instructions for each step of your experiment, ensuring that all actions and inputs/outputs are well-defined.

Copies of student final presentations
Additional python data detective challenge (find out why the stats are against the house on a guessing game)
Exercises and Answers for StatsSnap, TempTrack and Score_Predictor python coding challenges
rps_files – files to update project template and utilities. See directions in readme for the folder.
Updated data_prep_v2 – one that deals with colab name conflict issue and will not lose files.

TeamX_CNN_Models.ipynb – this was the base case template (student data / common code). Used to compare results generated by different data sets.
base_2024_project_template_v5.ipynb – this was the template we had students use as a starting point for their experiments.
More python for the advanced ones
Comparison of tensorflow vs pytorch approaches for cnn models
 i.      pt_train_rps_cnn_models.ipynb (version 2 has more evaluation charts)
ii.      tf_train_rps_cnn_models.ipynb

example using pre-trained model =  tf_transfer_learning_MobileNetV2.ipynb
CIFAR10 based tutorials for multi-class experiments – one student applied this to sign language
New camp video links to reinforce / introduce concepts – also added other data science resources on main readme
Printout into csv of confusion matrix that was used to inform ChatGPT of model performance and use it for assistance for more improvements or options.
For some students, this was the third time through the materials so it was important to cover a wider range of materials to keep them interested too.

