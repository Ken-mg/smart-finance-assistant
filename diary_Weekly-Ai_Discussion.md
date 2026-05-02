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

📓 Developer’s Diary – Week 10 Entry 1 👌 – Loading and editing main cell 

Context : I startded understanding and editing Foundation Data processing Functions cells 

Artifact : Screenshoot before changes were applicated 

<img width="558" height="312" alt="image" src="https://github.com/user-attachments/assets/88113b0a-8f01-4bed-bd9f-78bbe85e49ad" />

My Prompt 💰: Create a function to load CSV transaction data with Date, Amount, Category,
    Description columns. Handle dollar signs in Amount, missing values, and
    data validation. Include clear business-focused error messages." 

Result✅: Claude provide a clear function to load a csv Transaction data with Date , Amount , Category and Description collums . However , i realized that i can load the "sample_transaction.csv" files for all the cells to facilitate the work and avoid misunderstangin about data . 


Prompt 💰: To facilitate the work , is it possible to simply load and clead my sample_transaction.csv files instead of creating another one ? if so could you provide me a clear fonction about it ? 

Ai summary answer 🤖: Provide clearly a fonction to load and clead the transaction csv files 

Result ✅:
<img width="710" height="650" alt="image" src="https://github.com/user-attachments/assets/ead4f881-de2c-40e7-a5e9-cc8bb1c1a165" />


Entry 2 : Editing Spending Analysis function cells 

Prompt : Could you help me understand this cell first? Then I'd like you to create a function that would analyze the data , spending by category, calculate the percentages, identify the different spending areas, and generate actionable financial insights formatted for business presentations. Important note: Include category, percentage, and business insights. I already have a CSV file called transaction.csv, so it’s better to stick with that file. 

Ai Summary answer : Claude provided a clear explanation about the the requirement need for this cells . Provided a full function with all the requirement needed such as percentage calculation , spending areas and business insights .

Result ✅: The cell is neatly organized. During testing, all requirements were clearly specified, with additional elements such as icons to represent the progress bar as a percentage. 
<img width="519" height="185" alt="image" src="https://github.com/user-attachments/assets/37c9395e-0cec-497c-a894-155e2c6e8e8d" />

Reflection : I learned much more about how to use AI through the exercises I didn't understand, and I learned the importance of distinguishing between daily needs and other expenses. 

