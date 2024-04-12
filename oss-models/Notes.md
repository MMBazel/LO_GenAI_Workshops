# Resources for Mini-Workshop: Crash Course Open Source Models

In the mini-workshop we covered a couple different tutorials, tools and resources as an introduction to working with open-source LLMs. 

👇 The links to the referenced resources are below 👇

## Slides & Talk
* Slides should be in this repo but backup slides will also be posted to LinkedIn
* For the talk video, check with Tine &/or Rex. 

## Notebooks & Tutorial Materials 

### Using TinyLlama Chat
* Chatting with [TinyLlama/TinyLlama-1.1B-Chat-v1.0](https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0) on Huggingface

![Screenshot 2024-04-11 at 5 10 46 PM](https://github.com/MMBazel/LO_GenAI_Workshops/assets/3360070/c0c46997-7a9e-4f1d-a210-c293ab14fe5c)


### Fine-Tuning: Creating a Taylor Swift fine-tuned model 
There are two notebooks (exact same project): 

* [[Mini]_HelloTaylorSwift_FineTuning.ipynb](https://github.com/MMBazel/LO_GenAI_Workshops/blob/main/oss-models/%5BMini%5D_HelloTaylorSwift_FineTuning.ipynb) - This is the minimal amount of code need to fine-tune a tinyllama model on Taylor Swift lyrics.
* [[Explainer]_HelloTaylorSwift_FineTuning.ipynb](https://github.com/MMBazel/LO_GenAI_Workshops/blob/main/oss-models/%5BExplainer%5D_HelloTaylorSwift_FineTuning.ipynb) - This is the explainer notebook; it has a lot more unnecessary code (like print statements), is peppered with explanations about each code block. At the end I also offer some suggestions for how to extend the notebook.

![Screenshot 2024-04-11 at 5 10 15 PM](https://github.com/MMBazel/LO_GenAI_Workshops/assets/3360070/7b476d03-2398-4158-befa-2380b8e821bf)

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

HelloTaylorSwift tutorial is based primarily on this tutorial:

* [Original kaggle notebook](https://www.kaggle.com/code/tommyadams/fine-tuning-tinyllama)
* [Kaggle dataset](https://www.kaggle.com/datasets/thespacefreak/taylor-swift-song-lyrics-all-albums)
  
However these other resources are also helpful:

* Similar Model: https://huggingface.co/huggingartists/taylor-swift
* Similar Dataset: https://huggingface.co/datasets/huggingartists/taylor-swift
Tutorials on SFT & fine-tuning, TinyLlama, & HuggingFace

* [Fine-Tune Your Own Tiny-Llama on Custom Dataset](https://www.youtube.com/watch?v=OVqe6GTrDFM)
* [TinyLlama LLM: A Step-by-Step Guide to Implementing the 1.1B Model on Google Colab](https://dev.to/_ken0x/tinyllama-llm-a-step-by-step-guide-to-implementing-the-11b-model-on-google-colab-1pjh)
* [Instruct-Tune Llama to Create ChatGPT Like Chatbots | Custom Dataset, Huggingface, SFT](https://www.youtube.com/watch?v=6XeTk8cZUsM)
* https://github.com/uygarkurt/SFT-TinyLlama/tree/main


### Doing Simple RAG 
There are two notebooks/spaces that I showed and which offer a great introduction to using RAG (both of which are hosted on [Lightning.ai](https://lightning.ai/)).

Right now Lightning.ai has a really generous pricing & billing structure + if you sign up with your real phone number (trust me, it doesn't accept Google Voice numbers 😢) you'll get an additional 15 compute units. 

![image](https://github.com/MMBazel/LO_GenAI_Workshops/assets/3360070/cdfb36b9-657f-4a7e-8143-e9f2932ffea9)

Anecdote: I ran the Weaviate notebook at least 20 times on the A100 and only burned down 3 units, so there's plenty for building example projects.

* Chat with your code using RAG! (Easy Mode) - https://lightning.ai/lightning-ai/studios/chat-with-your-code-using-rag?section=featured

For this first space, you don't need anything special in terms of keys or credentials.

* Chat with your code: Using [Weaviate](https://weaviate.io/), [LlamaIndex](https://www.llamaindex.ai/), & [Ollama](https://ollama.com/) (Not as easy) - https://lightning.ai/weaviate/studios/chat-with-your-code-rag-with-weaviate-and-llamaindex

For the second space you'll need to create an account with Weaviate to create a hosted Weaviate cluster where the embeddings are ultimately stored. 
The instructions are incredibly straight-forward and they offer a 14-day trial. You can do quite a bit with the existing sandbox clusters for toy projects and they have an active developer community, so would highly recommend.


## Additional Resources

These are resources that can be helpful but weren't primary references.
### LLMs
* How do LLMs like ChatGPT work? Explained by Deep-Fake Ryan Gosling using Synclabs and ElevenLabs: https://www.youtube.com/watch?v=xU_MFS_ACrU
* [Andrej Karpathy's Intro to LLMs](https://www.youtube.com/watch?v=zjkBMFhNj_g)
* [State of GPT | Andrej Karpathy's Detailed description of how Chat-GPT came to be](https://youtu.be/bZQun8Y4L2A?si=VZV0t831ctsmBRFV)
* [Let's build GPT: from scratch, in code, spelled out.](https://www.youtube.com/watch?v=kCc8FmEb1nY)
* [Cohere's LLM University](https://docs.cohere.com/docs/llmu)

### AI Engineering
* [A collection of multi-day tutorials on LLMs: github/awesome-generative-ai-guide: https://github.com/aishwaryanr/awesome-generative-ai-guide/tree/main](https://github.com/aishwaryanr/awesome-generative-ai-guide/tree/main)
* [One of the best bootcamps on AI Engineering - Videos are kind of rough and slides are pretty incomplete but still really good - AI Makerspace](https://github.com/AI-Maker-Space/LLM-Ops-Cohort-1)
* [The Labonne LLMOps Mega-Course](https://github.com/mlabonne/llm-course)

### Gen-AI Ecosystem
* [Excellent AI Summarizer: https://buttondown.email/ainews](https://buttondown.email/ainews)
* [Latent.Space interviewing most of the gen-AI ecosystem at one point or another: https://www.latent.space/about](https://www.latent.space/about)


### Fine-Tuning 
* [Youssef Hosni's Fine-Tuning Recommendations](https://www.linkedin.com/posts/youssef-hosni-b2960b135_mastering-large-language-model-llm-fine-tuning-activity-7180922344054398976-t561?utm_source=share&utm_medium=member_desktop)


### RAG
* [How RAG makes LLMs like ChatGPT more accurate and up-to-date. By Deep-Fake Chance The Rapper.](https://www.youtube.com/watch?v=q9hlaa7DnNU) 
* [LLM and Vector Databases: Concepts, Architectures, and Examples - Sam Partee](https://www.youtube.com/watch?v=zEX3xVxSqqM)
* [Building RAG-based LLM Applications for Production from Anyscale](https://www.anyscale.com/blog/a-comprehensive-guide-for-building-rag-based-llm-applications-part-1)
* [Prince Canuma's RAGOps Presentation](https://www.linkedin.com/posts/langchain_ragops-advanced-retrieval-strategies-with-activity-7179983238927380480-6q6w/?utm_source=share&utm_medium=member_ios)

## Additional Practice
* [One of the best Hackathon sites for Gen-AI: https://lablab.ai/](https://lablab.ai/)
* [Huggingface Open-Source Cookbook](https://huggingface.co/learn/cookbook/index)
