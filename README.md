# 📊 Análisis de DNIs y Años de Nacimiento con Python

## 👥 Autores

- **Andrés Piuzzi**
- **Pablo León**

## 🎓 Cátedra

> Materia: Matemática
> Carrera: Tecnicatura Universitaria en Programación  
> Universidad Tecnológica Nacional (UTN)  
> Comisión 16 – Año 2025  
> Profesora: Ethel Carina R. Jovanovich  
> Tutor: Cristian Mut

---

## 📌 Descripción general

Este script en Python realiza un análisis lógico y matemático sobre una lista de DNIs y años de nacimiento utilizando:

- Teoría de conjuntos
- Condicionales lógicas
- Frecuencias y sumas de dígitos
- Comparaciones entre pares
- Evaluación de años pares, impares y bisiestos
- Producto cartesiano entre años y edades actuales

El objetivo es aplicar fundamentos de conjuntos, lógica y programación sobre datos reales de manera didáctica.

---

## 📦 Requisitos

- Python 3.7 o superior
- No requiere librerías externas. Se utilizan únicamente módulos estándar:
  - `itertools`
  - `datetime`

## 🧾 Datos utilizados

python
`dnis = ["31568054", "36054031"]
años_nacimientos = [2003, 1999, 2000]`

## ⚙️ Estructura del programa

| Sección | Descripción |
|--------|-------------|
| **1. Creación de conjuntos** | Convierte cada DNI en un conjunto de dígitos únicos para facilitar el análisis |
| **2. Operaciones entre conjuntos** | Se calcula la unión, intersección, diferencias y diferencia simétrica entre los DNIs |
| **3. Suma y frecuencia de dígitos** | Se calcula la suma total de los dígitos y cuántas veces aparece cada uno en cada DNI |
| **4. Evaluación lógica** | Se analizan características como la diversidad numérica, presencia del 0 y la paridad del conjunto |
| **5. Análisis de años de nacimiento** | Se evalúa si los años son pares o impares, si forman parte del grupo Z (nacidos después del 2000), y si alguno es bisiesto |
| **5.1 Producto cartesiano** | Se cruza cada año de nacimiento con todas las edades posibles al año actual |

---

## 📎 Anexos

**🎥 Video explicativo:**  
[Ver en YouTube](https://www.youtube.com/watch?v=ZkS6nut9DOk)
