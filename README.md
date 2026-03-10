# biblioteca-AR
# Sistema de Gestión de Libros en Python

Este proyecto es un programa sencillo desarrollado en **Python** que permite registrar y gestionar información básica de un libro. El sistema muestra los datos del libro y permite actualizar su número de páginas.

## 📌 Descripción

El programa utiliza **Programación Orientada a Objetos (POO)** mediante la clase `Libro`.
Cada objeto de esta clase representa un libro con la siguiente información:

* Título
* Autor
* Número de páginas

El programa permite mostrar la información del libro y actualizar la cantidad de páginas si es necesario.

---

## 🧠 Conceptos utilizados

En este proyecto se aplican conceptos básicos de **Python**:

* Clases y Objetos
* Método constructor `__init__`
* Métodos de clase
* Condicionales (`if / else`)
* Uso de atributos de objeto
* Ejecución del programa con `if __name__ == "__main__"`

---

## 📂 Estructura del Proyecto

```
gestion-libros/
│
├── libro.py
└── README.md
```

---

## ⚙️ Requisitos

Para ejecutar este programa necesitas tener instalado:

* **Python 3.x**

Puedes verificar tu versión con el siguiente comando:

```bash
python --version
```

---

## ▶️ Cómo ejecutar el programa

1. Clona el repositorio:

```bash
git clone https://github.com/tu-usuario/gestion-libros.git
```

2. Entra en la carpeta del proyecto:

```bash
cd gestion-libros
```

3. Ejecuta el programa:

```bash
python libro.py
```

---

## 💻 Ejemplo de ejecución

```
========================================
INFORMACIÓN DEL LIBRO
========================================
Título: Cien Años de Soledad
Autor: Gabriel García Márquez
Número de páginas: 417
========================================

El número de páginas ha sido actualizado a: 422
```

---

## 📚 Métodos de la clase `Libro`

### `mostrar_informacion()`

Muestra en pantalla los datos del libro: título, autor y número de páginas.

### `actualizar_paginas(nuevo_numero_paginas)`

Permite modificar el número de páginas del libro, siempre que el valor sea mayor que 0.

---

## 👨‍💻 Autor

Proyecto desarrollado como práctica de **Programación en Python y Programación Orientada a Objetos (POO)**.

---

## 📄 Licencia

Este proyecto es de uso educativo y puede ser modificado libremente.
