# Resources for Mini-Workshop: Crash Course Open Source Models

In the mini-workshop we covered a couple different tutorials, tools and resources as an introduction to working with open-source LLMs. 

👇 The links to the referenced resources are below 👇

## Slides & Talk
* Slides should be in this repo but backup slides will also be posted to LinkedIn
* For the talk video, check with Tine &/or Rex. 

## Notebooks & Tutorial Materials 

### Using TinyLlama Chat
* Chatting with TinyLlama/TinyLlama-1.1B-Chat-v1.0 on Huggingface: https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0

### Fine-Tuning: Creating a Taylor Swift fine-tuned model 
There are two notebooks (exact same project): 
* [[Mini]_HelloTaylorSwift_FineTuning.ipynb](https://github.com/MMBazel/LO_GenAI_Workshops/blob/main/oss-models/%5BMini%5D_HelloTaylorSwift_FineTuning.ipynb) - This is the minimal amount of code need to fine-tune a tinyllama model on Taylor Swift lyrics.
* [[Explainer]_HelloTaylorSwift_FineTuning.ipynb](https://github.com/MMBazel/LO_GenAI_Workshops/blob/main/oss-models/%5BExplainer%5D_HelloTaylorSwift_FineTuning.ipynb) - This is the explainer notebook; it has a lot more unnecessary code (like print statements), is peppered with explanations about each code block. At the end I also offer some suggestions for how to extend the notebook.

There are some requirements that need to be met to work, namely that you need:
1. Need a [Huggingface account](https://huggingface.co/)
2. Need a [Google Colab account](https://colab.research.google.com/).

In both cases, having a Pro subscription is super helpful (and well-worth it) especially if your lcoal computer isn't powerful enough to fine-tune (although I picked TinyLlama specifically because of the size). 

With that being said, it shouldn't be required. 

* [Huggingface Pro](https://huggingface.co/pricing)
* [Colab Pro](https://colab.research.google.com/signup)

![Screenshot 2024-04-11 at 4 12 15 PM](https://github.com/MMBazel/LO_GenAI_Workshops/assets/3360070/3eeae395-f5a5-4dc5-80a6-36be727d0db2)

![Screenshot 2024-04-11 at 4 13 26 PM](https://github.com/MMBazel/LO_GenAI_Workshops/assets/3360070/741b0644-ef9c-4bcc-8aa7-8ef088a15b6a)

#### Additional Links



### RAG 
There are two notebooks/spaces that I showed and which offer a great introduction to using RAG (both of which are hosted on [Lightning.ai](https://lightning.ai/)).

* Chat with your code using RAG! (Easy Mode) - https://lightning.ai/lightning-ai/studios/chat-with-your-code-using-rag?section=featured

* Chat with your code: Using Weaviate, LlamaIndex, & Ollama (Not so easy) - https://lightning.ai/weaviate/studios/chat-with-your-code-rag-with-weaviate-and-llamaindex

Right now Lightning.ai has a really generous pricing & billing structure + if you sign up with your real-number you'll get an additional 15 compute units. I ran the Weaviate notebook at least 20 times on the A100 and only burned down 3 units, so there's plenty for building example projects.

![image](https://github.com/MMBazel/LO_GenAI_Workshops/assets/3360070/cdfb36b9-657f-4a7e-8143-e9f2932ffea9)



## Additional Resources

These are resources that can be helpful but weren't primary references.
### AI Engineering


### LLMOps/Gen-AI Ecosystem


### Fine-Tuning 


### RAG
* LLM and Vector Databases: Concepts, Architectures, and Examples - Sam Partee - https://www.youtube.com/watch?v=zEX3xVxSqqM
