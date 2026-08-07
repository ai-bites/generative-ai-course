

# Curso de IA Generativa 🤖

Una colección completa de cuadernos Jupyter que cubren los aspectos esenciales de la IA Generativa, desde conceptos fundamentales hasta aplicaciones avanzadas. Este repositorio sirve como guía práctica para aprender e implementar técnicas modernas de IA.

## 🎯 Descripción General

Este curso ofrece experiencia práctica con:
- Sistemas de **Generación Aumentada con Recuperación (RAG)**
- **Framework DSPy** para programación con modelos de lenguaje
- **Ajuste fino (fine-tuning) de modelos** con los modelos Gemma de Google y OpenAI
- **Técnicas de cuantización** para la optimización de modelos
- **IA Agentica** y sistemas multiagente
- Exploración de la **biblioteca Transformers**
- **Conversión de modelos GGUF** y despliegue

## 📚 Contenido del Curso

### 🔍 RAG (Generación Aumentada con Recuperación)
- **`simple_rag.ipynb`** - Implementación básica de RAG usando LangChain y ChromaDB
- **`rag_with_dspy.ipynb`** - RAG avanzado con integración del framework DSPy
- **`agentic_rag.ipynb`** - RAG agentico usando LangGraph y NVIDIA AI Endpoints
- **`agentic_rag_chromadb.ipynb`** - RAG agentico con almacén vectorial ChromaDB

### 🧠 Framework DSPy
- **`dspy_demo.ipynb`** - Introducción a DSPy para optimización de prompts y programación con modelos de lenguaje

### 🎛️ Ajuste Fino (Fine-tuning) de Modelos
- **`Finetune_Gemma.ipynb`** - Guía completa para el ajuste fino del modelo Gemma de Google
- **`gpt-oss-ft.ipynb`** - Ajuste fino de los modelos GPT de OpenAI (código abierto)

### ⚡ Optimización de Modelos
- **`intro_to_quant.ipynb`** - Introducción a las técnicas de cuantización para compresión de modelos
- **`quantize_gemma_gguf.ipynb`** - Conversión y cuantización de modelos Gemma al formato GGUF

### 🤝 Sistemas Multiagente
- **`arxiv_research_crew.ipynb`** - Creación de equipos de investigación usando CrewAI para el análisis de artículos de arXiv

### 🔧 Exploración de Frameworks
- **`Tour_of_Transformers_Library.ipynb`** - Recorrido completo por la biblioteca HuggingFace Transformers

## 🚀 Inicio Rápido

### Requisitos Previos
```bash
# Create a virtual environment
python -m venv genai-course
source genai-course/bin/activate  # Linux/Mac
# or
genai-course\Scripts\activate  # Windows

# Install core dependencies
pip install jupyter numpy pandas matplotlib
```

### Para los Tutoriales de RAG
```bash
pip install langchain langchain-community chromadb gpt4all
pip install beautifulsoup4 tqdm
```

### Para los Tutoriales de DSPy
```bash
pip install dspy-ai torch transformers accelerate
```

### Para los Tutoriales de Ajuste Fino
```bash
pip install transformers accelerate datasets peft
pip install torch torchvision torchaudio
```

### Para la Cuantización
```bash
pip install transformers accelerate matplotlib numpy
```

### Para Sistemas Multiagente
```bash
pip install crewai crewai_tools arxiv
```

## 📁 Estructura del Repositorio

```
├── README.md                           # This file
├── simple_rag.ipynb                   # Basic RAG implementation
├── rag_with_dspy.ipynb                # Advanced RAG with DSPy
├── agentic_rag.ipynb                  # Agentic RAG systems
├── agentic_rag_chromadb.ipynb         # Agentic RAG with ChromaDB
├── dspy_demo.ipynb                    # DSPy framework demo
├── Finetune_Gemma.ipynb               # Gemma fine-tuning guide
├── gpt-oss-ft.ipynb                   # GPT fine-tuning
├── intro_to_quant.ipynb               # Quantization introduction
├── quantize_gemma_gguf.ipynb          # GGUF conversion & quantization
├── arxiv_research_crew.ipynb          # Multi-agent research system
├── Tour_of_Transformers_Library.ipynb # Transformers library tour
├── data/                              # Datasets and data files
├── llama.cpp/                         # GGUF conversion tools
├── merged_model/                      # Merged model outputs
├── peft_model/                        # PEFT adapter models
└── *.log                             # Training and usage logs
```

## 🎯 Ruta de Aprendizaje

### Ruta para Principiantes
1. **Tour_of_Transformers_Library.ipynb** - Familiarízate con el ecosistema
2. **simple_rag.ipynb** - Comprende los fundamentos de RAG
3. **intro_to_quant.ipynb** - Aprende los conceptos básicos de optimización de modelos

### Ruta Intermedia
4. **dspy_demo.ipynb** - Ingeniería de prompts avanzada
5. **rag_with_dspy.ipynb** - Sistemas de RAG sofisticados
6. **Finetune_Gemma.ipynb** - Entrenamiento de modelos personalizados

### Ruta Avanzada
7. **agentic_rag.ipynb** - Sistemas de IA multiagente
8. **arxiv_research_crew.ipynb** - Automatización de flujos de trabajo complejos
9. **quantize_gemma_gguf.ipynb** - Despliegue en producción

## 🛠️ Tecnologías Clave

- **🤗 HuggingFace Transformers** - Hub de modelos y entrenamiento
- **🦜🔗 LangChain** - Framework para aplicaciones de LLM
- **📊 ChromaDB** - Base de datos vectorial para embeddings
- **🧪 DSPy** - Programación con modelos de lenguaje
- **⚡ PEFT** - Ajuste fino eficiente en parámetros
- **🔧 llama.cpp** - Inferencia de modelos eficiente
- **👥 CrewAI** - Orquestación multiagente
- **🎯 NVIDIA AI Endpoints** - Inferencia acelerada por GPU

## 📊 Modelos Cubiertos

- **Google Gemma** (2B parámetros) - Ajuste fino y cuantización
- **Modelos GPT de OpenAI** - Flujos de trabajo de ajuste fino
- **Varios modelos de HuggingFace** - Para RAG y embeddings
- **Modelos personalizados ajustados** - Adaptadores PEFT y fusión

## 🎓 Lo que Aprenderás

- **Sistemas RAG**: Construye sistemas inteligentes de recuperación de documentos y respuesta a preguntas
- **Ajuste Fino de Modelos**: Personaliza modelos de lenguaje grandes para tareas específicas
- **Cuantización**: Optimiza modelos para despliegue y velocidad de inferencia
- **Programación con DSPy**: Ingeniería de prompts avanzada y encadenamiento de modelos
- **IA Multiagente**: Crea sistemas de IA colaborativos para tareas complejas
- **Despliegue en Producción**: Convierte y optimiza modelos para uso en el mundo real

## 🔧 Requisitos de Hardware

- **Mínimo**: 8GB de RAM, inferencia posible solo con CPU
- **Recomendado**: 16GB+ de RAM, GPU NVIDIA con 8GB+ de VRAM
- **Para Ajuste Fino**: Se recomiendan 24GB+ de VRAM (o usa gradient checkpointing)

## 📝 Notas de Uso

- Cada cuaderno es autónomo e incluye instrucciones de instalación
- Algunos cuadernos requieren claves API (OpenAI, HuggingFace, NVIDIA)
- Los modelos se almacenan en caché localmente después de la primera descarga
- Los archivos de modelos grandes no se incluyen en el repositorio

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Por favor:
1. Haz un fork del repositorio
2. Crea una rama de características
3. Agrega documentación completa
4. Envía un pull request

## 📄 Licencia

Este proyecto es de código abierto. Por favor, verifica las licencias individuales de los modelos al usar modelos específicos.

## 🙏 Agradecimientos

- Google Research por los modelos Gemma
- HuggingFace por la biblioteca Transformers
- Comunidad de LangChain por los frameworks de RAG
- Equipo de DSPy por la programación avanzada de LLM
- Proyecto llama.cpp por la inferencia eficiente

---

**¡Feliz aprendizaje! 🚀**

*Para preguntas o problemas, por favor abre un issue en GitHub o contacta a los mantenedores.*
