# 🧩 Reto 17: Conversor de Monedas (sin API)

## 🎯 Objetivo
Aplicar funciones matemáticas, validaciones y formateo numérico.

## 📋 Requisitos
- Input de cantidad.
- Selects de moneda origen y destino (USD, EUR, PEN).
- Conversión usando tasas internas en JS.
- Botón "Convertir" y resultado con formato local.

## ✅ Criterios de evaluación
- Función pura `convert(amount, from, to)` clara y reutilizable.
- Validaciones para valores negativos o vacíos.
- Formateo con `Intl.NumberFormat`.

## 🧠 Planificación
- Define un objeto `rates = { USD: 1, EUR: 0.9, PEN: 3.7 }`.
- Multiplica/divide según selección.
- Separa lógica de UI.

## 💡 Tip
Aplica `parseFloat()` con cuidado y limita decimales con `.toFixed(2)`.
