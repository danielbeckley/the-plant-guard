Code Execution Steps

Dataset url - https://www.kaggle.com/datasets/sadmansakibmahi/plant-disease-expert/data

Follow up from our last discussion - https://dev.azure.com.mcas.ms/Dbeckley6774/INFO8665%20-%20Projects%20in%20Machine%20Learning%20(Plantify)/_workitems/edit/105

Not sure if you can access the azure link, here is a screenshot - 
https://asset.cloudinary.com/dk0k3povu/0871e322515f5057f30627593386a560


# **Main Steps**
1. **Install Python**: Ensure that Python is installed on your system. You can download the latest version of Python from the official Python website.

2. **Clone the project**: Clone the project repository from a version control system like Git. Use the following command in your terminal:
    ```
    git clone https://github.com/nathekame/plantify-app.git
    ```

    If you are not cloning the project from github and just unzipping it, then you can skip the above step.

3. **Navigate to the project directory**: Use the `cd` command to navigate to the project directory:
    ```
    cd plantify-app
    ```

4. **Create a virtual environment**: It is recommended to create a virtual environment to isolate project dependencies. Run the following command to create a virtual environment:
    ```
    python -m venv plantify-env
    ```

5. **Activate the virtual environment**: Activate the virtual environment using the appropriate command for your operating system:
    - For Windows:
      ```
      .\env\Scripts\activate
      ```
    - For macOS/Linux:
      ```
      source env/bin/activate
      ```

6. **Install project dependencies**: Install the required dependencies by running the following command:
    ```
    pip install -r requirements.txt
    ```

7. **Run the project**: You can run any of the notebook files in the project to see it in action.
    You will be prompted to select a kernel. In the python environments, you can select
    ```
    plantify-env
    ```

8. You can navigate to the eda folder where you find two sets of notebook files

    ```
    cd eda
    ```
    - EDA 
    ```
    plant_id_eda.ipynb
    ```
    and 
     ```
    plant_disease_id_eda.ipynb
    ```