# bots

## APPLICATIONS OF BOTS

1. customer service
2. e-commerce
3. 

## CHATBOT ARCHITECTURE

### COMPONENTS OF A CHATBOT

1. user interface 

Some examples of chatbot user interfaces:
- Messaging app chatbots (WhatsApp, Facebook Messenger,
Slack etc.)
- Text-based widgets on websites
- Voice assistants (Alexa, Siri, Google Assistant)
- Embodied chatbot avatars (human-like, cartoons, animals)

2. Natural language processing Engine 

3. Dialog Manager
This component determines the conversational flow and responses of the chatbot based on the extracted intents and
entities. The dialog manager contains:
- Domain-specific dialog rules and flows
- Trigger phrases that activate dialog nodes
- Mapping of intents to responses
- Integration with external APIs, databases, services

4. Knowledge Base
The knowledge base contains domain-specific data that allows the chatbot to have meaningful conversations:
- Frequently asked questions (FAQ)
- Product catalogs
- User manuals
- Factual information
- Task/process flows

This data is encoded in formats like documents, databases, JSON etc. that can be seamlessly accessed to respond to user queries. The knowledge base essentially contains the 'brain' of the chatbot.

5. Integration APIs
External APIs allow the chatbot to connect with backend systems and data sources to function effectively:
- Weather, maps, places APIs for location-based information
- Payment gateways for collecting payments
- Inventory databases for checking product availability
- Enterprise systems for customer account info
- IoT platforms to control devices or environments
Relevant data is pulled from integrated systems within the conversation flow through APIs and used to generate context-specific responses.

6. Reporting Database
The conversations between users and the chatbot need to be logged in a database to allow reporting and analytics.
Key information recorded:
- User inputs and bot responses
- Intents identified
- Entities extracted
- Dialog states
- Errors and failed conversations
Recording conversations helps identify areas for improving the chatbot's performance through additional training data, dialog tweaking and knowledge base expansion.

7. Admin Interface
A console that allows non-technical teams like business users, chatbot trainers etc. to manage the solution:
- Add/modify dialog flows
- Expand knowledge base
- Train natural language model
- Review conversations
- Monitor KPIs
- Enable new capabilities
This allows chatbots to be quickly improved without needing technical resources. Continuous modifications can be made based on real user conversations.

## CHATBOT DESIGN PATTERNS

1. rule-based chatbot
2. self-learning chatbots
3. conversational AI chatbots
4. Modular architecture

## CHATBOT PLATFORMS & FRAMEWORKS

### AWS LEX

- Managed chatbot service on AWS cloud
- Supports voice and text conversations
- NLU powered by deep learning 
- Integrates with AWS Lambda, AWS data sources
- Used to build Alexa skills

### GOOGLE DIALOGFLOW

- Develop conversational interfaces on Google Cloud
- Visual editor for dialog flow design
- Integrates with Contact Center AI for full CX stack
- Strong NLP capabilities with Machine Learning

### MICROSOFT BOT FRAMEWORK

- Framework for creating chatbots on Azure
- Support for .NET and Node runtimes
- Channels like Teams, Cortana integrated
- LUIS, QnA Maker for NLP capabilities
### IBM Watson Assistant

- Build and deploy conversational AI with Watson
- Conversation design tool
- Understands complex language patterns
- Integrates with business systems and IoT
### LivePerson

- Omnichannel conversational commerce platform
- Drag-and-drop conversation designer
- Powers millions of AI-assisted engagements
- Strong focus on CX and support use cases
### Pandorabots

- Cloud-based chatbot development platform
- Visual flow-based dialog editor
- Over 300K developers worldwide
- API access to tools and platform capabilities
### Chatfuel

- Leading messaging platform for Facebook chatbots
- Visual conversational interface builder
- Integrates with Facebook API for user data
- Caters mainly to marketing bots

