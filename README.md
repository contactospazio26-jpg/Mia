# SkinCare Bot Policy

Este repo contiene la configuración central (`policy.json`) que define el estilo, tono y reglas de conversación del bot **SkinCare**.

## 📂 Archivos

- `policy.json` → define:
  - Estilo y tono (rioplatense, íntimo, amistoso).
  - Frases de apertura y recolección de datos.
  - Posicionamiento de la marca (16 años, médicos, red).
  - Política de valores y franjas.
  - Reglas de agenda y horarios sugeridos.
  - Hooks de conversación y manejo de objeciones.
  - Lenguaje permitido y prohibido.
  - Ejemplos de templates de mensajes.

- `README.md` → este archivo con las instrucciones.

## 🚀 Uso

1. Copiá el archivo `policy.json` en tu proyecto (por ejemplo, en la carpeta `prompt/`).
2. Desde tu flujo (Respond.io, script o bot), hacé un GET al archivo o incluilo directo como JSON.
3. Cuando quieras ajustar frases o reglas:
   - Editá `policy.json`.
   - Subí el cambio al repo o actualizalo en el hosting que uses (ej: GitHub Raw, Gist).
4. Probá el bot en un chat de test para verificar que las variables ($weekend_message, $faq_xxx, etc.) se lean correctamente.

## ✨ Notas

- **No usa texto inventado**: todas las frases provienen de la autora.
- **JSON válido**: se puede consumir directamente desde Respond.io o cualquier script.
- **Versionado semántico recomendado**: usá etiquetas como `v1.0.0`, `v1.1.0` cuando cambies frases o reglas.
