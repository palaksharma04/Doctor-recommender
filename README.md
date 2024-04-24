**Medical Diagnosis and Doctor Recommendation System**

**Introduction**

This project is designed to assist in medical diagnosis based on symptoms provided by the patient and recommend appropriate doctors according to the predicted disease. It leverages machine learning models to predict diseases based on symptoms and recommends doctors specialized in treating those diseases. The system provides a user-friendly interface for inputting patient information and symptoms and displays the predicted disease along with recommended doctors.

**Features**

Patient Information Input: Collects essential patient information including age, gender, symptoms, cholesterol level, blood pressure, and city of residence.

Disease Prediction: Utilizes machine learning algorithms such as Logistic Regression, Support Vector Machines (SVM), Decision Trees, and Random Forests to predict diseases based on the provided symptoms and patient information.

Doctor Recommendation: Recommends doctors specializing in the predicted disease based on the patient's location and the doctor's specialty and availability.

Graphical User Interface (GUI): Provides an intuitive GUI for easy interaction with the system, allowing users to input information and view results effortlessly.

**Technologies Used**

Python: Programming language used for the backend logic and algorithms.
Libraries:
pandas: Data manipulation and analysis.
numpy: Mathematical operations and array manipulation.
matplotlib: Data visualization.
seaborn: Statistical data visualization.
tkinter: GUI toolkit for building the user interface.
Machine Learning:
scikit-learn: Python library for machine learning tasks such as classification and regression.

**How to install and run the project**

Install Python: You can download and install Python from the official website: Python Downloads. Choose the appropriate version for your operating system (Windows, macOS, or Linux) and follow the installation instructions.

Install Required Python Packages: Open a terminal or command prompt and use pip, the Python package manager, to install the required packages. 

Run the following command: pip install pandas numpy matplotlib seaborn scikit-learn

Install Anaconda: You can download and install Anaconda from the official website.

Open Jupyter Notebook: Once Anaconda is installed, you can launch Jupyter Notebook by opening the Anaconda Navigator and clicking on the Jupyter Notebook icon. This will open a web browser with the Jupyter Notebook interface.

Install all files from the Github repo in your personal computer.

Navigate to Your Notebook: Use the file browser within Jupyter Notebook to navigate to the directory where your final.ipynb file is located.

Open the Notebook: Click on the final.ipynb file to open it in Jupyter Notebook.

Execute Cells: You can execute the code cells in the notebook one by one by selecting each cell and pressing Shift + Enter. Alternatively, you can run all cells by clicking on "Cell" in the menu bar and selecting "Run All".

Enter Patient Information: Fill in the required patient information including age, gender, symptoms, cholesterol level, blood pressure, and city in the provided fields.

Submit Information: Click the "Submit" button to process the information.

View Results: The system will display the predicted disease and recommend doctors based on the predicted disease and the patient's location.

**Dataset**

Dataset: The project utilizes a dataset (data.csv) containing symptoms and corresponding diseases for training the machine learning models.
Doctor Data
Doctor Information: Doctor data is stored in a separate CSV file (dr_mock_dataset.csv) containing details such as doctors' names, specialties, availability, ratings, and locations.

**Contributions**

Contributions to the project are welcomed! If you have any suggestions for improvements, bug fixes, or additional features, feel free to open an issue or submit a pull request.

**License**

This project is licensed under the MIT License.
