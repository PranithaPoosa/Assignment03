
----- 
> [Live Application link]<br>
> [Model 1](https://algodm-fall2023-team4-assignment02-streamlitmain-l1iq34.streamlit.app) <br>
> [Model 2](<>)) <br>
> [Model 3](https://algodm-fall2023-team4-assignment02-streamlitmain-l1iq34.streamlit.app) <br>
> [Codelab Slides](https://docs.google.com/document/d/1FCJP5iOxU3BNZ887LejyLGaVKoYz8_n02kPSXLtGNrs/edit?usp=sharing) <br>
> [Application Demo/Presentation](<>)

----- 
## Index
  - [Objective](#objective)
  - [Project Structure](#project-structure)
  - [How to run the applications](#how-to-run-the-application-locally)
----- 

## Objective
This application aims comprehensive guide to our innovative models and techniques designed to enhance visual search capabilities.
We used 3 different Visual Search Models to train data and based on certain key factors we are finding the images.<br>
The use cases are as follows: <br>
1. Neural Style Transfer for Image Search
2. Visual Search Models for Object Retrieval
3. Variational Autoencoder for Embedding Learning

## Project Structure
```
  ├── Neural Style Transfer for Image Search
  │    ├── Assets                          
  │        ├── Images
  │    ├── requirements.txt                  # relevant package requirements file
  │    ├── app.py                            # model1 streamlit application
  │    ├── model.py                          # model code
  │    └──  style_embeddings.pkl              # trained model pickle file 
  │── Visual Search Models for Object Retrieval
  │    ├──
  │    ├── requirements.txt
  │    └──  
  └── Variational Autoencoder for Embedding Learning
      ├── streamlitapp3.py                  # model3 streamlit application    
      ├── model3.py                         # model code
      ├── query-example-2.pdf               # query pdf        
      ├── model_vae.pkl                     # trained model pickle file 
      └── requirements.txt                  # relevant package requirements file      
```
## How to run the application
- Clone the repo to get all the source code on your machine

```bash
git clone https://github.com/AlgoDM-Fall2023-Team4/Assignment03.git
```
- All the code related to the streamlit is in the streamlit/ directory of the project

- First, create a virtual environment, activate and install all requirements from the requirements.txt file present
```bash
python -m venv <virtual_environment_name>
```
```bash
source <virtual_environment_name>/bin/activate
```
```bash
pip install -r <path_to_requirements.txt>
```
- Run the application

```bash
streamlit run streamlit/main.py
```
