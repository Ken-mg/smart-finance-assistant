📓 Developer’s Diary – Week 8
Entry 1 – Loading and Inspecting CSV Data

Context: I loaded a transaction dataset into my Smart Finance Assistant project using pandas.

Artifact: Screenshot of pandas loading the transaction CSV file showing df.head() output.


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




📓 Developer’s Diary – Week 9 Entry 1 👌 – Loading and Inspecting Cells


Artifact : Screenshot of the different cells to be tested

<img width="773" height="623" alt="Week 9  screenshoot ent 1" src="https://github.com/user-attachments/assets/e2b1c3ab-d56b-4960-9562-8dac2a3444ce" />

Context : I ran the various “hands-on AI configuration & connection test” scenarios to see if the cells are working properly.

Encounter Issues : One of the cells displays a “module not found” error

My prompt : Could you explain the problem in this cell so I can understand why it isn't working?

Ai Response Summary : Explaining where is the issues . Providing code to install hands-on-ai in Colab environment .

My Critique / Improvment : I added the function provided by Claude and confirmed that without the command !pip install hand-on-ai, the cell will always return the same error.

Result ✅ : Cell's was successfully load with the hand-on-ai installed .

<img width="937" height="792" alt="Week9 Ent1 aft" src="https://github.com/user-attachments/assets/b407dba0-d8b3-4601-94b6-96c149406962" />

Reflection : I learned how to install Hand-On-AI as part of the program. I also learned the importance of running the cells properly to verify that they work correctly and to identify and understand any issues that may arise.



Entry 2 👌 : Starting runnning and editing cell's programming

Context : I started reading and following the steps in the section: Building Processing Skills

Artifact : Screenshot before changes were made to the foundation cell

<img width="833" height="421" alt="Week 9 ent 2 bfr" src="https://github.com/user-attachments/assets/804bcea2-9d62-4115-97c1-d33d4a9a62bf" />

My prompt : In this cell i've tried to input and loand my csv file and indeed it worked . However when after save and closing everything , my csv files disappeard even if i have it into a folder on google collab . Can you advice me how to correct it and make it work ? 

Artifact : Screenshoot of Ai Collaboration  


<img width="582" height="949" alt="image" src="https://github.com/user-attachments/assets/bf021e7d-e3d4-4937-8883-71e7e5dd853d" />


Ai Answer summury : First of all , Claude AI gaves solution regarding loading files issues with a step & a sample that should be followed to load my csv files on the cell's  .

Improvement : However even after providing clear step and solution about it , i think that loading csv files by using a github url is way more better and easier for the work . Therefore i asked Claude what he think about it and indeed he agreed that using url methods was way much easier solution . Also , Claude provided step to load the csv files by using url methods 

Artifact : Screenshoot of Ai Discussion , improvement section 


<img width="564" height="935" alt="image" src="https://github.com/user-attachments/assets/a20b3de1-69c6-4e3e-b04c-c6366d7213cf" />


Result ✅: The cell's is proprely organised without adding or creating another sample data transaction . Using the sample transaction .csv files was a pretty good idea .


<img width="692" height="560" alt="Week9 ent 2 aft" src="https://github.com/user-attachments/assets/58061b50-d9af-4e1c-81b5-cdc51f0a7bae" />


Reflection : When i was looking through the prompt gaves on the cell , i've start firstly to understood how can i collaborate with ai to make this cell's work . Then i saw that it wasn't mandatory to create a realistic template but loading one was completly enough . Then when i asked Claude Ai , i knew that loading a cell's with url was easier for me but also saves a quit of time of work and make the understanding easier . Moreover , even if that claude AI gave a solution that could worked , i think that using a github url was better that using google drive methods becausee it's shorter , faster and also have less step to do to access this files . Therefore i've told to myself that sometimes even if AI can be helpfull , human intervention - reflection and thinking will make the work way better than just asking a solution to a tools . 


📓 Developer’s Diary – Week 10 Entry 1 👌 – Loading and editing main cell 

Context : I startded understanding and editing Foundation Data processing Functions cells 

Artifact : Screenshoot before changes were applicated 

<img width="558" height="312" alt="image" src="https://github.com/user-attachments/assets/88113b0a-8f01-4bed-bd9f-78bbe85e49ad" />

My Prompt 💰:  " 


Ai summary answer 🤖: Provide clearly a fonction to load and clead the transaction csv files 


Result✅: 

<img width="710" height="650" alt="image" src="https://github.com/user-attachments/assets/ead4f881-de2c-40e7-a5e9-cc8bb1c1a165" />


Entry 2 : Editing Spending Analysis function cells 

Artifact : Screenshoot before editing cell's with AI Collaboration 

<img width="662" height="402" alt="image" src="https://github.com/user-attachments/assets/97dab42d-ce8f-4256-90e5-7200fc081deb" />



Prompt : Could you help me understand this cell first? Then I'd like you to create a function that would analyze the data , spending by category, calculate the percentages, identify the different spending areas, and generate actionable financial insights formatted for business presentations. Important note: Include category, percentage, and business insights. I already have a CSV file called transaction.csv, so it’s better to stick with that file. 

Ai Summary answer : Claude provided a clear explanation about the the requirement need for this cells . Provided a full function with all the requirement needed such as percentage calculation , spending areas and business insights .

<img width="1352" height="740" alt="image" src="https://github.com/user-attachments/assets/d87ac5c8-fd29-4c0c-9246-3308134698a5" />
<img width="1451" height="1013" alt="image" src="https://github.com/user-attachments/assets/61a8f8f9-0ffa-4492-ae71-b53be42ba603" />

Result ✅: The cell is neatly organized. During testing, all requirements were clearly specified, with additional elements such as icons to represent the progress bar as a percentage. 

Artifact : Screenshoot of the Cell's with AI Collaboration 

<img width="519" height="185" alt="image" src="https://github.com/user-attachments/assets/37c9395e-0cec-497c-a894-155e2c6e8e8d" />

Reflection : I learned much more about how to use AI through the exercises I didn't understand, and I learned the importance of distinguishing between daily needs and other expenses. 

Developer Diary  - Week 11 Entry 1 : Hands on ai configuration 

Context : After examining and launching cells functions , hands on ai always had issues with the configuration and can't get it to be recognized in the cell. According to Blackboard , i've tried to follow the hand.on.ai installation as well as adding the new Api Key . 

Artifact : Screenshoot of Hand-on-Ai Configuration Cells 

<img width="357" height="212" alt="image" src="https://github.com/user-attachments/assets/05823c70-a8ad-4450-ba4c-8395ff9cd5dc" />

Artifact of Connection Test : 

<img width="366" height="498" alt="image" src="https://github.com/user-attachments/assets/ba91b7cc-6e66-4546-b88f-d91ebfe19310" />

Prompt used : "Could you explain why my test connection cells  still not working even after drag and drop the correct function provided by Kevin on Blackboard . Here is the codeline given : from hands_on_ai.chat import get_response
# Test the connection to the hands-on-ai server
try:
    response = get_response("Hello! I'm building a Smart Finance Assistant.")
    print("✅ Hands-on-AI connection successful!")
    print(f"Response: {response}")
except Exception as e:
    print(f"❌ Connection issue: {e}")
    print("You can still work on the data processing foundation without this.")" 


AI Answer Summary : 
Claude provided clear explanation about connnection issuees . Give advice about it such as mailing Keving with some exact information. 

Result :

Entry 2 : Editing Foundation Data Processing Functions 

Context : After installing Hand-On-Ai and trying to make it work , I continued to modify the remaining cells. In addition to making changes especially the foundation data processing functions cells . More over , I tried to understand how they work. 

AI Prompt used : Based on spending analysis data . Create a professional financial recommendation . Include specific savings opportunities , spending pattern , obsevation and actionable advice formated for a personal finance app user . 

Result : Claude provided clear and proper result everything asked so far ( Savings oopportunities , spending pattern observations and actionable advice with top category ) . Organized cell correctly without issues . 

Artifact : Testing the cell's after asking changement with ai collaboration 

