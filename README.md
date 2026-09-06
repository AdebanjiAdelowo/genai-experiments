# Generative AI Projects

A collection of end-to-end Generative AI projects covering RAG pipelines, LLM fine-tuning, chatbots, vector databases, and cloud LLM deployment, built with LangChain, OpenAI, Google Vertex AI, Amazon Bedrock, and more.

---

## End-to-End-AI-Applications

| Project | Description | Stack |
|---|---|---|
| [Medical Chatbot](End-to-End-AI-Applications/End-to-end-Medical-Chatbot-Generative-AI/) | RAG-based chatbot that answers medical questions from a PDF knowledge base | OpenAI, Pinecone, LangChain, Flask |
| [Source Code Analyser](End-to-End-AI-Applications/End-to-end-Source-Code-Analysis-Generative-AI/) | Clone any GitHub repo and ask natural language questions about the code | OpenAI, ChromaDB, LangChain, Flask |
| [Food OrderBot](End-to-End-AI-Applications/LLM-Apps-with-Chainlit/) | Conversational food ordering chatbot with a full menu | OpenAI, Chainlit |

---

## Cloud-LLM-Apps

| Project | Description | Stack |
|---|---|---|
| [RAG with Amazon Bedrock (Chroma)](Cloud-LLM-Apps/EndtoendRAGusingAmazonBedrockChromaProject/) | RAG pipeline over PDF documents using AWS Bedrock and a Chroma vector store | Bedrock, ChromaDB, LangChain |
| [RAG with Amazon Bedrock (FAISS)](Cloud-LLM-Apps/EndtoendRAGusingAmazonBedrockFaissProject/) | RAG pipeline over PDF documents using AWS Bedrock and a FAISS vector store | Bedrock, FAISS, LangChain |
| [Vertex AI Chatbot (Flask)](Cloud-LLM-Apps/PoweredChatbotwithVertexAIFlask/) | Conversational chatbot powered by Gemini 1.5 Flash on Google Cloud, served with Flask | Vertex AI, Gemini 1.5 Flash, Flask |
| [Vertex AI Chatbot (Streamlit)](Cloud-LLM-Apps/PoweredChatbotwithVertexAIStreamlit/) | Same chatbot with a Streamlit front end | Vertex AI, Gemini 1.5 Flash, Streamlit |
| [RAG on Vertex AI](Cloud-LLM-Apps/RAG%20on%20VertexAI.ipynb) | RAG pipeline notebook using Vertex AI embeddings and Gemini | Vertex AI, LangChain |
| [Vertex AI Demo](Cloud-LLM-Apps/vertexai%20demo.ipynb) | Multimodal demos with Gemini 1.5 Flash (text, image, chat) | Vertex AI, Gemini 1.5 Flash |
| [Vertex AI Fine-Tuning](Cloud-LLM-Apps/vertexai_llm_fine_tuning_supervised.ipynb) | Supervised fine-tuning of Gemini 1.5 Flash on BBC News summaries | Vertex AI SFT, Gemini 1.5 Flash |

---

## Retrieval-Augmented-Generation

| Project | Description | Stack |
|---|---|---|
| [RAG Demo](Retrieval-Augmented-Generation/RAG-Demo/) | Basic RAG pipeline demonstration | LangChain, OpenAI |
| [RAG with Gemini](Retrieval-Augmented-Generation/RAG-gemini/) | PDF-based RAG chatbot with Gemini and ChromaDB | Gemini, ChromaDB, LangChain, Streamlit |

---

## OpenAI-Projects

| Project | Description | Stack |
|---|---|---|
| [OpenAI Demo](OpenAI-Projects/OpenAI-Demo/) | OpenAI API demos and experiments | OpenAI |
| [DALL-E Demo](OpenAI-Projects/DALLE-demo/) | Image generation with DALL-E | OpenAI DALL-E |
| [Audio Translation](OpenAI-Projects/Audio-Translation/) | Speech-to-text using Whisper API | OpenAI Whisper |
| [Telegram Chatbot](OpenAI-Projects/Telegram-chatbot/) | Chatbot integrated with Telegram | OpenAI, Telegram Bot API |
| [Fine-Tuned Classification](OpenAI-Projects/Fine_tuned_classification.ipynb) | Text classification using a fine-tuned OpenAI model | OpenAI Fine-tuning |

---

## LangChain-Projects

| Project | Description | Stack |
|---|---|---|
| [LangChain Projects](LangChain-Projects/LangChain-Projects/) | Custom chatbots, agents, multi-dataframe agents, and Hugging Face integrations | LangChain, OpenAI, HuggingFace |

---

## Vector-Database-Projects

| Project | Description | Stack |
|---|---|---|
| [Vector Database Demos](Vector-Database-Projects/Vector-Database-Demos/) | ChromaDB, Pinecone, and Weaviate demos with LangChain | ChromaDB, Pinecone, Weaviate |

---

## Fine-Tuning-LLMs

| Project | Description | Stack |
|---|---|---|
| [Llama 2 Fine-Tuning](Fine-Tuning-LLMs/Llama2-Fine-Tuning/) | Fine-tuning Llama 2 with custom datasets | Llama 2, HuggingFace |

---

## Open-Source-LLM-Projects

| Project | Description | Stack |
|---|---|---|
| [Falcon 7B Demos](Open-Source-LLM-Projects/Falcon-7B-Demos/) | Falcon 7B with ChromaDB multi-doc retriever and LangChain | Falcon 7B, ChromaDB, LangChain |
| [Llama 2 Demos](Open-Source-LLM-Projects/Llama2-Demos/) | Running Llama 2 locally, LangChain integration, website bot | Llama 2, Pinecone, LangChain |

---

## LlamaIndex-Projects

| Project | Description | Stack |
|---|---|---|
| [Financial Stock Analysis](LlamaIndex-Projects/financial-stock-llama-index/) | AI-powered stock outlook and competitor analysis reports | LlamaIndex, OpenAI, Streamlit |
| [LlamaIndex Demo](LlamaIndex-Projects/LlamaIndex_demo.ipynb) | Introductory LlamaIndex notebook covering core indexing and querying concepts | LlamaIndex, OpenAI |
| [Mistral with LlamaIndex](LlamaIndex-Projects/Mistral_with_llamaindex.ipynb) | LlamaIndex integration with Mistral for local/open-source LLM querying | LlamaIndex, Mistral |

---

## HuggingFace-Projects

| Project | Description | Stack |
|---|---|---|
| [HuggingFace Demo](HuggingFace-Projects/HuggingFace_demo.ipynb) | Model inference and pipeline demos using Hugging Face Transformers | HuggingFace Transformers |
| [Text Summarizer](HuggingFace-Projects/Text_Summarizer_project.ipynb) | Abstractive text summarization with HuggingFace models | HuggingFace Transformers |
| [Text-to-Image Generation](HuggingFace-Projects/Text_to_Image_generation_with_LLM_with_hugging_face.ipynb) | Generate images from text prompts using diffusion models | HuggingFace Diffusers |
| [Text-to-Speech](HuggingFace-Projects/Text_to_speech_generation_with_LLM_with_hugging_face.ipynb) | Convert text to audio using HuggingFace TTS models | HuggingFace Transformers |

---

## Setup

Most projects use conda environments. Each project folder has its own `requirements.txt` and `README.md` with specific setup instructions.

```bash
conda create -n <env-name> python=3.10 -y
conda activate <env-name>
pip install -r requirements.txt
```

You will need API keys depending on the project:
- `OPENAI_API_KEY`: OpenAI projects
- `PINECONE_API_KEY`: Pinecone vector store projects
- AWS credentials: Amazon Bedrock projects
- Google Cloud credentials: Vertex AI projects
