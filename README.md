# 🔐 Encriptador de Mensajes (Challenge Alura ONE)

> *Aplicación web interactiva de frontend diseñada para encriptar y desencriptar textos mediante reglas de sustitución de caracteres, desarrollada como parte de los retos de formación en programación.*

Este proyecto toma un mensaje de texto ingresado por el usuario, valida las restricciones de formato (solo letras minúsculas y sin acentos) y aplica un algoritmo de sustitución de vocales para convertirlo en un texto cifrado, o bien revertirlo a su forma original.

---

## 🚀 Características Principales

* **Reglas de Cifrado por Sustitución:** Reemplaza vocales específicas según las siguientes llaves predefinidas:
  * `e` ➔ `enter`
  * `o` ➔ `ober`
  * `i` ➔ `imes`
  * `a` ➔ `ai`
  * `u` ➔ `ufat`
* **Validación Dinámica:** Diseñado para procesar entradas en minúsculas de forma limpia y segura.
* **Interfaz Interactiva (UI):** Oculta elementos vacíos y muestra dinámicamente el resultado cifrado junto con un botón funcional de copiado al portapapeles.

---

## 💻 Stack Tecnológico

* **HTML5:** Estructura semántica de la interfaz de usuario.
* **CSS3:** Estilos personalizados, diseño de contenedores (*flexbox/floats*) y diseño responsivo.
* **JavaScript (Vanilla):** Lógica de manipulación del DOM, funciones de reemplazo con expresiones regulares (`RegExp`), y gestión de eventos de copiado.

---

## ⚙️ Uso y Ejecución

1. Clona o descarga este repositorio en tu computadora.
2. Abre el archivo **`index.html`** directamente en cualquier navegador web moderno.
3. Escribe tu mensaje, selecciona "Encriptar" o "Desencriptar", y utiliza el botón de copiado para llevar el resultado donde desees.

---
*Desarrollado como parte de las prácticas y retos de habilidades de programación frontend.* ✨
