# 💸 Platini 💸

![Platini Bot](/Logo_resized.png)

> **Platini** es un bot inteligente de Telegram desarrollado en Python, diseñado para ayudarte a **gestionar tus finanzas personales**, registrar gastos automáticamente, analizar patrones de consumo, generar alertas, y mucho más.

---

## 🚀 Características principales

✅ Registro de gastos con texto, voz o fotos
✅ OCR para leer tickets de supermercado y desglosarlos
✅ Clasificación automática por categoría 
✅ Distribución 50/30/20 con alertas financieras
✅ Gráficos mensuales y resúmenes 
✅ Almacenamiento en Google Sheets 
✅ Panel de visualización con React + Tailwind

---

## ✨ Comandos del bot

```
/start - Registrar usuario
/ingreso - Cargar un ingreso
/estado - Ver porcentajes de gasto (50/30/20)
/resumen - Ver resumen mensual
/grafico - Ver gráfico por categoría
/configurar - Configurar límites de tarjetas
/ayuda - Ver todos los comandos
```

---

## 🧠 Clasificación inteligente

El bot analiza el contenido de los mensajes o tickets para clasificar automáticamente según palabras clave. Algunas categorías soportadas:

* **Vivienda:** alquiler, departamento
* **Delivery:** rappi, pedido ya
* **Transporte:** sube, colectivo, uber
* **Salud:** farmacia, hospital
* **Mascotas:** veterinaria, perros
* **Supermercado:** tickets escaneados (detalle por ítem)

---

## 🛠️ Tecnologías utilizadas

| Herramienta                           | Uso                               |
| ------------------------------------- | --------------------------------- |
| `python-telegram-bot`                 | Framework principal del bot       |
| `Tesseract OCR`                       | Lectura de tickets desde imágenes |
| `Whisper`                             | Transcripción de audios a texto   |
| `Google Sheets + gspread`             | Persistencia de datos en la nube  |
| `matplotlib`                          | Generación de gráficos            |
| `React + Vite + Tailwind + Shadcn/ui` | Panel web (frontend de gastos)    |

---

## 🖥️ Requisitos

* Python 3.10+
* Tesseract instalado y disponible en PATH
* Google API Key + credenciales `credentials.json`
* Archivo `.env` con el `BOT_TOKEN` y claves necesarias

---

## ⚙️ Instalación

```bash
git clone https://github.com/tuusuario/platini-bot.git
cd platini-bot
python -m venv venv
source venv/bin/activate   # en Windows: venv\Scripts\activate
pip install -r requirements.txt
```

Configurá `.env` con tus credenciales y ejecutá:

```bash
python bot_gastos.py
```

---

## 🌐 Frontend (opcional)

Visualización web:

```bash
cd gastos-front
npm install
npm run dev
```

---

## 🧾 Licencia

MIT © 2025 Natalia – Proyecto personal para automatizar la gestión financiera desde Telegram.

---

## 📬 Contacto

Abrir bot:
💸 [@platini\_bot](https://t.me/natigastabot)
