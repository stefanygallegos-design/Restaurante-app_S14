# 🍽️ Restaurante App - Semana 14

## 📌 Descripción del proyecto

`restaurante_app` es una aplicación desarrollada en Python que permite gestionar información básica de un restaurante mediante una interfaz gráfica de usuario (GUI).

En la Semana 14 se realiza una evolución de la aplicación desarrollada anteriormente, incorporando componentes y contenedores de Tkinter y ttk para mejorar la organización, presentación y funcionalidad de la interfaz.

La aplicación mantiene una arquitectura modular, separando los modelos, servicios, datos y la interfaz gráfica. Las operaciones sobre los productos son procesadas mediante `RestauranteServicio` y la información se mantiene almacenada en archivos JSON.

---

## 🎯 Objetivo de la Semana 14

El objetivo principal es aplicar correctamente componentes y contenedores de Tkinter/ttk dentro de la aplicación `restaurante_app`.

Se busca mejorar la interfaz gráfica mediante una distribución organizada de los elementos, facilitar la interacción del usuario y mantener la separación de responsabilidades entre la interfaz, los servicios y los datos.

---

## 🛠️ Tecnologías utilizadas

- Python
- Tkinter
- ttk
- JSON
- Programación Orientada a Objetos (POO)
- GitHub

---

## 📂 Estructura del proyecto

```text
restaurante_app/
│
├── datos/
│   ├── productos.json
│   └── usuarios.json
│
├── modelos/
│   ├── __init__.py
│   ├── producto.py
│   └── usuario.py
│
├── servicios/
│   ├── __init__.py
│   ├── archivo_servicio.py
│   └── restaurante_servicio.py
│
├── ui/
│   ├── __init__.py
│   ├── login_view.py
│   └── main_view.py
│
├── main.py
└── README.md
