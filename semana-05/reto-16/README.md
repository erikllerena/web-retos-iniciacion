# 🧩 Reto 16: Generador de Contraseñas

## 🎯 Objetivo
Practicar lógica, manipulación del DOM y manejo de eventos en JavaScript.

## 📋 Requisitos
- Campo numérico para la longitud (6–24 caracteres).
- Checkboxes: mayúsculas, minúsculas, números, símbolos.
- Botón "Generar" y botón "Copiar al portapapeles".
- Validar mínimo una opción seleccionada.

## ✅ Criterios de evaluación
- Uso correcto de `Math.random()` y concatenación de strings.
- Validaciones y manejo de errores visuales.
- Feedback visual al copiar (mensaje o toast).

## 🧠 Planificación
- Diseña estructura: inputs arriba, resultado al centro, botones abajo.
- Crea una función `generatePassword(options)`.
- Define rangos ASCII o sets de caracteres.

## 💡 Tip
Usa `navigator.clipboard.writeText()` para copiar y prueba con un efecto CSS para feedback visual.
