# WineQualityPrediction
This is the end to end Machine learning project based on Wine Quality Prediction

1. create a python file called "template.py" file in order to develop the file and folder using the structure.

2. create a virtual environment:

    ```
    conda create -n mlproj python=3.8 -y
    ```

    To activate the conda environment:
    ```
    conda activate mlproj
    ```
3. create 'requirements.txt' file to automatically install all the packages and the installation can be done by below commands:

    ```
    pip install -r requirements.txt
    ```

4. create a setup.py file 

5. In Jupyter notebook, The Experiments have been performed. 

6. why to use yaml file:

    ```
    When some functions are used frequently, so instead of using it components again and again we can make 'util'.
    ```

7. Update the Common.py file 

8. #### Workflows
    ```
        1. update config.yaml
        2. update schema.yaml
        3. update params.yaml
        4. update the entity 
        5. update the configuration manager in src config (jupyter notebook)
        6. update the components
        7. update the pipeline
        8. update the main.py
        9. update the app.py
    ```
    Each component should follow the same above workflow

    schema.yaml have been used to validate the data.

8. created an UI app in order to predict:

    ```
    python app.py
    ```

    ```bash
    Now open up your local host 0.0.0.0:8080
    ```

