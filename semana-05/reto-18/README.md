# 🧩 Reto 18: Juego de Adivinar el Número

## 🎯 Objetivo
Aprender flujo lógico y control de estado en JS.

## 📋 Requisitos
- Número secreto entre 1 y 100.
- Input para intento y botón "Probar".
- Muestra mensajes "Mayor", "Menor" o "¡Correcto!".
- Límite de 10 intentos + botón "Reiniciar".

## ✅ Criterios de evaluación
- Variables de estado bien definidas.
- Reinicio funcional sin recargar página.
- Interfaz clara y retroalimentación visual.

## 🧠 Planificación
- Generar número aleatorio con `Math.floor(Math.random()*100)+1`.
- Contador de intentos y función `checkGuess()`.
- Reset de estado.

## 💡 Tip
Usa clases CSS (`.success`, `.error`) para cambiar color del feedback.
