# QA FAQ Bot: Streamlining Answers with AQAC

# Intro
This chatbot is designed to assist university employees and students by addressing their questions regarding report templates, instructions, and various other services.

To train our RASA model, we gathered our information independently using the Jordan University Quality Assurance website. We identified the information that users are most likely to seek on the website or would need to call the Quality Assurance department to obtain. The data we collected includes the main topics that users might need assistance with, and potential ways users might phrase their queries when speaking to a real person. This ensures that our chatbot can effectively understand and respond to user inquiries by simulating real-world interactions and addressing the most relevant and frequently asked questions. Additionally, we collected sample queries by simulating potential user questions based on the information available on the website. For example, for the intent InformationFormForParticipantsInMandatoryCourses, we identified various ways users might ask about information forms for participants in mandatory courses, such as نمذج المعلومات للمشاركين" " بالدورات الإلزاميةand "أسماء المشاركين بالدورات الالزامية".

The chatbot is designed with a well-defined framework comprising 57 intents, 57 stories, and 57 utters, ensuring a wide range of user queries can be addressed effectively. The domain file, integral to the chatbot’s operation, contains 235 lines of code, while the natural language understanding (NLU) file includes 676 lines, facilitating precise intent recognition and entity extraction. The stories file, which maps out user interactions, spans 284 lines. In total, the chatbot’s codebase amounts to 1195 lines. These performance measures highlight the chatbot’s extensive capabilities and the meticulous effort invested in its development, enabling it to handle diverse and complex user interactions with ease.

# GitHub Files Description
All the files were created automatically when the RASA project was initialized. Only three files were used to program our chatbot:
- NLU File (nlu.yml) : The nlu.yml file contains training examples for the bot to understand user intents.
- Stories File (stories.yml) : The stories.yml file defines the conversation flow.
- Domain File (domain.yml) : The domain.yml file defines the bot's responses, intents, and actions.  
- QA_chatbot_document.pdf : full documentation and information about how to run our chatbot  

# Team Members
- Leen Samman
- Layan Balbisi
- Beesan Alattal
- Besan Musallam
- Zaina Abunasser
