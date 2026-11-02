# Bitácora de Uso de Herramientas de Inteligencia Artificial

- **Proyecto:** UberClone — Versión Conductor[cite: 1]
- **Plataforma:** React Native con Expo[cite: 1]
- **Integrantes:** Yeison David Uribe Tobon y Jhon Fernando Oquendo Holguin
---

### Entrada #1
- **Fecha:** 2026-11-01
- **Integrante:** Yeison David Uribe Tobon
- **Herramienta:** Asistente IA
- **Objetivo:** Inicializar manualmente la arquitectura base del proyecto en Git y consultar la convención de variables públicas en Expo.
- **Prompt:** "¿Cómo se configuran las variables públicas en Expo y cuál es la lista de variables recomendada para .env.example en un proyecto con mapas y pagos?"
- **Resumen de la respuesta:** Se explicó el uso del prefijo `EXPO_PUBLIC_` para exponer variables seguras al cliente de React Native y se listaron las claves sugeridas para el archivo `.env.example`.
- **Qué se usó / modificó / descartó:** Realicé la inicialización del proyecto con Expo, el setup de Git y la estructura de carpetas. Usé la IA únicamente para validar el prefijo `EXPO_PUBLIC_` y armar el `.env.example`. Se descartó cualquier código autogenerado.
- **Archivos y commit:** `package.json`, `.env.example`, `docs/AI_LOG.md` - [Hash de tu commit]
- **Verificación:** Proyecto compilado en entorno local de VS Code y archivo `.env.example` comprobado.
- **Aprendizaje:** Reafirmé el flujo de inicialización en Expo y comprendí cómo el prefijo `EXPO_PUBLIC_` evita la exposición accidental de claves privadas en el repositorio.