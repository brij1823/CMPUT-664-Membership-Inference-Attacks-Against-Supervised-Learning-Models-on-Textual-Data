# CMPUT-664-Membership-Inference-Attacks-Against-Supervised-Learning-Models-on-Numeric-Data

## Environment Setup
To setup all the necessary files and libraries which will be required, we have setup a requirements.txt file.

To install the essential libraries, use the following command:
```
pip install -r ./requirements.txt
```

## Database Setup

For this project we have used 3 datasets which can be downloaded in ```./Dataset``` folder. The three datasets which are being used are : 
- [Adult Income Dataset ](https://github.com/brij1823/CMPUT-664-Membership-Inference-Attacks-Against-Supervised-Learning-Models-on-Textual-Data/tree/main/Dataset/adult%20census)
- [ Heart Disease](https://github.com/brij1823/CMPUT-664-Membership-Inference-Attacks-Against-Supervised-Learning-Models-on-Textual-Data/tree/main/Dataset/Heart%20Disease)
- [Pima Diabetes](https://github.com/brij1823/CMPUT-664-Membership-Inference-Attacks-Against-Supervised-Learning-Models-on-Textual-Data/tree/main/Dataset/Pima%20Diabetes)

## Methodology

### Step 1: Synthetic Data Generation

To generate the synthetic data, run the ```./Code/Synthetic Data/Synthetic Dataset.ipynb``` using the following command

``` python -m ./Code/Synthetic Data/ Synthetic Dataset.ipynb```


### Step 2: Overfit Model Generation
The next step is to generate the overfitted model on the original dataset, the code used for that is available in ```./Code/Overfitted Models/overfitted_model.ipynb```, to run the python notebook use the following command:
```
python -m ./Code/Synthetic Data/overfitted_model.ipynb
```

### Step 3 : Shadow Model Generation
Once the synthetic dataset and overfit model is complete, to generate the shadow models, run the ```./Code/Shadow Models/.Shadow_Attack_{Dataset}```, to run the python notebook use the following command :

```
python -m ./Code/Shadow Models/Shadow_Attack{Dataset}.ipynb
```

## Evaluation


