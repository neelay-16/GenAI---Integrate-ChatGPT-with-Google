# GenAI---Integrate-ChatGPT-with-Google

# Preview

https://github.com/neelay-16/GenAI---Integrate-ChatGPT-with-Google/assets/135517502/5484500e-fba0-42b7-829c-d6f7681250e6


# Description

This code imports the os module, which is used for interacting with the operating system. It then sets an environment variable named 'SERPAPI_API_KEY' to a value stored in the variable myserpkey.

![image](https://github.com/neelay-16/GenAI---Integrate-ChatGPT-with-Google/assets/135517502/1ceabcbd-f611-49b2-9ba2-2a05144096d0)

This line imports the OpenAI class from the llms module within the langchain library.

![image](https://github.com/neelay-16/GenAI---Integrate-ChatGPT-with-Google/assets/135517502/c9627b57-dabf-41ba-8b1b-1e5a9ef2a11c)


Initializing an OpenAI Language Model (GPT-3):
Here, we create an instance of the OpenAI class, specifying the model as "text-davinci-003." We set the temperature parameter to 1, which controls the randomness of the model's output. We also provide an OpenAI API key stored in the my_key variable.

![image](https://github.com/neelay-16/GenAI---Integrate-ChatGPT-with-Google/assets/135517502/d59d7391-0505-419e-82be-1fd7c28a0f0f)

This line imports the load_tools function from the agents module within the langchain library. It is needed for some language processing tools.

![image](https://github.com/neelay-16/GenAI---Integrate-ChatGPT-with-Google/assets/135517502/a77a8534-cb42-4b1e-ac06-e5757a2ab58d)

We use the load_tools function to load a language processing tool named "serpapi." This tool is related to searching for information using the Google SerpApi service.

![image](https://github.com/neelay-16/GenAI---Integrate-ChatGPT-with-Google/assets/135517502/387ebbd3-bd4e-45e4-a674-8ba7ebe56e66)

This line imports the AgentType class from the agents module within the langchain library. AgentType appears to define different types of language agents.

![image](https://github.com/neelay-16/GenAI---Integrate-ChatGPT-with-Google/assets/135517502/4906893b-d70f-4f3a-bb32-5bd607730888)

Here, we use the initialize_agent function to create an agent named mygooglechain. This agent is configured with:
1. llm: The OpenAI language model (myllm) you initialized earlier.
2. tools: The language processing tools, including "serpapi," loaded into myserptool.
3. agent: The type of agent you want to create.

![image](https://github.com/neelay-16/GenAI---Integrate-ChatGPT-with-Google/assets/135517502/daf7a11b-35b4-4115-9bf0-55b2cd0bd606)


Finally, we use the run method of the mygooglechain agent to perform some language processing task on the input text "Satyaprem ki Katha."

![image](https://github.com/neelay-16/GenAI---Integrate-ChatGPT-with-Google/assets/135517502/601d0295-2369-4bd7-8243-5428d4e164d9)









