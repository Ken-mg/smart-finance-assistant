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

.

📓 Developer’s Diary – Week 9 Entry 1 👌 – Loading and Inspecting Cells

Artifact : Screenshot of the different cells to be testedWeek 9  screenshoot ent 1
<img width="773" height="623" alt="Week 9  screenshoot ent 1" src="https://github.com/user-attachments/assets/e2b1c3ab-d56b-4960-9562-8dac2a3444ce" />

Context : I ran the various “hands-on AI configuration & connection test” scenarios to see if the cells are working properly.

Encounter Issues : One of the cells displays a “module not found” error

My prompt : Could you explain the problem in this cell so I can understand why it isn't working?

Ai Response Summary : Explaining where is the issues . Providing code to install hands-on-ai in Colab environment .

My Critique / Improvment : I added the function provided by Claude and confirmed that without the command !pip install hand-on-ai, the cell will always return the same error.

Result ✅ : Cell's was successfully load with the hand-on-ai installed .Week 9  screenshoot ent 1
<img width="937" height="792" alt="Week9 Ent1 aft" src="https://github.com/user-attachments/assets/b407dba0-d8b3-4601-94b6-96c149406962" />

Reflection : I learned how to install Hand-On-AI as part of the program. I also learned the importance of running the cells properly to verify that they work correctly and to identify and understand any issues that may arise.

Entry 2 👌 : Starting runnning and editing cell's programming

Context : I started reading and following the steps in the section: Building Processing Skills

Artifact : Screenshot before changes were made to the foundation cellWeek 9 ent 2 bfr
<img width="833" height="421" alt="Week 9 ent 2 bfr" src="https://github.com/user-attachments/assets/804bcea2-9d62-4115-97c1-d33d4a9a62bf" />

My prompt : Do you think it's better to load our old csv transaction files instead of creating a new sample ?

Ai Answer summury : Affirmed that using previous csv files was a pretty good idea . Provide python code .

Improvement : I added important pandas as pd functions and url to load the sample_transaction.csv files .

Result ✅: The cell's is proprely organised without adding or creating another sample data transaction . Using the sample transaction .csv files was a pretty good idea .Week9 ent 2 aft
<img width="692" height="560" alt="Week9 ent 2 aft" src="https://github.com/user-attachments/assets/58061b50-d9af-4e1c-81b5-cdc51f0a7bae" />

