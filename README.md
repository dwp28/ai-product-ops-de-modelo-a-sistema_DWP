# AI Product Ops: De Modelo a Sistema (Streamlit)

App didáctica para obligar decisiones de diseño (trade-offs) en sistemas IA:

- Framework (People/Process/Data/Tech/Policy)
- Simulador TI vs SI (coste API vs retrabajo humano)
- Wizard de diseño (pipeline, roles, métricas, guardrails)
- Auditoría y reporte (SDD en Markdown/PDF)

## Ejecutar (local)

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Desplegar (Streamlit Community Cloud)

1.  En tu workspace, pulsa **Create app**, elige repo/branch y el entrypoint app.py.
2.  En **Advanced settings**, selecciona versión de Python y pega secretos si los hubiera.

(Ver documentación oficial de Deploy + Python version + Secrets.)