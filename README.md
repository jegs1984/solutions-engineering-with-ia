## local tests

# Ingeniería de Soluciones con Inteligencia Artificial

Este repositorio contiene todos los materiales, ejemplos y prácticas del curso **Ingeniería de Soluciones con Inteligencia Artificial**. El curso está organizado en tres grandes módulos (RA), cada uno con submódulos (IL) y ejemplos prácticos en Python y Jupyter.

---

## 📚 Descripción General

El curso cubre desde los fundamentos de la IA generativa y el prompt engineering, hasta el desarrollo de agentes inteligentes y las mejores prácticas para llevar soluciones a producción, incluyendo observabilidad, seguridad y ética.

- **Nivel:** Intermedio
- **Modalidad:** Práctica y conceptual
- **Requisitos:** Python básico, interés en IA

---

## 🏗️ Estructura del Proyecto

```
RA1/  # Fundamentos de IA Generativa y Prompt Engineering
  IL1.1/  # Introducción a LLMs y APIs
  IL1.2/  # Técnicas de prompting
  IL1.3/  # Infraestructura RAG
  IL1.4/  # Evaluación y optimización

RA2/  # Desarrollo de Agentes Inteligentes
  IL2.1/  # Arquitectura y frameworks (LangChain, CrewAI)
  IL2.2/  # Memoria y herramientas externas
  IL2.3/  # Planificación y orquestación
  IL2.4/  # Documentación técnica y arquitectura

RA3/  # Observabilidad, Seguridad y Ética
  IL3.1/  # Observabilidad y métricas
  IL3.2/  # Trazabilidad y logs
  IL3.3/  # Seguridad y ética
  IL3.4/  # Escalabilidad y sostenibilidad
```

Cada subcarpeta IL contiene ejemplos en Python (`.py`), notebooks (`.ipynb`) o guías (`.md`).

---

## 🚦 ¿Cómo usar este repositorio?

1. **Lee los README.md** de cada carpeta para entender el objetivo de cada módulo.
2. **Ejecuta los ejemplos Python** en tu entorno local (requiere Python 3.8+ y, para algunos ejemplos, instalar dependencias como `langchain`, `crewai`, `openai`).
3. **Configura tus variables de entorno** si usas APIs (ver sección de variables en este README).
4. **Explora los notebooks** para prácticas guiadas y experimentos.
5. **Consulta los archivos `.md`** para teoría, mejores prácticas y requisitos de cada entrega.

---

## ⚙️ Requisitos y dependencias

- Python 3.8+
- Jupyter Notebook (opcional, para `.ipynb`)
- Instalar dependencias según el módulo:
  - `pip install langchain openai crewai` (para agentes y ejemplos avanzados)
  - Otros: `pandas`, `requests`, etc.

### Variables de entorno recomendadas
- `OPENAI_API_KEY` (para ejemplos con OpenAI/LangChain)
- `GITHUB_TOKEN` (para ejemplos con GitHub API)

---

## 🧭 Navegación recomendada

- **Empieza por RA1** si eres nuevo en IA generativa y prompting.
- **RA2** es ideal para aprender a construir agentes inteligentes y documentar soluciones.
- **RA3** te prepara para llevar tus agentes a producción, monitorear, asegurar y escalar.
- Cada IL tiene ejemplos autocontenidos y README propio.

---

## 📑 Evaluaciones y entregables

- Quizzes teóricos en cada RA
- Proyectos prácticos y presentaciones
- Proyecto final transversal (40% de la nota)

---

## 📖 Recursos adicionales

- [LangChain Docs](https://python.langchain.com/)
- [CrewAI Docs](https://docs.crewai.com/)
- [OpenAI API](https://platform.openai.com/docs/)
- [Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)

---

## 📝 Sobre este repositorio

- Inspirado en buenas prácticas de ingeniería y educación en IA.
- Estructura y progresión pensadas para aprendizaje autónomo y colaborativo.
- Para dudas, sugerencias o mejoras, abre un issue o pull request.

---

¡Explora, experimenta y aprende a construir soluciones de IA listas para producción! 