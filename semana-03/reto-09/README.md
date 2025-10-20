# 🧩 Reto 09: Temporizador (mm:ss)

## 🎯 Objetivo
Practicar temporizadores (`setInterval`) y formato de tiempo.

## 📋 Requisitos
- Botones: Start / Stop / Reset.
- Muestra tiempo formateado mm:ss.
- Evita múltiples intervalos activos.

## ✅ Criterios de evaluación
- Lógica clara de control de estado.
- `Date.now()` o timestamp como referencia.
- No drift visible.

## 💡 Tip
Usa `Math.floor(ms / 1000)` y `padStart(2, "0")` para formato.
