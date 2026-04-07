📓 Developer’s Diary – Week 8
Entry 1 – Loading and Inspecting CSV Data

Artifact: Screenshot of pandas loading the transaction CSV file showing df.head() output.

Context: I loaded a transaction dataset into my Smart Finance Assistant project using pandas.

My Prompt: "Help me load and display CSV transaction data using pandas"

AI Response Summary: Provided code using pd.read_csv() to load the file and df.head() to preview the dataset.

My Critique/Improvement: I checked the file path and confirmed the data was correctly loaded into a DataFrame.

Result: Successfully loaded the dataset and displayed the first rows of transactions.

Reflection: I learned how to import and inspect structured financial data using pandas. This is the first step in building a finance analysis tool.

Entry 2 – Understanding Data Structure and Cleaning

Artifact: Screenshot of df.info() showing data types before cleaning (Amount column as object).
<img width="539" height="531" alt="image" src="https://github.com/user-attachments/assets/4afaa8dd-a141-4f1a-b73b-cdc22db84414" />


Context: I analyzed the structure of the dataset to understand data types and identify issues before performing financial calculations.

My Prompt: "Why is my Amount column not numeric and how can I fix it?"

AI Response Summary: Explained that the Amount column contained currency symbols, so it was stored as text (object type), and needed cleaning before analysis.

My Critique/Improvement: I converted the Amount column from string to numeric format by removing currency symbols and converting it to float.

Result: The dataset was cleaned and ready for financial analysis (Amount column converted to numeric type).

Reflection: I learned that real-world financial data is often messy and must be cleaned before analysis. Proper data types are essential for correct calculations and insights.
