# Installation
Run below in terminal:
Clone this repository
```
git clone https://github.com/kaustubhsridhar/snorkel_tutorials_share.git
```
Create anaconda virtual environment using .yml file
```
cd snorkel_tutorials_share/
```
```
conda env create -f snorkel_env_spouse.yml -n snorkel_env
```
Activate virtual environment
```
conda activate snorkel_env
```

# Test Code
In the same terminal as above run the following:
```
jupyter notebook
```

Now navigate into spouse folder in jupyter GUI (which will open in your default web browser) and open "spouse_testing.ipynb"

Go to Kernel>Restart and Run All

Thats all!

# FYI

You can also navigate into visual_relation folder and open "visual_relation_testing.ipynb" and run all cells.
#### But, the second cell which downloads ~4 GB data of image, annotation data will take a little time (~15 to 20 mins)


