# AI-first Onboarding Demo

I have to provide a demo on Cursor to my "AI-first" team. This team has data scientists, product managers and designers. The main focus of this team is to develop MVPs for agentic apps using AI-first principles in each role. The Cursor IDE will be a playground for everyone to experiment with vibe coding and develop prototypes following a number of templates we need to define as a group. I have already started to put together some material, e.g. hooks, agent modes, rules, etc. I would like to create a "Hellow-World" example that I can build step-by-step with the team so they get to know the different functions of Cursor as we code with the Cursor agent and end-to-end application. 

## Hellow-world demo requirements
- Python-based backend using LangGraph. Pre-built Supervisor with ReAct agent(s)   
- Python-based frontend using Streamlit chatbot. Plotly components if charts are needed 
- LangChain Azure ChatOpenAI llm client
- InMemorySaver chatbot memory
- uv package manager
- pytest testing
- Simple architecture with minimalistic code to showcase a first-principles approach.

## References
[LangGraph Python llm.txt](https://langchain-ai.github.io/langgraph/llms.txt)
[LangChain Python llm.txt](https://python.langchain.com/llms.txt?__hstc=5909356.43229fd0b27333cdeccf733c94c6efa1.1759919359671.1759919359671.1759919359671.1&__hssc=5909356.4.1759919359671&__hsfp=2836217097&_gl=1*gnafz*_gcl_au*MTAzMjkyNjU4NC4xNzU5OTE5MzU4*_ga*MTI1NDc4MDUxOS4xNzU5OTE5MzU5*_ga_47WX3HKKY2*czE3NTk5MTkzNTgkbzEkZzEkdDE3NTk5MjA1OTIkajYwJGwwJGgw)

# Instructions
Explore the current repo and give me some ideas of what this hellow-world could look like. As this is an onboarding tool I'd like to enphasize the use of Cursor for no-code profiles that need to understand how to set up the environment, what the project structure looks like, what is done in each step in code terms, how we checkpoint progress with git (locally for now, no remote). It doesn't need to be a python tutorial but I'd like to show the fundamentals.

1. Give me some ideas for a "Hello-World" demo case
2. Define a step-by-step script to follow the AI-coding process during the demo: 
    1. PRD definition: generate `plans/prd.md` for the "Hello-World" demo case.
    2. Planning: Use `modes/planning_mode.md` to come up with an implementation plan 
    3. Environment setup: create a `README.md` with instructions to set up the environment using a simple `requirements.txt` from scratch and verify that everything is ready for development and testing  
    4. Task execution with Agent including unit testing as per the `modes/implementation_mode.md` 
    5. Debugging (if needed) as per `modes/debugging_mode.md`
    6. Integration test testing 
