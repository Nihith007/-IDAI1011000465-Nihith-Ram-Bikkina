# IDAI1011000465-Nihith-Ram-Bikkina

Candidate Name - Nihith Ram Bikkina
Candidate Registration Number -1000465
CRS Name: Artificial Intelligence
Course Name - AI-Based Smart Solutions: Designing Chatbots for Real-World Challenges
School name - Birla Open Minds International School, Kollur

The Smart Campus Assistant is an AI-powered chatbot developed using Google Dialogflow to help students, teachers, and visitors navigate and access campus information easily.
It provides quick answers about room locations, event venues, campus facilities, and general details, acting as a virtual guide for anyone on campus.

This project demonstrates the real-world application of Artificial Intelligence by designing a conversational assistant that is responsive, efficient, and user-friendly.

List and Explanation of Intents
Intent Name	Purpose / Description
* Default Welcome Intent - Greets users and introduces the campus assistant.
* Hi - Responds to greetings and starts a friendly conversation.
* Role_intent - Identifies if the user is a student, teacher, or visitor to provide personalized responses.
* DesiredLocationforevent - Helps users find the venue of a specific event.
* Roomname - Provides directions or information about campus rooms and facilities.
* Map - Shares navigation details or directs users to campus areas.
* Queries - Handles general questions about campus events and activities.
* Campus Facilities_Yes - Confirms that the user wants to see the facilities the campus offers.
* Campus Facilities_No - 	Understands the user doesn't want to see the facilities and moves on with the next intent.
* Phone Number - Provides contact details for departments or campus offices.
* Good Feedback - Thanks the user for positive feedback.
* Bad Feedback - Responds politely to negative feedback or improvement suggestions.
* Bye - Ends the conversation courteously.
* End - Closes the chat session completely.
* Default Fallback Intent - Triggered when the chatbot doesn’t recognize a user’s message.

List and Explanation of Entities
Entity Name	Function / Example
* Feedback - Detects user sentiment and categorizes feedback as positive or negative. (e.g., “⭐️⭐️⭐️⭐️⭐️” → positive, “⭐️⭐️” → negative)
* Event Name - Identifies school events such as Annual Day, Science Fest, MUN, Sports Meet, or Cultural Fest.
* Roles - Recognizes the user’s role (student, teacher, or visitor) to personalize information and responses.
* Rooms - Detects room or area names like Library, Music Room, Lunchroom, Teachers' Room, Gym roof, or Restroom.


Integration Details

Platform Used: Google Dialogflow ES

Agent Setup:
* 15+ intents and 4 entities configured.
* Slot filling used for roles, rooms, and event names.
* Contexts applied for multi-turn conversations.

Rich Responses:
* Uses text messages, quick replies, and suggestion chips.

Integrations:
* Dialogflow Messenger – for embedding in a website or portal.
* GitHub – for project storage and documentation.


Deployment Instructions

* Create Agent in Dialogflow
* Go to Dialogflow Console
* Create a new agent named Smart Campus Assistant.

Add Intents and Entities
* Create all main intents and entities listed above.
* Use slot-filling to collect event names or room details from the user.

Configure Responses
* Add short, helpful responses for each intent.
* Include fallback messages for unmatched queries.

Test the Chatbot
Try queries like:
* “Where is the science event conducted?”
* “When is Annual Day?”
* “I’m a teacher, where is the staff room?”

Integrate & Deploy
* Enable Dialogflow Messenger Integration.
* Copy the embed code to your website or project page.

Publish the Bot
* Test one final time and share the live chatbot link.


Please click the link below to access my Campus Assistant chatbot: 

https://nihith007.github.io/-IDAI1011000465-Nihith-Ram-Bikkina/
