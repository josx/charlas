---
author: José Luis Di Biase - Cooperativa de trabajo Cambá
date: DD-MM-YYYY
paging: Pag %d / %d
---
# Automatizando flujos de trabajo de IA con Python
## Preludio
> ¿Quiénes somos? ¿Qué venimos haciendo?

Durante el último año en Cambá (Cooperativa de trabajo tecnológica donde trabajo y estoy asociado), empezamos un proceso de investigación sobre Inteligencia Artificial Generativa. Para comprender, empezamos desde el más bajo nivel: Comprando, instalando y configurando nuestra propia maquina con múltiples servicios y herramientas, a la que denominamos **"La bestIA"**.

Empezamos un viaje de exploración y experimentación del estado del arte de diversas herramientas y modelos para encontrar caminos hacia nuevos servicios y productos. Durante éste proceso, en relación a las artes. Durante la charla vamos a relatar y mostrar nuestra experiencia en automatizar flujos de trabajo de IA artisticos con python.
---
# Automatizando flujos de trabajo de IA con Python
## Hardware
> ¿Donde corremos la inferencia? La BestIA
- GPUs: RTX 3090 24GB 384BIT GDDR6X GPU 24GB - x2
- CPU: AMD Ryzen 9 7950X
- HDD: ADATA LEGEND 960 MAX 1TB
- MEM: T-CREATE EXPERT CL34 White 64GB
- MOTHER: ASUS ROG STRIX X670E-E GAMING WIFI AM5 DDR5
- FUENTE: ASUS ROG THOR 2 1200W 80 Plus Platinum II 1200P Full Modular
- COOLER: Be quiet! SILENT LOOP 2 240mm Water
---
# Automatizando flujos de trabajo de IA con Python
## Flujos de trabajo IA
- ¿Qué es [ComfyUI](https://github.com/comfyanonymous/ComfyUI)?
    - IA para lo AudioVisual con GUI
    - Software libre y Hecha con Python
    - Interfaz de grafos/nodos.
- Construimos múltiple flujos de trabajo
    - Creador de Flyers
    - Avatar cantante
    - Clonación de voz
    - Avatar con Clonación de voz
    - Audio es IA
---
# Automatizando flujos de trabajo de IA con Python
## Modelos
> ¿Qué usamos para los flujos de trabajo?

| Organización | Modelos |
|--------------|---------|
|**Alibaba**   | Qwen-Image, Qwen-vl |
|**Microsoft** | VibeVoice |
|**DeepBrainAi**| Float |
|**Awsaf49** | Sonics |
---
# Automatizando flujos de trabajo de IA con Python
## Objetivos
- Construir Aplicación Demo
    - Interfaz GUI Web
    - Minima
    - Autenticación
- Permitir a usuarios interactuar con múltiples flujos de trabajo de IA
```
~~~/usr/bin/graph-easy --as=boxart
[USUARIO] - interactua -> [ WEBAPP ] - ejecuta -> [ FLUJO IA ]
~~~
```
---
# Automatizando flujos de trabajo de IA con Python
## **Python al rescate:** Interfaz y Automatización
- GRADIO (Formularios, campos, multiapp, Autenticación)
- COMFY_API_SIMPLIFIED (Ejecutar flujos de trabajo de ComfyUI de manera remota)
```
~~~/usr/bin/graph-easy --as=boxart
[ GRADIO ] - genera -> [ WEBAPP ]
[ JSON ] - flujo -> [ COMFY_API_SIMPLIFIED ] - api -> [ COMFYUI SERVER ]
[ WEBAPP ] - datos -> [ COMFY_API_SIMPLIFIED ]
~~~
```
---
# Automatizando flujos de trabajo de IA con Python

#### Mostrar Código
#### Ejecutar Aplicación
---
# Automatizando flujos de trabajo de IA con Python
## Contribuciones
> En el mientras tanto...

- [Comfy_api_simplified](https://github.com/deimos-deimos/comfy_api_simplified/commits?author=josx)
    - Support to download audios with Save Audio from comfy-core nodes (#15)
    - Support to download videos with VideoCombine from ComfyUI-VideoHelperSuite (#14)

- [Gradio](https://github.com/gradio-app/gradio/commits?author=josx)
    - Fix multiple: route with accents doesnt work (#11935) (#11936)
---
# Automatizando flujos de trabajo de IA con Python
## Coda

#### [Cooperativa de trabajo Cambá](https://www.camba.coop)
#### [Ia-demos](https://github.com/Cambalab/ia-demos)

#### José Luis Di Biase josx@camba.coop

#### PREGUNTAS Y RESPUESTAS
