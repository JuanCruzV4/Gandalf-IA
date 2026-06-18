# 🧙‍♂️ Gandalf AI Chatbot

¡Bienvenido a la morada de Gandalf AI! Este proyecto es un chatbot de inteligencia artificial con una interfaz web amigable, diseñado con la sabiduría y el humor del legendario mago de J.R.R. Tolkien. 

Una característica destacada de este proyecto es su **sistema de respaldo (fallback) automático**: utiliza la API de Google Gemini como motor principal, pero si la conexión con Valinor se debilita (falla la API o no hay internet), recurre automáticamente a magia local utilizando Ollama.

## ✨ Características Principales

* **Personalidad Única:** Responde como Gandalf, combinando asistencia experta con el tono del universo de El Señor de los Anillos.
* **Motor Principal (Nube):** Utiliza `gemini-2.5-flash` a través de la API compatible de OpenAI para respuestas rápidas y de alta calidad.
* **Respaldo Local (Offline):** Si la API de Google falla o falta la clave, el sistema cambia automáticamente a un modelo local usando Ollama (`qwen2.5`).
* **Interfaz Gráfica:** Construido con **Gradio 6.0** para ofrecer una experiencia de chat moderna, fluida y fácil de usar.

## 🛠️ Requisitos Previos

Antes de ejecutar el proyecto, asegúrate de tener instalado lo siguiente:

1. **Python 3.8 o superior.**
2. **Ollama:** Descargado e instalado en tu computadora (para el respaldo local).
   * Debes tener descargado el modelo Qwen 2.5. Puedes hacerlo corriendo en tu terminal:
```bash
     ollama run qwen2.5
```
3. **Clave de API de Google Gemini** (Google AI Studio).

## 🚀 Instalación y Configuración

Sigue estos pasos para levantar el proyecto en tu máquina local:

**1. Clonar el repositorio**
```bash
git clone [https://github.com/JuanCruzV4/Gandalf-IA.git](https://github.com/JuanCruzV4/Gandalf-IA.git)
cd Gandalf-IA
