# LearnTube by CareerNinja - Machine Learning Task

![image](https://github.com/prathameshparit/LearnTube_ML_Task/assets/63944541/b2edb047-76aa-44e2-9112-525488a37e55)

## Assignment: Replicate Typeform-like Chat Feature with Multiple Chat Agents for Data Gathering and Extraction

### Objective

This machine learning task is assigned by LearnTube, a platform by CareerNinja, to replicate a Typeform-like chat feature using machine learning techniques. The goal is to create an engaging and persuasive conversational experience for users to willingly share their personal details. Users may not answer correctly, may ask questions, or refuse to provide information until convinced about the reason. The chat agents take on the role of friendly persuaders, seeking to validate and gather information in a natural conversation. The gathered data is then extracted, verified, and saved into a CSV file.

### Project Structure

The project consists of the following components:

1. **Chat Agents**: Multiple chat agents are implemented, each with a specific role in the conversation. These agents include the "convincing to give details" agent, the "extract and verify user information" agent, and the "format the extracted information" agent.

2. **Conversation Flow**: The conversation flow is designed to guide users smoothly through the agents' questions. The agents aim to engage users, persuade them to provide information, and handle unrealistic or unhelpful responses.

3. **Details to Extract**: The following user details are extracted during the conversation:
   - Name
   - Email
   - Phone number
   - Address
   - Date of birth
   - Education

4. **Conversation Logic**: The conversation logic ensures that the chat flow is consistent and natural, minimizing hallucinations such as question repetitions or out-of-context questions.

5. **Language Model**: Large language models are used for chat agents, and parameters are tuned to achieve the desired conversational style and tone.

6. **CSV File Creation**: The gathered user details are formatted and saved into a CSV file using the pandas library in Python.

7. **REST API Endpoints (Optional)**: The project can be extended to include REST API endpoints, allowing it to be integrated into messaging systems and used for data collection via chat.

### Replicating the Chat Feature

To replicate the Typeform-like chat feature and run the project, follow these steps:

#### Colab File

1. Open the provided Jupyter Notebook file in Google Colab.

2. Run each cell in the notebook sequentially to set up the chat interface, conversation logic, and data extraction and formatting.

3. Engage with the chat agents via the notebook interface to collect user information.

4. After the conversation is completed, the gathered data will be formatted and saved into a CSV file named `user_info.csv`.

5. The notebook includes comments to explain each step and provide guidance for customization.

#### Additional/Optional Task: REST API Endpoints

If you want to extend the project to include REST API endpoints, follow these steps:

1. Modify the Python script to include Flask and Flask-ngrok for creating REST API endpoints.

2. Create REST API endpoints for chat interactions and data extraction.

3. Deploy the Flask app with ngrok to create a public URL for accessing the chat feature via messaging systems.

4. Share the public URL with users to engage with the chat agents and collect data.

### Conclusion

This machine learning task assigned by LearnTube by CareerNinja replicates a Typeform-like chat feature using machine learning techniques to collect user information in an engaging and persuasive manner. The gathered data is extracted, verified, and stored in a CSV file. You can choose to replicate and run the project using the provided GitHub repository or Colab file, and optionally extend it to include REST API endpoints for integration into messaging systems.
