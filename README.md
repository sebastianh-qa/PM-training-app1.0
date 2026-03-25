# PM Training App – 2024 Operations Standards

¡Bienvenido/a a mi primer proyecto! 🚀  
Esta aplicación web de entrenamiento está basada en los **2024 Property Management Operations Standards**. Su propósito es ayudar a nuevos empleados de property management a aprender los procesos clave a través de micro‑learning, práctica interactiva y evaluaciones.

## 🎯 Enfoque principal: Testing

Este proyecto es mi punto de partida en el mundo del testing de software.  
He priorizado:

- **Pruebas de funcionalidad**: navegación, guardado de progreso, lógica de práctica y quiz.
- **Validación de datos**: uso de `data.json` como fuente única de verdad.
- **Experiencia de usuario**: feedback inmediato en escenarios de práctica y aleatorización de preguntas para evitar memorización por descarte.
- **Persistencia**: el progreso se guarda en `localStorage`, permitiendo retomar el entrenamiento en cualquier momento.

## 🧰 Tecnologías

- HTML5, CSS3, JavaScript (vanilla)
- Almacenamiento local (`localStorage`)
- Datos en JSON
- Despliegue continuo con Vercel + GitHub

## 📁 Estructura del proyecto



## 🚀 Cómo ejecutarlo localmente

1. Clona este repositorio  
2. Abre `index.html` en tu navegador  
3. No requiere instalación ni servidor

## 🌐 Despliegue

El proyecto está desplegado automáticamente en Vercel.  
Cada `push` a la rama `main` genera una nueva versión en la URL pública.

## 📖 Sobre los módulos

Los módulos siguen el orden del manual original:

1. Unit Onboarding  
2. Make Ready  
3. Turnover  
4. Leasing (Marketing + Applications)  
5. Maintenance Request  
6. Communications  
7. Delinquency  
8. Portfolio Metrics

Cada módulo incluye:

- **Métricas clave** (qué miden, cómo calcularlas, objetivos median y top 25%)
- **Key Notes, Definitions & Nuances** (en un mismo paso para mayor claridad)
- **Práctica** con escenarios realistas (feedback inmediato)
- **Quiz final** (3 preguntas aleatorias de un pool de 9, se necesita 80% para aprobar)

## 🔒 Reinicio de progreso

Los administradores pueden restablecer todo el progreso haciendo clic en el botón "Reset lessons" (contraseña: `tryagain`).

---

Hecho con ❤️ como parte de mi aprendizaje en testing y desarrollo frontend.
