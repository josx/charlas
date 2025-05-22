---
author: Cooperativa de trabajo Cambá
date: DD-MM-YYYY
paging: Pag %d / %d
---

# Ciberseguridad y IA Generativa

## Preludio
- ¿Quiénes somos?
- ¿Qué hacemos?
- ¿Por qué estamos acá?

---
# Introducción Ciberseguridad

La ciberseguridad se refiere a cualquier tecnología, práctica y política para prevenir los ataques cibernéticos o mitigar su impacto. La ciberseguridad tiene como objetivo proteger los sistemas informáticos, las aplicaciones, los dispositivos, los datos, los activos financieros y a las personas.


---

# IA Generativa
- Adopción responsable: Indagar en Riesgos, Causas, Consecuencias, Mitigaciones, etc
## Glosario
- Modelos, Inferencia, Prompts
- Contexto
    - Archivos, Imagenes
    - Prompts del sistema
    - Bases de datos
- Funciones/tools/Mcp
    - Resultados de funciones deterministas
    - Interacción con otros programas
- Flujos de información, Nube, Onpremise, Local
---

# Recomendaciones Gubernamentales

## ARGENTINA
- [Guía para entidades públicas y privadas en materia de Transparencia y Protección de Datos Personales para una Inteligencia Artificial responsable](https://www.argentina.gob.ar/sites/default/files/aaip-argentina-guia_para_usar_la_ia_de_manera_responsable.pdf)

## REINO UNIDO
- [Código de práctica de ciberseguridad de IA](https://www.gov.uk/government/publications/ai-cyber-security-code-of-practice/code-of-practice-for-the-cyber-security-of-ai)

---

# Orientado a Sistemas

Consideraciones para las diferentes etapas del desarrollo dentro del ciclo de vida de los sistemas de IA (Diseño del sistema, Verficicación y validación, Implementación, Operación y mantenimiento)

- Invertir en investigación para conocer buenas prácticas, formación de los equipos de trabajo y en sensibilización de los actores en general.
- Evaluar el impacto en la protección de datos personales desde el inicio, incluyendo riesgos e impactos adversos.
- Considerar la privacidad por diseño y por defecto para que sean objeto de tratamiento solo aquellos datos personales necesarios.
- Garantizar que la fuente de datos que alimentan los sistemas de IA sea lícita.
- Asegurar el tratamiento de datos personales aplicando técnicas de minimización, anonimización, cifrado, control de acceso, conservación, destrucción, entre otras.

---

# Orientado a Sistemas

- Determinar los plazos de conservación de los datos a recolectar.
- Controlar la calidad de datos y metadatos, aplicando medidas para garantizar que sean ciertos, exactos y actualizados.
- Garantizar la trazabililidad y auditabilidad de los sistemas
- Asegurar que los datos personales sean para la finalidad que motivaron su obtención.
- Promover la explicabilidad de los sistemas y garantizar la transparencia algorítmica
- Evaluar alineación con los valores, principios y orientaciones establecidas.
- Calibrar la relevancia y precisión de los datos e identificar los sesgos, pertinencia, patrones y errores del modelo algorítmico y los resultados.


---
# Orientado a Tecnologías

## Fundación OWASP (Open Worldwide Application Security Project)
- Informes extensos con tipo de vulnerabilidad con estrategias de prevención y mitigación

## [Top 10 de vulnerabilidades/riesgo de aplicacioines LLMs](https://genai.owasp.org/resource/owasp-top-10-for-llm-applications-2025/)

- Inyección de prompts (directa, indirecta, intencionales o no, jailbreak)
- Divulgación de información sensible (buscar datos de entrenamiento, filtros, guardrials)
- Cadena de suministro (integridad, sesgos, fallas del software tradicional, infra)
- Envenenamiento de datos y del modelo (manipulación de datos de entrenamiento, fine tunning, comportamiento ético del modelo)
- Manejo indadecuado de la salida (validación insuficiente, sanitización, otras aplicaciones)

---
# Orientado a Tecnologias

- Excesiva Agencia (tools, interacción con empresas/softawre, protocolo MCP)
- Fuga de prompts del sistema (passwords, credenciales, cadenas de caracteres)
- Debilidades sobre vectores y/o embeddings (Técnica RAG, generación, guardado y búsqueda)
- Desinformación (Salidas creibles pero falsa, con intencionalidad o no)
- Consumo ilimitado (Denegación del servicio, Performance, tazas limites)

## Específicos
- Protocolo MCP: Tool poisoning, Rugpull, Retrieval-agent deception (RADE), Server spoofing, cross server shadowing.[Info](https://prompthub.substack.com/p/5-mcp-security-vulnerabilities-you)

---
# Coda

#### [Cooperativa de trabajo Cambá](https://www.camba.coop)
#### José Luis Di Biase josx@camba.coop
#### Nicólas Doallo nico@camba.coop

#### PREGUNTAS Y RESPUESTAS


