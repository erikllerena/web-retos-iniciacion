# 🧩 Reto 21: App del Clima (API real)

## 🎯 Objetivo
Aprender peticiones asíncronas y renderizado de datos.

## 📋 Requisitos
- Input para ciudad.
- Botón "Buscar" que consulte una API (ej. OpenWeatherMap).
- Mostrar temperatura, descripción e ícono.
- Estados: cargando, error, éxito.

## ✅ Criterios de evaluación
- Uso de `async/await` con manejo de errores.
- Limpieza del DOM antes de renderizar.
- Persistencia de última búsqueda en `localStorage`.

## 🧠 Planificación
- Función `fetchWeather(city)`.
- Elementos `#loading`, `#error`, `#result`.

## 💡 Tip
Usa `try/catch/finally` para manejar errores y mostrar siempre un estado visual.
