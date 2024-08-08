<h1 style="display: flex; justify-content: space-between; align-items: center;">
    <span>Scientific Text Summarizer</span>
    <img src="https://github.com/user-attachments/assets/30168dc8-3dce-4756-9070-31ef0b4a95ac" alt="LangChain" style="width: 200px;"/>
    <img src="https://github.com/user-attachments/assets/8985f5fe-dbb5-4692-969e-6141d2721feb" alt="LangChain" style="width: 200px;"/>
</h1>

This summarizer generates short summaries of scientific articles from Google Scholar using the power of the affordable GPT-3.5-turbo.

# Requirements:

1- You will need an OpenAi API key to access the LLM model.

2- Install openai, LangChain and scholarly packages using 

    pip install openai scholarly langchain


3- To generate the summaries, run the code and enter your desired keywords (use ',' to separate the keywords). 

4- You can further increase the randomness in the summaries using the 'temperature' parameter.

5- The number of summaries for a set of keywords has been limited to 10; you can easily increase the number by changing the code. 
