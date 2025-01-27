# Personal-AI-Agent
This code in langchain and langgraph is a personalized AI Agent that can help you in your tasks


This Notebook has the Agetnic AI workflow whihc can perform several tasks such as:
1. `Enhancer`: Use prompt enhancer as the first preference, to Focuse on clarifying vague or incomplete user queries, improving their quality, and ensuring they are well-defined before further processing.
2. `Researcher`: Specializes in gathering information.
3. `research_paper_node`: this node helps to gather information about a research paper.
4. `Coder`: Handles technical tasks related to caluclation, coding, data analysis, and problem-solving, ensuring the correct implementation of solutions.
5. `Email Summariser`: this nod is responsible to get emails of the user and summarise them.
6. `document_create_node`: this node on its on do  research based on specific informations and then create an docs and give user the link

The Main `Supervisor Node` here is reponsible to delegate task to lower nodes based on user queries.

![alt text](https://github.com/AbbasMakasarwala-786/personal-AI-Agent/blob/main/model.png?raw=true)

  
After cloning this repository 
run the requirements.txt file using:`pip install -r requirements.txt`

Then go to https://console.cloud.google.com/ and create two api's:
1. Create Creadentials for OAuth2.0 --> Enable Gmail API and add the contents of gmails API to credentials.json file
2. Create Credentials for services --> Enable Google Docs and Google Drive API'S download the contents and add to services.json file

Finally Add your Groq API key from https://groq.com/ and add it to your `.env' file 

After this you will be ready to Automate your Personal Work
