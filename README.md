Fake News Detection using LSTM
This project aims to classify news articles as either fake or real using LSTM (Long Short-Term Memory) neural networks.
Steps to Run the Project:
1.	Download the Datasets:
•	Download the datasets Fake.csv and True.csv.
2.	Open the Project Notebook:
•	Download the project file CS354_PROJECT.ipynb and open the notebook in Google Colab.
3.	Upload Datasets:
•	Upload the downloaded datasets (Fake.csv and True.csv) to your Google Colab environment.
4.	Execute the Code:
•	Run all cells in the notebook. This can be done by clicking on the "Run All" button.
5.	Copy Text for Testing:
•	Once the code execution is complete, copy a text snippet from either the title or text column of Fake.csv or True.csv. This will be used to test the model's classification.
6.	Testing the Model:
•	Paste the copied text snippet into the input_text variable in the last snippet of code in the notebook and Run the cell to see the predicted label (fake or real) for the provided text.

If any line in the input text gives an EOF inside string error during reading of dataset, it indicates a parsing issue in the dataset (Fake.csv or True.csv).
To resolve this error, remove the problematic line from the dataset before retesting.




