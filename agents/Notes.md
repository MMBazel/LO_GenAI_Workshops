# Resources for Talk: Creating New Futures With Agents
Description: Fearing the agent-takeover? Learn how to make agents work for you in this fun introduction showing the strengths (& limitations) of agents.

Some recommended reading (and listening)

👇 The links to the referenced resources are below 👇

Note: ⭐ = Definitely should read for the course

---
## Slides
None for this talk, just readings and the take-home task to build an agent with RelevanceAI. 


---
## Pre-Reading
### What are agents? 
What we hope agents will do for us: 
* Video: [Silicon Valley Season 6 Gilfoyle's AI Chat Bot War](https://www.youtube.com/watch?v=IWIusSdn1e4)

#### Try building an agent
* [RelevanceAI](https://relevanceai.com/agents): try to build social copy to send out in an email using an OpenAI key

![Screenshot 2024-05-02 at 7 24 58 PM](https://github.com/MMBazel/LO_GenAI_Workshops/assets/3360070/9efbb81c-55d3-4d92-a221-bbafe3de10db)

* [Zapier](https://zapier.com/ai)


## Introduction to Agents
### Ingredients of agents
* Jim Fan - Nvidia: ["The moat of software AI agents is not the thin wrapper layer (Devin, SWE-Agent), but the underlying LLM."](https://www.linkedin.com/posts/drjimfan_the-moat-of-software-ai-agents-is-not-the-activity-7183871380742922242-0NE3/?utm_source=share&utm_medium=member_desktop)

![image](https://github.com/MMBazel/LO_GenAI_Workshops/assets/3360070/8a4fade8-52d1-446a-870b-80912674db36)

![image](https://github.com/MMBazel/LO_GenAI_Workshops/assets/3360070/68657039-247b-4fc1-8359-aa08aaec60eb)

![image](https://github.com/MMBazel/LO_GenAI_Workshops/assets/3360070/edf38e51-4fd6-44ff-bb54-7445c1375b18)

![image](https://github.com/MMBazel/LO_GenAI_Workshops/assets/3360070/e576aed7-307c-4f89-8dba-2e20c54f3ab1)


### LLM Agents 101
* Aishwarya Naresh Reganti 's ["LLM Agents 101"](https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/resources/agents_101_guide.md) 
![image](https://github.com/MMBazel/LO_GenAI_Workshops/assets/3360070/5caa13c6-2a7d-47fe-adc9-427ba5eef6c8)


## Technical Reading
### The agent framework landscape
* Eduardo Ordax on LinkedIn: [Characteristics & use cases](https://www.linkedin.com/posts/eordax_ai-genai-agent-activity-7188922479887736832-6rHM/?utm_source=share&utm_medium=member_desktop)
![image](https://github.com/MMBazel/LO_GenAI_Workshops/assets/3360070/ddd2800e-0536-4bd0-af2e-167962025a9d)

* Jerry Liu (Llamaindex) on [building agents](https://twitter.com/jerryjliu0/status/1784279431739265439?s=12)
  
![image](https://github.com/MMBazel/LO_GenAI_Workshops/assets/3360070/d9b075a4-51ec-4b19-8e25-d47fd60d2a2d)

> Here are the main ingredients for building an agent (mini 🧵)
> Query Planning: Given the task + surrounding context, decompose it into a series of steps (chain-of-thought, DAG, tree). Can be represented as a simple prompt call with structured outputs.
> Memory: Store state across user tasks, to better inform the next task. Important for any chatbot!
> Tool Use: Use the LLM to make API calls to any external system. This could be a vector db (through auto-retrieval). This could also be calling an external API (Slack, Gmail, Calendar) 

### The knitty-gritty of building & using agents
* Emerging AI Agent Architectures - presents a concise summary of emerging AI agent architectures; it focuses the discussion on capabilities like reasoning, planning, and tool calling which are all needed to build complex AI-powered agentic workflows and systems; the report includes current capabilities, limitations, insights, and ideas for future development of AI agent design. [The Landscape of Emerging AI Agent Architectures for Reasoning, Planning, and Tool Calling: A Survey](https://arxiv.org/abs/2404.11584)

* Along Blochman on [The TLDR on agentic workflows](https://www.linkedin.com/posts/alonbochman_aiagents-agenticai-workflowautomation-activity-7180915750147084288-KBzI/?utm_source=share&utm_medium=member_ios)

Andre Ng on
> Last week, I described four design patterns for AI agentic workflows that I believe will drive significant progress: Reflection, Tool use, Planning and Multi-agent collaboration. Instead of having an LLM generate its final output directly, an agentic workflow prompts the LLM multiple times, giving it opportunities to build step by step to higher-quality output. [LinkedIn](https://www.linkedin.com/posts/andrewyng_one-agent-for-many-worlds-cross-species-activity-7179159130325078016-_oXr/?utm_source=share&utm_medium=member_ios)

* [Will the prevalance of agentic workflows produce and refine higher-quality pre-training data?](https://www.linkedin.com/posts/andrewyng_apples-tiny-llms-amazon-rethinks-cashier-free-activity-7191823188215885825-blwT/?utm_source=share&utm_medium=member_desktop)
* [Agentic workflows](https://twitter.com/andrewyng/status/1770897666702233815?s=12)
* ["Multi-agent collaboration has emerged as a key AI agentic design pattern."](https://www.linkedin.com/posts/andrewyng_ai-agents-with-lowno-code-hallucinations-activity-7186771840034340864-14ug/?utm_source=share&utm_medium=member_desktop)
* ["Planning is a key agentic AI design pattern in which we use a large language model (LLM) to autonomously decide on what sequence of steps to execute to accomplish a larger task."](https://www.linkedin.com/posts/andrewyng_autonomous-coding-agents-instability-at-activity-7185372097127366658-8DMS/?utm_source=share&utm_medium=member_desktop)

### What sucks about building agents
* Li Yin on LinkedIn: ["Both AI research and engineering use Pytorch, but there is not a single shared library between the RAG and agent research and engineering communities."](https://www.linkedin.com/posts/li-yin-ai_both-ai-research-and-engineering-use-pytorch-activity-7189366364694892544-Uk1U/?utm_source=share&utm_medium=member_ios)

* Iason Gabriel from DeepMind [on the ethical implications of agents](https://www.linkedin.com/posts/iason-gabriel_what-are-the-ethical-and-societal-implications-activity-7187028824071581696-znVD/?utm_source=share&utm_medium=member_desktop)

## Examples: Agent-building projects
* Project: [Building an AI Agent With Memory Using MongoDB, Fireworks AI, and LangChain](https://www.mongodb.com/developer/products/atlas/agent-fireworksai-mongodb-langchain/)
* Project: [🎥 Llama 3 + CrewAI + Groq = Email AI Agent 🤖📧](https://www.linkedin.com/posts/samwitteveen_llama3-crewai-groq-email-ai-agent-activity-7188367604061736961-ygLo/?utm_source=share&utm_medium=member_ios)
* Project: [A Progressive Understanding Web Agent for Web Crawler Generation](https://twitter.com/arankomatsuzaki/status/1782227184410669417?s=12)
* Project: [Building a finance agent with Llamaindex](https://www.linkedin.com/posts/llamaindex_building-a-finance-agent-if-youre-looking-activity-7182842001321549825-afYb/?utm_source=share&utm_medium=member_desktop)
* Hackathon: [AI Agents Global Challenge](https://aiagentschallenge.com/)
* Project: [Demo of a game with GPT-4 agents! 🚀 Starlight Labs shows the next step in the Large Language Model world where it builds on the ideas shared in the paper.](https://www.linkedin.com/posts/sanyambhutani_demo-of-a-game-with-gpt-4-agents-remember-activity-7117122606222258176-NsUb/?utm_source=share&utm_medium=member_desktop)
* Project: [An indie hacker just jailbroke a Google Nest to run his own LLM agents and voice models.](https://www.linkedin.com/posts/eric-vyacheslav-156273169_this-is-the-future-an-indie-hacker-just-ugcPost-7090017332042891264-DRpV/?utm_source=share&utm_medium=member_ios)

### Cookbooks & Other Tools
* ["new LlamaIndex + Mistral AI Cookbook Series on RAG, routing, agents, function calling and more 🧑‍🍳 🧡" ](https://www.linkedin.com/posts/sophiamyang_love-the-new-llamaindex-mistral-ai-cookbook-activity-7182776358924693504-s85k/?utm_source=share&utm_medium=member_ios)
* [Vertex AI Agent builder from Google](https://www.linkedin.com/posts/paulroetzer_the-ai-show-episode-92-ai-reveals-at-google-activity-7186004839221395456-ezrq/?utm_source=share&utm_medium=member_ios)

## Other good reads
* [On-Premise ➡ Software-as-a-Service ➡ Service-as-Software 🤖? from DecibelVC](https://www.linkedin.com/posts/dan-nguyen-huu-11502719_a-new-frontier-service-as-software-powered-activity-7127682014169755649-lLgN/?utm_source=share&utm_medium=member_ios)
*  [MetaGPT paper is an absolute golden treat on how to effectively apply Large Language Model powered agents. It takes inspiration from how humans work in software industry and applies it to agents. ](https://www.linkedin.com/posts/sanyambhutani_a-masterpiece-on-using-llm-agents-metagpt-activity-7095385402106163201--mzJ/?utm_source=share&utm_medium=member_ios)
