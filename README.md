ChatBot Step-by-Step Guide

1. Setup
Clone Repository:

Clone the repository containing the ChatBot code from the source.
Install Dependencies:

Install the required dependencies using npm:
Copy code
npm install
Set Environment Variables:

Create a .env file in the root directory.
Define the following variables:
makefile
Copy code
MONGODB_URI=<Your MongoDB connection URI>
MONGODB_DATABASE=<Name of your MongoDB database>
OPENAI_API_KEY=<Your OpenAI API key>
2. Starting the ChatBot
Run ChatBot Program:

Start the ChatBot program by running:

Copy code
npm start
Connection to MongoDB:

The program will connect to MongoDB using the provided URI.
If the connection is successful, a message "Connected to MongoDB" will be displayed.
3. Topic Selection
Select Topic:
Upon startup, the ChatBot will prompt you to enter a topic you want to discuss.
Enter a topic of your choice when prompted.
Example: Enter "History" to discuss historical topics.
4. Chatting with the ChatBot
Engage in Conversation:

Once a topic is selected, you can engage in a conversation by entering questions or statements related to the chosen topic.
Example: Enter "What is the importance of studying history?"
Receive Responses:

The ChatBot will process your input and generate a response based on the selected topic.
Example: You will receive a response explaining the importance of studying history.
View Message History:

At any time during the conversation, you can type "chat history" to view the message history.
Example: Type "chat history" to see the history of messages exchanged.
Exit Conversation:

To end the conversation or change the topic, type "exit" at any time.
Example: Type "exit" to end the current conversation.
5. Error Handling
Graceful Error Handling:
Errors during MongoDB connection, OpenAI interaction, or general runtime errors are handled gracefully.
Example: If there is an error connecting to MongoDB, an informative error message will be displayed.
