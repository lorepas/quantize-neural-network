# Quantize Neural Network with low bitwidth for weights, activations and gradients
![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)

In `train_log` folder there are all the files with the performances derived from the training. Among all the files there are the ones with accuracy performances. The file with such informations are named `stats.json` or are in the form `stat_other_names.json`. If there are both, keep in consideration the ones in this form `stat_other_names.json`.

The two .PNG images are the ones with the accuracy trend during the training among the 10 epochs that you can find in the report.

The files .CSV in the form `appr_name_file.csv` are the ones with the accuracy performances obtained from the deep-in study about the MNIST case. The other two .CSV files are the ones obtained by the overall study.

In the file `dorefa.ipynb` there are the utility function used in DoReFa. This file is useless because the functions needed are directly imported in each .ipynb files.

The files .ipybn starting with **appr** are the ones related to the deep-in study about the MNIST case. The other ones are related to the overall study. The name of the file is explanatory as to which network and dataset were used. The ones without numbers in the name means that uses the configuration with **1,2,4**.

The files `appr_mnist_performance.ipynb` and `performance.ipynb` are the ones from which we get the images and the csv files respectively of the deep-in study and of the overall study.

##Running

To run the script is needed to pre-install Tensorpack with `!pip install tensorpack` command. If you use Colab environment you need to mount Google Drive folder and to move in the folder where you want to execute the script. Pay attention, in case you change the name of the folder you must change all the path name in the files. 
