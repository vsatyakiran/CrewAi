
<img width="388" alt="Screenshot-2024-01-16-at-12 30 59-PM" src="https://github.com/vsatyakiran/CrewAi/assets/103512987/2739a7ae-4790-417a-a803-65af98dc95de">

**Offincial Doc:** https://docs.crewai.com/

**Agents** _can interact with each other using crewAI's built-in delegation and communication mechanisms. This allows for dynamic task management and problem-solving within the crew._

`Tools:` CrewAI tools empower agents with capabilities ranging from web searching and data analysis to collaboration and delegating tasks among coworkers.

A tool in CrewAI is a skill or function that agents can utilize to perform various actions. This includes tools from the crewAI Toolkit and LangChain Tools, enabling everything from simple searches to complex interactions and effective teamwork among agents.

# Key Characteristics of Tools
***Utility:*** Crafted for tasks such as web searching, data analysis, content generation, and agent collaboration.
***Integration:*** Boosts agent capabilities by seamlessly integrating tools into their workflow.

This approach to AI, where multiple agents work together, is called `collaborative intelligence`. CrewAI provides the tools to  harness this collective power for tasks like:

* Building a smart assistant platform
* Creating an automated customer service system
* Developing a research team comprised of multiple AI agents 

`Note:` We can automate the several applications using the CrewAI tools, such as automatic customer service, research team, and smart assistant platform. 

To view the original content, please visit the [official documentation](https://docs.crewai.com/).

<hr>

# Code explanation

`Problem Statement:` Create the AI agents to which works together for writting the blog content about new job trends in the market.

`Solution:`

<img width="640" alt="1709344597095" src="https://github.com/vsatyakiran/CrewAi/assets/103512987/449600a3-3f63-4fba-bb59-402dbf9ace51">

* We can use the CrewAI tools to automate the process of writing the blog content. The agents can work together to search the web for the latest job trends, analyze the data, and generate the content for the blog.

* The required libraries need to be imported are alreadt written in the requirements.txt file. After importing the necessary libraries, we need to setup the environment by providing the API key. I have used GPT-4 to generate the content for the blog. The agents can work together to generate the content by using the CrewAI tools.

* We can also use local models insted of GPT for completing the task. In this case we need to setup the local model and provide the path of the model in the code. You can achieve this by using [Ollama ](https://ollama.com/) or [Hugging Face](https://huggingface.co/). 

* The agents can also collaborate with each other to delegate tasks and communicate effectively. This allows for dynamic task management and problem-solving within the crew. The agents can use the CrewAI tools to perform various actions such as web searching, data analysis, content generation, and agent collaboration.

* I will provide code snippets to demonstrate how to create local models and use them to generate content, in the next section.
  
<hr>

# Results 

![crewai](https://github.com/vsatyakiran/CrewAi/assets/103512987/9f3bab28-bc1a-42c2-b03a-ab7a071dfb39)


