# 💉 Calculadora CRI Veterinaria

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**Calculadora de Infusión a Ritmo Constante (CRI) para uso veterinario.**  
Determina de forma rápida y precisa el volumen de fármaco que debes añadir a una bolsa de suero para administrar una dosis objetivo continua.

---

## 📸 Vista previa

![Preview de la calculadora](https://raw.githubusercontent.com/DavidLora2000/calculadora-cri/refs/heads/main/captura_ejemplo_1.png)

---

## 🎯 ¿Qué es una CRI?

Una **CRI** (*Constant Rate Infusion*) es la administración intravenosa continua de un fármaco a un ritmo fijo, con el fin de mantener niveles plasmáticos estables. Es ampliamente utilizada en veterinaria para:

- Analgesia
- Sedación
- Antiarrítmicos
- Inotrópicos
- Gastroprotectores

---

## 🚀 Características

- ✅ Interfaz limpia, moderna y responsive.
- ✅ Cálculo automático del volumen de fármaco a añadir y velocidad de infusión.
- ✅ Selectores rápidos para volumen de suero, duración, dosis y concentración.
- ✅ Cambio dinámico de unidades: **µg/kg/min** ↔ **mg/kg/min**.
- ✅ Botones predefinidos para los valores más utilizados en clínica.
- ✅ Mensajes de error y validación de datos.
- ✅ Aviso legal integrado.
- ✅ 100% offline, sin dependencias externas.

---

## 🧪 Fórmula utilizada

$$
\text{Vol. a añadir (ml)} = \frac{D \times P \times 60 \times V_{\text{bolsa}}}{R \times C}
$$

Donde:

- **D** = dosis (mg/kg/min)
- **P** = peso del paciente (kg)
- **V bolsa** = volumen total del suero (ml)
- **R** = velocidad de administración (ml/h)
- **C** = concentración del fármaco (mg/ml)

> La velocidad de infusión se obtiene automáticamente al dividir el volumen de la bolsa entre la duración deseada.

---

## 🧰 Cómo usar

1. Abre el archivo `index.html` en cualquier navegador.
2. Introduce el **peso** del paciente.
3. Selecciona la **duración** de la CRI (puedes usar los botones rápidos 8h / 12h / 24h o escribir un valor personalizado).
4. Elige el **volumen del suero** (50, 100, 250 o 500 ml, o escribe el tuyo).
5. Establece la **dosis** y la **unidad** (µg/kg/min o mg/kg/min) con los botones o manualmente.
6. Indica la **concentración del fármaco** (0.5, 10, 20, 50 mg/ml o personalizada).
7. Pulsa **"Calcular volumen a añadir"** o simplemente cambia cualquier valor (el cálculo es automático).
8. El resultado mostrará:
   - 💧 Volumen de fármaco a añadir al suero.
   - ⏲️ Velocidad de infusión para respetar la duración.
   - 📋 Resumen detallado de la preparación.

---

## 📂 Estructura del proyecto

- **index.html** – Archivo principal que contiene todo el código (HTML, CSS, JavaScript).
- **README.md** – Documentación del proyecto.
- **captura_ejemplo_1.png** - Imagen de ejemplo.

---

## 🛠️ Tecnologías

- **HTML5** semántico.
- **CSS3** personalizado con diseño responsivo (flexbox, grid, pseudo-elementos, transiciones).
- **JavaScript** vanilla para la lógica de cálculo y la interactividad de los botones.

---

## ⚠️ Aviso legal / Disclaimer

> **Esta calculadora es una herramienta de apoyo.**  
> Las dosis deben ser revisadas y validadas por un profesional veterinario.  
> El creador no se hace responsable de posibles errores, omisiones o del uso clínico de los resultados obtenidos.

---

## 🐾 Agradecimientos

Gracias a Lidia por sus apoyo a las mejoras de la calculadora.
