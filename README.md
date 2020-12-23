# MLSec_Final_Project

The project can be run as follows :
As the clean_validation.h5 , clean_test_data.h5 , poisoned data files are too large to be uploaded on github , 
we suggest they be downloaded from  the following google drive : https://drive.google.com/drive/folders/13o2ybRJ1BkGUvfmQEeZqDo1kskyFywab.

Download the files and place the clean_validation_data.h5 , clean_test_data.h5 , anonymous_1_poisoned_data.h5 , sunglasses_poisoned_data.h5 files in the data folder along with the .ipynb file and badnet model weights. 

Place the contents of the Multi-Trigger-Multi-Target within the corresponding folder in data.

In order to obtain the final good net for a given badnet, go to cell 3 in the .ipynb file and change the Poison_data_filename, model_filename, and save_path_name. 
Then run all cells to have the good_nets weights saved in the corresponding "save path".

The final goodnet weights that we obtained can be found in the models folder
