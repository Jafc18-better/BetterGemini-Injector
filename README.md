# 🌌 BetterGemini - Desktop UI Customizer

**BetterGemini** es una herramienta de código abierto (Open Source) diseñada para inyectar de forma segura temas visuales personalizados en la aplicación nativa de Google Gemini para Windows. 

Dile adiós a la interfaz blanca y aburrida por defecto. Convierte tu IA en una terminal hacker, un entorno macOS minimalista, o un HUD Cyberpunk en 3D.

## 🛡️ 100% Seguro y Transparente
Este inyector fue creado con la seguridad como prioridad número uno:
- **No es malware:** Puedes revisar el código fuente completo (`inyector.py` y `app_visual.py`) en este repositorio.
- **Inyección CSS pura:** El programa *solo* inyecta hojas de estilo (CSS) en la capa visual de Electron. No altera la lógica de la IA, no roba tokens y no elude la seguridad de tu cuenta de Google.
- **Modo Seguro integrado:** Incluye un botón de "Restaurar valores de fábrica" que devuelve tu aplicación a su estado original al instante usando una copia de seguridad nativa.

## 💎 Obtén los Temas Premium
El código de este inyector es totalmente gratuito, pero requiere archivos `.css` optimizados para funcionar correctamente. 

Apoya el desarrollo adquiriendo nuestro **Pack Inicial Premium**, que incluye el instalador compilado en `.exe` (listo para usar con un clic) y el catálogo maestro de temas de alta gama:
- 🟣 **Cyber-HUD V3** (Tema estrella con animaciones de aura 3D)
- 🍏 **MacOS Minimalista** 
- 🟢 **Terminal Retro**
- 👾 **Neón Gaming Pro**
- 🌸 **Sakura Cozy V3**
- 🦇 **Dracula Oficial**
- 👑 **AMOLED Gold**

👉 **[COMPRA EL PACK PREMIUM V2 AQUÍ] (https://tu-usuario.gumroad.com/l/bettergemini](https://tu-usuario.gumroad.com/l/bettergemini)
## 🚀 Cómo usar (Para desarrolladores)
Si prefieres compilar el inyector por tu cuenta:
1. Clona este repositorio.
2. Instala los requerimientos: `pip install customtkinter`
3. Asegúrate de tener la herramienta oficial de extracción instalada globalmente: `npm install -g @electron/asar`
4. Ejecuta `python app_visual.py`.
5. Coloca tus propios archivos `.css` en una carpeta llamada `Catalogo_Temas` en el mismo directorio.

