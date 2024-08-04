## Rock-Paper-Scissors Project

The goal of this project is to train a neural network to recognize different hand gestures in the game of rock-paper-scissors. The students are encouraged to create their own data for this project and use it for training and performance assessment.

Cosider this  an experiment   and  document how changes in data inputs or model processes affect outcomes. That's your presentation story.

### Instructions:

1. **Browse and Learn the Project Files:**
The datasets  used include many 480x640x3 color images, divided into three categories: scissors, rock, and paper. Don't worry if it seems overwhelming at first. There are zip backup files with larger sets of images that you will also be using to make comparisons. 

The MVPS documents contain the Camp Project Folder: `Camp-Rock-Paper-Scissors`. 

Its sub-folders and main files are:
  - `data_prep` ... `data_prep_v3_from_student_pics.ipynb`  , `data_prep_v3_from_zip.ipynb`  
  - `model_init` ... `baseline_2024_project_template.ipynb`
  - `model_tune` ... `tuned_2024_project_template.ipynb
  - `rps`... will contain images you create

2. **Prepare Image Dataset:**
  - in `data_prep` ... open `data_prep_v3_from_zip.ipynb` and create images
  - In the project 'rps' folder, you will find a 'test' folder, as well as 'train' and 'model' folders. 
  - Save a backup of the collected data (either as a zip file or a folder) in `/content/gdrive/My Drive/dsai-2024/MVPS/Camp-Rock-Paper-Scissors/rps.zip`  or somewhere safe. Safety first.

3. **Create Initial Baseline Model:**
  - Use the rps pictures you took to create an initial baseline model.     
  - In `model_init` ... open `baseline_2024_project_template.ipynb`
  - Save the file with your team number.

4. **Swap Out Images:**
Training and testing pre-made datasets (rps.zip, rps_60.zip, and rps_360.zip) are used for comparing data quality before model tuning. Pick one.
    
  - in `data_prep` ... open `data_prep_v3_from_zip.ipynb` ... change `rps_dir = os.path.join(proj_dir, 'the  set  you  pick')`
  - in `model_init` ... open `baseline_2024_project_template.ipynb`... change `rps_dir = os.path.join(proj_dir, 'the  set  you  pick')`
  - CAREFUL :  Do not overwrite  your oeiginal rps images, just repoint to using a different dataset.
  - Save the file with your team number and also note which "rps set" you used.


5. **Tune and Optimize:**
Adjust and optimize the model based on whichever dataset you think performs best. 
  - Use the `tuned_2024_project_template`. Save your models along the experiment journey  to document your progress.

The project is aimed to be covered in 4 half-day modules:
- **Data Collection**: 1 module.
- **Model fitting and presentation prep**: 2 modules.
- **Students present their results**: 1 module.

Each module is accompanied by a short lecture covering the necessary theoretical background of the task. For lecture materials, please refer to [Session Materials/Tutorials](https://github.com/RudyMartin/dsai-2024/tree/main/MVPS/Session-Materials/Tutorials) folder.

