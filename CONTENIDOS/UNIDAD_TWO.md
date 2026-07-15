# 🔀 Métodos de Simplificación de Expresiones Lógicas

## 📖 Introducción

El presente portafolio académico tiene como propósito consolidar y exponer los conocimientos adquiridos en el área del **diseño de circuitos digitales**, específicamente en los métodos de simplificación de expresiones lógicas. Estos procedimientos constituyen una base fundamental para el desarrollo de sistemas digitales más eficientes, ya que permiten reducir la cantidad de compuertas lógicas necesarias para implementar una función booleana.

Dentro de este contexto, la simplificación de expresiones lógicas desempeña un papel esencial en la electrónica digital y la arquitectura de computadores, debido a que optimiza el diseño de circuitos, disminuye costos de implementación y mejora el rendimiento de los sistemas digitales.

En este repositorio se presenta una fundamentación teórica de los dos métodos más utilizados para simplificar funciones booleanas:

- **Álgebra Booleana**
- **Mapas de Karnaugh**

Además, se describen sus definiciones, propiedades, principios fundamentales y aplicaciones prácticas en el diseño de circuitos digitales.

---

# 🧮 1. Simplificación mediante Álgebra Booleana

## ¿Qué es el Álgebra Booleana?

El **Álgebra Booleana** es una rama de las matemáticas desarrollada por George Boole que permite representar y manipular expresiones lógicas utilizando variables binarias, cuyos únicos valores posibles son:

```text
0 = Falso
1 = Verdadero
```

Este método se basa en la aplicación de leyes y propiedades matemáticas para transformar una expresión lógica compleja en otra equivalente, pero con una menor cantidad de términos y operaciones.

---

## Principales Leyes del Álgebra Booleana

### 📌 Ley de Identidad

Permite mantener el valor original de una variable al operar con los elementos neutros.

```text
A + 0 = A
A · 1 = A
```

---

### 📌 Ley de Dominación

Indica que ciertos valores dominan completamente el resultado de una operación lógica.

```text
A + 1 = 1
A · 0 = 0
```

---

### 📌 Ley del Complemento

Establece la relación entre una variable y su complemento.

```text
A + A' = 1
A · A' = 0
```

---

### 📌 Ley Idempotente

Una variable operada consigo misma conserva su valor.

```text
A + A = A
A · A = A
```

---

### 📌 Ley Conmutativa

El orden de las variables no altera el resultado de la operación.

```text
A + B = B + A
A · B = B · A
```

---

### 📌 Ley Asociativa

Permite reagrupar operaciones sin modificar el resultado.

```text
(A + B) + C = A + (B + C)

(A · B) · C = A · (B · C)
```

---

### 📌 Ley Distributiva

Relaciona las operaciones de suma y producto lógico.

```text
A(B + C) = AB + AC

A + BC = (A + B)(A + C)
```

---

### 📌 Teoremas de De Morgan

Son fundamentales para transformar expresiones que contienen complementos.

```text
(A · B)' = A' + B'

(A + B)' = A' · B'
```

Estos teoremas son ampliamente utilizados para simplificar circuitos digitales y facilitar su implementación.

---

# 🗺️ 2. Simplificación mediante Mapas de Karnaugh

## ¿Qué es un Mapa de Karnaugh?

El **Mapa de Karnaugh**, también conocido como **K-Map**, es una herramienta gráfica utilizada para simplificar funciones booleanas de forma visual.

Este método organiza los valores de una tabla de verdad en una cuadrícula especialmente diseñada para identificar agrupaciones de unos (1) o ceros (0), permitiendo obtener expresiones lógicas mínimas de manera más sencilla.

---

## Funcionamiento del Método

El procedimiento consiste en:

1. Construir la tabla de verdad.
2. Trasladar los valores al mapa de Karnaugh.
3. Agrupar celdas adyacentes que contengan valores iguales.
4. Obtener la expresión lógica simplificada a partir de los grupos formados.

---

## Clasificación de los Mapas de Karnaugh

### 📌 Mapas de 2 Variables

Están conformados por cuatro celdas y permiten simplificar funciones sencillas.

Se utilizan principalmente como introducción al método.

---

### 📌 Mapas de 3 Variables

Poseen ocho celdas organizadas según el código Gray.

Permiten resolver funciones con un mayor número de combinaciones.

---

### 📌 Mapas de 4 Variables

Constan de dieciséis celdas y representan uno de los formatos más utilizados en electrónica digital.

Facilitan la simplificación de funciones de complejidad media.

---

### 📌 Mapas de 5 o más Variables

Para funciones de mayor tamaño se emplean múltiples mapas de Karnaugh.

Aunque siguen siendo efectivos, su utilización resulta más compleja y normalmente se complementa con herramientas computacionales.

---

# ⚙️ Comparación entre ambos métodos

| Característica | Álgebra Booleana | Mapas de Karnaugh |
|----------------|------------------|-------------------|
| Método de trabajo | Manipulación algebraica | Representación gráfica |
| Nivel de dificultad | Medio | Bajo para funciones pequeñas |
| Número de variables | Sin límite práctico | Recomendado hasta 5 variables |
| Precisión | Depende del dominio de las leyes | Reduce errores visualmente |
| Aplicación principal | Simplificación manual y análisis matemático | Diseño y optimización de circuitos digitales |

---

# 🎯 Objetivo del Portafolio

El estudio de los métodos de simplificación de expresiones lógicas constituye una parte esencial en la formación de los futuros profesionales de la ingeniería, ya que proporciona las herramientas necesarias para diseñar circuitos digitales más eficientes, reduciendo la cantidad de componentes utilizados y optimizando el funcionamiento de los sistemas electrónicos.

Los ejercicios y casos prácticos desarrollados en este portafolio tienen como finalidad demostrar la aplicación de los conceptos teóricos mediante la resolución paso a paso de problemas de simplificación lógica, fortaleciendo la comprensión del Álgebra Booleana y los Mapas de Karnaugh como herramientas fundamentales en el análisis y diseño de circuitos digitales.

---
# 📂 Actividades del Curso

En esta sección se encuentran organizadas las actividades desarrolladas durante la unidad de **Métodos de Simplificación de Expresiones Lógicas**. Cada apartado contiene un enlace a la carpeta correspondiente en Google Drive, donde se encuentran almacenados los documentos, informes y evidencias elaboradas en grupo.

---

## 📘 Actividad Autónoma (AA)

**Descripción**

Actividad desarrollada de forma colaborativa como parte del aprendizaje autónomo, orientada al fortalecimiento de los conocimientos teóricos y prácticos sobre los métodos de simplificación de expresiones lógicas.

🔗 **Acceder a la actividad**

[📁 Abrir carpeta en Google Drive](https://drive.google.com/drive/folders/1iiykdLlTB67eN8fgFDTshBXkDswdsZmc?usp=sharing)

---

## 👨‍🏫 Actividad en Contacto con el Docente (ACD)

**Descripción**

Actividad desarrollada bajo el acompañamiento del docente, en la cual se aplican los conceptos estudiados mediante ejercicios guiados y actividades colaborativas.

🔗 **Acceder a la actividad**

[📁 Abrir carpeta en Google Drive](https://drive.google.com/drive/folders/1GOt1Smb-XpQdjt8x0TdyeS56tesFkOxK?usp=sharing)

---

## 🧪 Aprendizaje Práctico Experimental (APE) – Fases 1 a 6

**Descripción**

Compilación de las actividades correspondientes al Aprendizaje Práctico Experimental (APE), desarrolladas de forma grupal durante las diferentes fases de la asignatura.

### 📌 Fases 1 – 2

🔗 **Acceder a la actividad**

[📁 Abrir carpeta en Google Drive](https://drive.google.com/drive/folders/13KMqNHtzZcRpIYKlUffDRVZMZgucFQVp?usp=sharing)

---

### 📌 Fases 3 – 4

🔗 **Acceder a la actividad**

[📁 Abrir carpeta en Google Drive](https://drive.google.com/drive/folders/1H_gFvCIt_Nzbd0QyEe2apByZEfJNYCKh?usp=sharing)

---

### 📌 Fases 5 – 6

🔗 **Acceder a la actividad**

[📁 Abrir carpeta en Google Drive](https://drive.google.com/drive/folders/1IgN_8q0yWykL7_gXU-vEvT6DVpy43Swe?usp=sharing)

---

> **Nota:** Todas las carpetas de Google Drive contienen los documentos, informes, ejercicios y demás evidencias correspondientes a las actividades desarrolladas durante esta unidad de aprendizaje.

---
