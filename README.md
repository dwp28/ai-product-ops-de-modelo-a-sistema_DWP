# 🤖 AI Product Ops: De Modelo a Sistema

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_svg.svg)](https://ai-appuct-ops-de-modelo-a-sistema-dwp-tgpchoqvpgkddd3gegoe4p.streamlit.app/)

Este proyecto es una plataforma interactiva diseñada para transformar el despliegue de Inteligencia Artificial de un simple "experimento técnico" a un **sistema de producción rentable, seguro y gobernable**.

## 👤 Sobre el Autor
Desarrollado por **[Tu Nombre/Usuario]**. 
Soy un apasionado de la eficiencia operativa y la implementación estratégica de IA. Puedes encontrar más de mi trabajo y conectar conmigo en mis perfiles:

* **GitHub:** [github.com/dwp28](https://github.com/dwp28)
* **Proyecto en Vivo:** [Acceder a la Web App](https://ai-appuct-ops-de-modelo-a-sistema-dwp-tgpchoqvpgkddd3gegoe4p.streamlit.app/)

---

## 🚀 ¿Qué hace esta aplicación?

Esta aplicación es una herramienta de **toma de decisiones para Product Managers y Ops**. Permite simular escenarios reales donde la elección de una IA barata puede salir cara debido a los errores humanos que genera.

### Funcionalidades Clave:
1.  **Simulador TI vs. SI:** Calcula el coste real de propiedad (TCO). Compara cuánto gastas en la API (TI) frente a cuánto gastas en humanos arreglando los fallos de la IA (SI).
2.  **Diseñador de Producto (Wizard):** Un configurador paso a paso para definir el pipeline técnico (Auth, PII, RAG, Auditoría).
3.  **Gobernanza y Roles:** Permite asignar responsabilidades críticas como el *Kill Switch Owner* (quién apaga la IA) y métricas de seguridad.
4.  **Generador de SDD:** Exporta automáticamente un *System Design Document* profesional en PDF o Markdown.

---

## 🌍 Aplicaciones en el Mundo Real

Esta herramienta es vital para sectores que manejan altos volúmenes de datos y necesitan control total:
* **Atención al Cliente (Contact Centers):** Para decidir si un modelo barato compensa el tiempo que los agentes pierden corrigiendo tickets mal clasificados.
* **Recursos Humanos:** Para implementar filtros de privacidad (PII) y asegurar que los datos de nóminas no se filtren a la IA.
* **Soporte Técnico Crítico:** Para definir umbrales de seguridad donde la IA se detiene y pide ayuda humana (*Human-in-the-loop*).

---

## 🧠 Conceptos Clave Explicados

Para entender esta app, es fundamental conocer estos pilares de **AI Product Ops**:

* **FCR (First Contact Resolution):** El porcentaje de veces que la IA resuelve el problema a la primera sin que un humano intervenga.
* **HITL (Human-in-the-Loop):** Estrategia donde un humano supervisa las respuestas de la IA, especialmente cuando la confianza del modelo es baja.
* **PII (Personally Identifiable Information):** Filtros para detectar y anonimizar datos sensibles (DNI, tarjetas, nombres) antes de enviarlos a la nube.
* **Kill Switch:** Un mecanismo de emergencia que permite detener el sistema de IA instantáneamente si se detecta un comportamiento anómalo o peligroso.
* **SLO (Service Level Objective):** El compromiso de calidad del sistema, por ejemplo, que la IA responda siempre en menos de 2 segundos.

---

## 🛠️ Instalación y Uso Local

Si deseas ejecutar este proyecto en tu propia máquina:

1.  **Clona el repositorio:**
    ```bash
    git clone [https://github.com/dwp28/ai-product-ops-de-modelo-a-sistema.git](https://github.com/dwp28/ai-product-ops-de-modelo-a-sistema.git)
    ```
2.  **Instala las dependencias necesarias:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Lanza la aplicación con Streamlit:**
    ```bash
    streamlit run app.py
    ```

---
*Este proyecto ha sido desarrollado como parte de un programa especializado en AI Product Ops, enfocado en pasar de "modelos que funcionan en el chat" a "sistemas que funcionan en la empresa".*
