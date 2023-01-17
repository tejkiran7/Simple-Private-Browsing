# Private-Browsing-Application
I just tried building a simple PRIVATE BROWSING APPLICATION using ChatGPT in python. I came to know recently about ChatGPT. So, I was just curious to know more about ChatGPT like what it does, how it will help the developers to become more productivity in their work. 

**About ChatGPT:**
ChatGPT is an AI-powered chatbot developed by the Artificial Intelligence (AI) research company OpenAI. The chatbot uses a field of machine learning known as natural language processing (NLP) to generate responses to users' questions and prompts. As defined by ChatGPT- "Its 'AI is trained on a dataset of internet text and is able to generate human-like text in response to prompts. It can be used for a variety of natural language processing tasks such as language translation, text summarization, and question answering." 
It was trained using Reinforcement Learning from Human Feedback (RLHF), using the same methods as InstructGPT, but with slight differences in the data collection setup. 

**About Private Browsing Application:**
When you search the web in a private mode, your browser won't store a history of the sites you've visited, videos you've watched or online forums you’ve posted to. The private browser also won't store any cookies – codes that track the sites you've visited – or remember any usernames or passwords that you've entered during your online session.
So,this application resembles a very tiny copy of Google's incognito mode, where we can do our private browsing. This application which will prevent the browser from saving any cookies or caching any data.

**Small Glance about the code:**
Created a PyQt5 application with a QWebEngineView as the central widget of the main window. It creates a back and forward button, connect them to the appropriate webview functions, and add them to a toolbar. To add private browsing mode, ChatGPT uses the QWebEngineProfile class to create a new profile for the browser. This profile can then be used to enable or disable private browsing mode. For this mode it added a private browsing button and a QWebEngineProfile for private browsing. The private_profile is set with QWebEngineProfile.NoPersistentCookies and QWebEngineProfile.MemoryHttpCache settings, which will prevent the browser from saving any cookies or caching any data. It also added a function toggle_private_browsing which is connected to the private_button, this function will check if the current page profile is private_profile or not, if it's private_profile then it will switch to normal browsing mode else it will switch to private browsing mode. The setUrl() and load() functions are used to set and load the default URL. Finally, set some properties for the main window and start the application.




