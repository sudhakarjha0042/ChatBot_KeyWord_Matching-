Description
-----------

This is a Django chatbot application that uses natural language processing to provide users with information about different types of headaches and their treatment according to Ayurveda. The chatbot recognizes specific words in the user's input and selects the appropriate response based on the given keywords. The application has three pages: `home`, `page`, and `input`.

-   `home`: This page displays a welcome message and an input field to start a conversation with the chatbot.

-   `page`: This page displays information about the different types of headaches and their treatment according to Ayurveda.

-   `input`: This page receives input from the user and returns a response from the chatbot.

### Prerequisites

-   Python 
-   Django

Dependencies
------------

-   Django: web framework for Python.

Getting started
---------------

1.  Clone the repository:

bashCopy code

`git clone https://github.com/sudhakarjha0042/ChatBot_KeyWord_Matching-.git`

1.  Install the dependencies:

Copy code

`pip install Django`
`pip install -r requirements.txt`

1.  Run the server:

Copy code

`python manage.py runserver`

1.  Open your web browser and navigate to `http://localhost:8000/` to start chatting with the bot.

Usage
-----

-   Start by typing a greeting, such as "hello," "hi," or "hey."

-   The chatbot will respond with a question, such as "How are you feeling today?" or "What kind of headache do you have?"

-   Respond to the chatbot's question with relevant information.

-   The chatbot will provide information on the appropriate treatment for the type of headache mentioned.