<br />
<div align="center">
    <img src="images/logo.jpeg" alt="Logo" width="300" height="200">
  <h3 align="center">Neural Network for time series forecasting</h3>
    <a href="NeuroNauti/Report.pdf"><strong>Project Documentation</a>
</div>

## Neural Networks and Deep Learning 2023/24

This repository hosts a project developed as part of the *Artificial Neural Networks and Deep Learning* course at Politecnico di Milano. 

The project received a score of 10 out of 10 points and its summary description is provided below as well as links to the original Codalab challenge page.

Additionally, this repository includes the hidden datasets utilized for the final grading of the project to provide all the data necessary for understanding the approaches and the final evaluation of the work.
- *The data MUST be downloaded before running the notebook from the links provided in the data folder.*

## Project description

- **[Time Series Prediction](https://codalab.lisn.upsaclay.fr/competitions/16514)**: The objective was to predict future samples of multiple time series by designing and implementing a forecasting model. These models aimed to learn from past observations in the input sequences to accurately forecast future values. 

The task involved developing a model capable of predicting multiple uncorrelated time series while demonstrating strong generalization capabilities, this meant that the model needed to excel at forecasting across various contexts, without being restricted to a single or predefined time domain.

The project was implemented in Python utilizing the TensorFlow and Keras libraries, additional information can be found in the [report](NeuroNauti/Report.pdf) we submitted for evaluation or in the [notebook](NeuroNauti/Report.ipynb).

A final better version of the notebook was created after the challenge completion and is available [here](an2dl-ch2-complete.ipynb).

## Data structure

The Data for this project should be downloaded and extracted in the data folder from the following link:
- [full_ch2_data](https://www.beltrante.it/matteo/data2/data2.zip) (or from [Kaggle](https://www.kaggle.com/datasets/matteobeltrante/an2dl-ch2-data) if you are authorized)

The complete folder MUST have the following structure
    
    ├── this dir                        
        ├── data                            # Data dir
            ├── challenge                   # Challenge data dir 
                ├── training_data.npy       # Series data 
                ├── valid_periods.npy       # Series valid periods
                ├── categories.npy          # Series categories
            ├── public_test                 # Phase1 secret test data dir
                ├── history.npy             # Series data 
                ├── phase1.npy              # Series expected prediction
                ├── categories.npy          # Series categories
            ├── private_test                # Phase2 secret test data dir
                ├── history.npy             # Series data 
                ├── phase2.npy              # Series expected prediction
                ├── categories.npy          # Series categories

## Acknowledgments

The model in this directory has been developed by the *NeuroNauti* team, composed by:

* [Matteo Beltrante](https://github.com/Beltrante)
* [Lorenzo Rossi](https://github.com/lorossi)

In the context of the course [Artificial Neural Networks and Deep Learning](http://chrome.ws.dei.polimi.it/index.php?title=Artificial_Neural_Networks_and_Deep_Learning) at @PoliMi (Politecnico di Milano), AY2023/24.
