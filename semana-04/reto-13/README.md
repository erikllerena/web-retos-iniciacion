# 🧩 Reto 13: Modal Accesible

## 🎯 Objetivo
Aprender control del foco y cierre accesible (`Esc`, clic fuera).

## 📋 Requisitos
- Modal abre/cierra con botón.
- `aria-modal="true"`, `role="dialog"`.
- Foco atrapado dentro del modal.
- Devuelve foco al botón al cerrar.

## ✅ Criterios de evaluación
- Overlay clic-out cierra correctamente.
- Navegable con teclado.
- Scroll del fondo bloqueado.

## 💡 Tip
Usa `tabindex="-1"` y controla foco con `focus()` y `keydown`.
