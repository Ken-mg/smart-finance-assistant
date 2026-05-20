
📓 Developer’s Diary – Week 8 Entry 1 : Loading and Inspecting Initial Set up Cell's 

Context : First of all , i was looking and inspecting every cell's of the starter notebook to see the content of the files . After inspecting every cell's i've decided to started working on that . 

Artifact: Screenshoot of Startup cell's .

<img width="909" height="474" alt="image" src="https://github.com/user-attachments/assets/41124465-cac1-4dbd-ba9c-11d716b8288f" />


Artifact : Screenshoot of AI Collaboration 

<img width="571" height="416" alt="image" src="https://github.com/user-attachments/assets/4b4669c2-da62-4371-9629-43852c91c930" />


<img width="579" height="793" alt="image" src="https://github.com/user-attachments/assets/e08e8fb1-1574-47e3-a13c-a81e7031564f" />



My Prompt📜: "Should i add something else in this cell's ? I know i just have to uncomment the line below , however i just want to make sure that nothing is missing on this cell's ."

AI Response Summary: Claude Ai gave a clear answer without adding any functions other than the one provided in the cells. 

My Critique/Improvement: I checked the cell's and confirmed that i just have to uncomment the line below to install libraries . 

Result 👌: Successfully installed hands-on-ai and loaded core libraries .

<img width="755" height="536" alt="image" src="https://github.com/user-attachments/assets/5a37874e-480a-4b18-a3b9-7ac9e8664f20" />


<img width="1708" height="500" alt="image" src="https://github.com/user-attachments/assets/b082e245-6d55-47eb-873d-1b3899f78c59" />



Reflection 🧠: In the beginning , i saw the comment above the pip install gradio pandas hand-on-ai line . However , i wasn't sure that by uncommenting the line it will worked proreply . In my head i was thinking the idea about adding aditional function or someting else . But Claude Ai confirmed that my cell's is already completed as is and the only step to do was to uncomment line . 

📓 Developer’s Diary – Week 8 Entry 2 : Hand's on Aai configuration 

Context : After installing hand-on-ai , i've decided to configure and set up H-O-A package for advanced features 

Artifact : Screenshoot of the cell's before editing it 

<img width="1013" height="471" alt="image" src="https://github.com/user-attachments/assets/8a099a07-a760-4a5f-9fc2-c243c84e743e" />

Artifact : screenshot of the cell launch 

<img width="901" height="435" alt="image" src="https://github.com/user-attachments/assets/92b53b98-dbe9-4a2b-9607-300b17409f65" />

<img width="1082" height="513" alt="image" src="https://github.com/user-attachments/assets/06619314-f476-4a4e-93ed-84a0a9c93ff5" />

Result ✅ : The cell is working properly, and the AI is configured correctly using the provided API key. 

📓 Developer’s Diary – Week 9 Entry 1 👌 – Loading and Inspecting Cells


Artifact : Screenshot of the different cells to be tested

<img width="760" height="455" alt="image" src="https://github.com/user-attachments/assets/68aab226-f463-4783-a609-a47b0a7d7308" />

Context : I ran the various “hands-on AI configuration & connection test” scenarios to see if the cells are working properly.

Artifact : Screenshoot of after launching connection test cell's  

<img width="750" height="580" alt="image" src="https://github.com/user-attachments/assets/ee3a7417-f982-4133-a6af-6907b9a49101" />


My prompt 📜: Could you explain the problem in this cell so I can understand why it isn't working?

<img width="582" height="378" alt="image" src="https://github.com/user-attachments/assets/6d248f57-1631-46c5-8d34-343b44404373" />

<img width="567" height="705" alt="image" src="https://github.com/user-attachments/assets/de859dfa-d869-4a47-9440-18284bd925a6" />



<img width="572" height="649" alt="image" src="https://github.com/user-attachments/assets/adb99103-cd9e-4dd9-bfc0-23c1a6aa38a4" />



Ai Response Summary : Explaining where is the issues and provides advice to encounter the issues without impacting other cell's .

Improvement : I saw a lot of contradiction on the cell's especually when it come to give a comment after launching the cell's . Indeed it say that "Hands-on-Ai connected sucessfully" however in the previous and following line it say " Response : Connection error " . To resolve that i ask Claude Ai the following prompt : 


<img width="496" height="434" alt="image" src="https://github.com/user-attachments/assets/438d66cb-f901-4122-ae3e-cb0096ed8659" />


Ai improvement : 

<img width="523" height="713" alt="image" src="https://github.com/user-attachments/assets/11710038-dd20-43ba-a99a-c4ff155eec9d" />

Ai response summary 👌: Claude AI directly made changes to the cell by resolving all previous inconsistencies. It provided a summary of the changes made to the cell as well as the various responses generated after the cell was launched. 

Result ✅ : Cell's was successfully running without previous contradiction .


<img width="764" height="688" alt="image" src="https://github.com/user-attachments/assets/dfb4181a-7f99-4543-ad43-cb04969dbbfb" />


Reflection :I learned that it wasn't just a matter of running a cell and asking artificial intelligence for a solution. It was also about understanding the various issues behind it. In fact, when I ran the program, I immediately saw the contradiction, knowing full well what I needed to fix in the cell. By guiding Claude correctly, I was able to see the importance of organizing the cells properly and identifying errors.


📓 Developer’s Diary – Week 9 Entry 2 👌 : Starting runnning and editing cell's programming

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

