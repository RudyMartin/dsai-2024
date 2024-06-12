# Data Science Experiment Instructions - Draft 20240611-a

## Instructions to Download Files from GitHub and Upload to Google Drive

Please follow the steps below to download the necessary files from GitHub and upload them to the specified Google Drive folder:

### Step 1 Download Files from GitHub

1. Open your web browser and go to the following GitHub repository link:

    - [2024_project_template_v4.ipynb](https://github.com/RudyMartin/dsai-2024/blob/main/rps_files/2024_project_template_v4.ipynb)
    - [dlutils.py](https://github.com/RudyMartin/dsai-2024/blob/main/rps_files/dlutils.py)
    - [kerutils.py](https://github.com/RudyMartin/dsai-2024/blob/main/rps_files/kerutils.py)

2. Download each file by clicking on the "Download" button or by right-clicking the file and selecting "Save Link As...".

### Step 2: Upload Files to Google Drive

1. Open your web browser and go to [Google Drive](https://drive.google.com/).

2. Navigate to the following directory in your Google Drive:

    ```
    dscamp/dscamp_public/project object recognition/2024 raocck paper scissors
    ```

3. Upload the downloaded files into the `2024 Rock Paper Scissors` folder. 

    - Click on the "New" button, then select "File upload".
    - Select `2024_project_template_v4.ipynb`, `dlutils.py`, and `kerutils.py` from your computer.
    - Confirm the upload. If prompted to replace existing files, confirm the replacement.


### Step 3: Process Raw Images and Adjust
1. **Input**: Raw images.
2. **Action**: Run the raw images through the raw model.
3. **Output**: Use the output to adjust the images.
4. **Details**: 
    - Load the raw images into your environment.
    - Use the raw model to process these images.
    - Based on the model's output, adjust the images accordingly.
    - Save the adjusted images for the next step.

### Step 4: Process Adjusted Images and Get LLM Suggestions
1. **Input**: Adjusted images.
2. **Action**: Run the adjusted images through the raw model again.
3. **Output**: Take the output and request suggestions from the LLM model.
4. **Details**: 
    - Load the adjusted images into your environment.
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

### Step 5: Create New Model with Adjusted Data and LLM Suggestions
1. **Input**: Adjusted data and LLM suggestions.
2. **Action**: Create a new model incorporating the hyperparameter suggestions.
3. **Output**: Final model with enhanced performance.
4. **Details**:
    - Combine the adjusted data with the suggestions provided by the LLM.
    - Incorporate hyperparameter suggestions as advised by the LLM.
    - Train a new model using this enhanced dataset.
    - Evaluate the performance of the new model and make further adjustments if necessary.

---

This structure provides clear instructions for each step of your experiment, ensuring that all actions and inputs/outputs are well-defined.



