---
author: Josx - Cooperativa de trabajo Cambá
date: DD-MM-YYYY
paging: Pag %d / %d
---

# La bestIA: Ni Inteligente Ni Artificial

## Preludio
- ¿Quiénes somos? ¿Qué hacemos?
- ¿Por qué estamos acá?
- Dos años de La bestIA ¿Probamos?

---

# Motivaciones: Generales
- Genarar conocimiento sobre los usos y herramientas de nuestra área
- Utilización de Software libre y modelos lo más abiertos posibles
- Mejorar el grado de autonomía e independencia de las grandes empresas del rubro
- Pensar, reflexionar y profundizar sobre las herramientas que están alineadas con nuestros principios.

# Motivaciones: Espécificas
- Tener disponibles servicios de IA para poder consumirlos de diversas formas con infra propia
- Reemplazar uso interno de Chatgpt/poe.com/COPILOT, etc
- Abrirnos camino con herramientas específicas para nuestra área
- Empezar a tener experiencia en soluciones de programación e infrastrucutra en relación a la IA para posibles nuevos servicios.

---

# Hardware
> Adquisición de hardware y configuración para proveernos de servicios selfhosted/OnPrem

## Incertidumbres
- ¿Cuánto presupuesto es el mínimo que necesitamos?
- ¿Qué conviene más?
- ¿Qué cuesta menos?

## Fuentes de información
- [Grupo LocalLLaMA de Reddit](https://www.reddit.com/r/LocalLLaMA/)
- [Board de Tech de 4chan](https://boards.4chan.org/g/)
- [Videos de Alex Ziskind](https://www.youtube.com/@AZisk)
- [Videos de Digital Space Port](https://www.youtube.com/@DigitalSpaceport)

---

# Hardware
## PC
- **GPUs: ZOTAC GAMINC GEFORCE RTX 3090 TRINITY OC 24GB 384BIT GDDR6X GPU 24GB - x2**
- CPU: AMD Ryzen 9 7950X
- HDD: ADATA LEGEND 960 MAX 1TB
- MEM: T-CREATE EXPERT CL34 White 64GB
- MOTHER: ASUS ROG STRIX X670E-E GAMING WIFI AM5 DDR5
- FUENTE: ASUS ROG THOR 2 1200W 80 Plus Platinum II 1200P Full Modular
---

# Hardware
## Tiempos
- Investigación y compra: **20h**
- Armado: **16h**
- Testeo: **20h**

## Costo
- **USD 3178 Abril/Mayo 2024 (+10,5% impuestos)**

---

# Software
> Aprender sobre la posibilidad de un stack de IA con software libre

## Incertidumbres
- ¿Cuales son las necesidades mínimas?
- ¿Necesitamos varias aplicaciones?
- ¿Para que sirve cada una?
- ¿Hay diferentes opciones para cada aplicaciones? Evaluaciones

## Fuentes de información
- [Videos de NetworkChuck](https://www.youtube.com/@NetworkChuck)
- [Blog de Simon Willison](https://simonwillison.net/)
- [Revista Electrónica de Cambá](https://camba.gitlab.io/ctte-ezine/)

---

# Software
## Aplicaciones

- [Ubuntu 24.04](https://ubuntu.com/download/server/) - Sistema Operativo, Usamos software no libre para los drivers de NVIDIA 550.120
- [Ollama](https://ollama.com/) - Motor de inferencia/backend: llama.cpp + interfaz en terminal
- [Open Webui](https://openwebui.com/) - Interfaz de chat para usuarios via web
- [Langfuse](https://langfuse.com/) - LLM observabilidad, telemétria, monitor, evaluar y debug de aplicaciones

## Otras
- [LLM](https://llm.datasette.io/en/stable/index.html)
- [Page-Assist](https://github.com/n4ze3m/page-assist)
- [MAID](https://github.com/Mobile-Artificial-Intelligence/maid)
---

# Modelos LLMs
> Aprender sobre los grandes modelos de lenguaje

## Incertidumbres
- ¿Cuál podria hacer funcionar en mi hardware?
- ¿Hay muchos como selecciono?
- ¿Hay nuevos modelos todos los días?
- ¿Todos sirven para el mismo fin?

## Fuentes de información
- [Videos de Matthew Berman](https://www.youtube.com/@matthew_berman)
- [Blog de Simon Willison](https://simonwillison.net/)

---

# Modelos LLMs

## Nombres/Empresas
| Empresas    | Modelos |
|-------------|---------|
|**Deepseek** | v4  |
|**Alibaba**  | Qwen  |
|**Google**   | Gemma, Gemini |
|**Meta** | Llama |
|**Antrophic** | haiku, Sonnet, Opus|
|**OpenAI** |Gpt-X, O-mini, Ox|
|**Mistral** | Small, Large |
|**Microsoft** | Phi |
|**MoonShot AI** | Kimi|
|**Ziphu.AI**| GLM |

---

# Modelos LLMs
## Palabras clave
- [Transformers](https://arxiv.org/abs/1706.03762) - Attention Is All You Need
- [Moe (Mixture of experts)](https://huggingface.co/blog/moe)
- [Thinking (Chain of thought)](https://www.ibm.com/think/topics/chain-of-thoughts)
- [Quantización](https://huggingface.co/blog/merve/quantization)
- [Fine tunning](https://www.ibm.com/es-es/think/topics/fine-tuning)
- [Destilados](https://techcommunity.microsoft.com/blog/aiplatformblog/distillation-turning-smaller-models-into-high-performance-cost-effective-solutio/4355029)
- Context Window length
- Multimodal

---
# Modelos LLMs

## ¿Licencias Libres?
- ¿Qué significa un modelo libre?
    - Hay discusion sobre el termino open source (¿son open weight?)
- [Open Source AI Definition 1.0 - OSAID](https://opensource.org/ai/open-source-ai-definition)
- [Open source European Index](https://osai-index.eu/the-index) - Listado de modelos y apertura
- [Model Opennes Framework](https://isitopen.ai/) - Listado de modelos y apertura

---

# Modelos LLMs
## Ejemplos
- [Licencia de  llama 3](https://www.llama.com/llama3/license/)
> ...is greater than 700 million monthly active users in the preceding calendar month, you must request a license from Meta
- [Qwen2.5](https://huggingface.co/Qwen/Qwen2.5-72B/blob/main/LICENSE)
> If you are commercially using the Materials, and your product or service has more than  100 million monthly active users
- Apache2 License
    - [Qwen 3.6](https://github.com/QwenLM/Qwen3.6/blob/main/LICENSE)
    - [Gemma](https://ai.google.dev/gemma/apache_2)
- MIT License
    - [Deepseek-v4](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro/blob/main/LICENSE)
    - [GLM 5.1](https://huggingface.co/zai-org/GLM-5.1/blob/main/LICENSE)
    - [Kimi k2](https://github.com/moonshotai/Kimi-K2/blob/main/LICENSE)
---

# Modelos LLMs
## Leaderboard/Rankings
- [Chatbot Arena](https://lmarena.ai/)
- [Open LLM](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard)
- [Resolver Real-World GitHub Issues](https://www.swebench.com/index.html)
- [Aider - Desarrollo de software con costos asociados](https://aider.chat/docs/leaderboards/)
- [LiveCodeBench](https://livecodebench.github.io/leaderboard.html)
---
# Modelos LLMs
## Performance
> En nuestro hardware con 48GB de VRAM, 64GB de RAM, CPU Ryzen 9 7950X

| Modelo              | Paramétros | GB | Token/s |
|--------------------------|------|---------|-----|
| qwen3.6:35b-a3b-q4_K_M   | 35B  |  23GB   | 90  |
| qwen3-coder-next:q4_K_M  | 80B  |  50GB   | 130 |
| gemma4:e4b-it-q4_K_M     | 26B  |  17GB   | 21  |

---

# Programación

## Incertidumbres
- ¿Qué librerias/bibliotecas/Framework usamos?
- ¿Cuáles son las mejores herramientas para programar?
- ¿Hay diferentes opciones? Evaluaciones


## Fuentes de información
- [Videos de AICodeKing](https://www.youtube.com/@AICodeKing)
- [Blog de Simon Willison](https://simonwillison.net/)

---

# Programación
## Herramientas
- [LangFlow](https://www.langflow.org/) - Low-code para creación de flujo de trabajo de IA
- [Langchain](https://www.langchain.com/) - Framework para crear aplicaciones con LLMs
- [Python-sdk (MCP)](https://modelcontextprotocol.io/introduction) -
Model Context Protocol (MCP) es un protocolo abierto para integración entre aplicaciones LLM y programas externos
- [Chroma DB](https://www.trychroma.com/) - Base de datos para aplicaciones IA  (Embeddings, vector search, document storage, full-text search, metadata filtering, and multi-modal)

## Asistentes/Agentes
- [Aider](https://aider.chat/) - Pair programming con AI en tu terminal
- [OpenCode](https://opencode.ai/) - Agente de programación autonóna en tu IDE

---

# Programación
## Contribuciones
- [Open-Webui](https://github.com/open-webui/open-webui/pull/3990)
- [LangFuse](https://github.com/langfuse/langfuse/pull/3980)
- [LangFlow](https://github.com/langfuse/langfuse-docs/pull/961)
- [Langchain](https://github.com/langchain-ai/langchain/pull/18519)
- [Aider](https://github.com/Aider-AI/aider/pull/2369)
- [ModelContextProtocol](https://github.com/modelcontextprotocol/servers/pull/92)
- [Dive](https://github.com/OpenAgentPlatform/Dive/pull/72)
- [OpenHands](https://github.com/All-Hands-AI/OpenHands/pull/6458)
- [Fabric](https://github.com/danielmiessler/fabric/pull/621)
- [Page-Assist](https://github.com/n4ze3m/page-assist/pull/128)
- [Chatmcp](https://github.com/daodao97/chatmcp/pull/65)
- [Llm-ollama](https://github.com/taketwo/llm-ollama/pull/43)
- [Rag-api](https://github.com/danny-avila/rag_api/pull/59)
---

# Coda

#### [Cooperativa de trabajo Cambá](https://www.camba.coop)
#### José Luis Di Biase josx@camba.coop

#### PREGUNTAS Y RESPUESTAS
