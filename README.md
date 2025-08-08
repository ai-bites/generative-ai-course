# Generative AI Course 🤖

A comprehensive collection of Jupyter notebooks covering the essential aspects of Generative AI, from foundational concepts to advanced applications. This repository serves as a practical guide for learning and implementing modern AI techniques.

## 🎯 Overview

This course provides hands-on experience with:
- **Retrieval-Augmented Generation (RAG)** systems
- **DSPy framework** for programming with language models
- **Model fine-tuning** with Google's Gemma and OpenAI models
- **Quantization techniques** for model optimization
- **Agentic AI** and multi-agent systems
- **Transformers library** exploration
- **GGUF model conversion** and deployment

## 📚 Course Content

### 🔍 RAG (Retrieval-Augmented Generation)
- **`simple_rag.ipynb`** - Basic RAG implementation using LangChain and ChromaDB
- **`rag_with_dspy.ipynb`** - Advanced RAG with DSPy framework integration
- **`agentic_rag.ipynb`** - Agentic RAG using LangGraph and NVIDIA AI Endpoints

### 🧠 DSPy Framework
- **`dspy_demo.ipynb`** - Introduction to DSPy for prompt optimization and language model programming

### 🎛️ Model Fine-tuning
- **`Finetune_Gemma.ipynb`** - Complete guide to fine-tuning Google's Gemma model
- **`gpt-oss-ft.ipynb`** - Fine-tuning OpenAI's GPT models (open-source)

### ⚡ Model Optimization
- **`intro_to_quant.ipynb`** - Introduction to quantization techniques for model compression
- **`quantize_gemma_gguf.ipynb`** - Converting and quantizing Gemma models to GGUF format

### 🤝 Multi-Agent Systems
- **`arxiv_research_crew.ipynb`** - Building research crews using CrewAI for arXiv paper analysis

### 🔧 Framework Exploration
- **`Tour_of_Transformers_Library.ipynb`** - Comprehensive tour of HuggingFace Transformers library

## 🚀 Quick Start

### Prerequisites
```bash
# Create a virtual environment
python -m venv genai-course
source genai-course/bin/activate  # Linux/Mac
# or
genai-course\Scripts\activate  # Windows

# Install core dependencies
pip install jupyter numpy pandas matplotlib
```

### For RAG Tutorials
```bash
pip install langchain langchain-community chromadb gpt4all
pip install beautifulsoup4 tqdm
```

### For DSPy Tutorials
```bash
pip install dspy-ai torch transformers accelerate
```

### For Fine-tuning Tutorials
```bash
pip install transformers accelerate datasets peft
pip install torch torchvision torchaudio
```

### For Quantization
```bash
pip install transformers accelerate matplotlib numpy
```

### For Multi-Agent Systems
```bash
pip install crewai crewai_tools arxiv
```

## 📁 Repository Structure

```
├── README.md                           # This file
├── simple_rag.ipynb                   # Basic RAG implementation
├── rag_with_dspy.ipynb                # Advanced RAG with DSPy
├── agentic_rag.ipynb                  # Agentic RAG systems
├── dspy_demo.ipynb                    # DSPy framework demo
├── Finetune_Gemma.ipynb               # Gemma fine-tuning guide
├── gpt-oss-ft.ipynb                   # GPT fine-tuning
├── intro_to_quant.ipynb               # Quantization introduction
├── quantize_gemma_gguf.ipynb          # GGUF conversion & quantization
├── arxiv_research_crew.ipynb          # Multi-agent research system
├── Tour_of_Transformers_Library.ipynb # Transformers library tour
├── llama.cpp/                         # GGUF conversion tools
├── merged_model/                      # Merged model outputs
├── peft_model/                        # PEFT adapter models
└── *.log                             # Training and usage logs
```

## 🎯 Learning Path

### Beginner Track
1. **Tour_of_Transformers_Library.ipynb** - Get familiar with the ecosystem
2. **simple_rag.ipynb** - Understand RAG fundamentals
3. **intro_to_quant.ipynb** - Learn model optimization basics

### Intermediate Track
4. **dspy_demo.ipynb** - Advanced prompt engineering
5. **rag_with_dspy.ipynb** - Sophisticated RAG systems
6. **Finetune_Gemma.ipynb** - Custom model training

### Advanced Track
7. **agentic_rag.ipynb** - Multi-agent AI systems
8. **arxiv_research_crew.ipynb** - Complex workflow automation
9. **quantize_gemma_gguf.ipynb** - Production deployment

## 🛠️ Key Technologies

- **🤗 HuggingFace Transformers** - Model hub and training
- **🦜🔗 LangChain** - LLM application framework
- **📊 ChromaDB** - Vector database for embeddings
- **🧪 DSPy** - Programming with language models
- **⚡ PEFT** - Parameter-efficient fine-tuning
- **🔧 llama.cpp** - Efficient model inference
- **👥 CrewAI** - Multi-agent orchestration
- **🎯 NVIDIA AI Endpoints** - GPU-accelerated inference

## 📊 Models Covered

- **Google Gemma** (2B parameters) - Fine-tuning and quantization
- **OpenAI GPT models** - Fine-tuning workflows
- **Various HuggingFace models** - For RAG and embeddings
- **Custom fine-tuned models** - PEFT adapters and merging

## 🎓 What You'll Learn

- **RAG Systems**: Build intelligent document retrieval and question-answering systems
- **Model Fine-tuning**: Customize large language models for specific tasks
- **Quantization**: Optimize models for deployment and inference speed
- **DSPy Programming**: Advanced prompt engineering and model chaining
- **Multi-Agent AI**: Create collaborative AI systems for complex tasks
- **Production Deployment**: Convert and optimize models for real-world use

## 🔧 Hardware Requirements

- **Minimum**: 8GB RAM, CPU-only inference possible
- **Recommended**: 16GB+ RAM, NVIDIA GPU with 8GB+ VRAM
- **For Fine-tuning**: 24GB+ VRAM recommended (or use gradient checkpointing)

## 📝 Usage Notes

- Each notebook is self-contained with installation instructions
- Some notebooks require API keys (OpenAI, HuggingFace, NVIDIA)
- Models are cached locally after first download
- Large model files are not included in the repository

## 🤝 Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Add comprehensive documentation
4. Submit a pull request

## 📄 License

This project is open source. Please check individual model licenses when using specific models.

## 🙏 Acknowledgments

- Google Research for Gemma models
- HuggingFace for the Transformers library
- LangChain community for RAG frameworks
- DSPy team for advanced LLM programming
- llama.cpp project for efficient inference

---

**Happy Learning! 🚀**

*For questions or issues, please open a GitHub issue or reach out to the maintainers.*
