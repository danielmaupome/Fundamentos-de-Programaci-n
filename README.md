# 🐍 Fundamentos de Programación: Unidad 2 - Introducción a la Programación

¡Bienvenido al repositorio de **Fundamentos de Python**! Este proyecto contiene una colección de ejemplos prácticos y didácticos diseñados para comprender las bases del lenguaje antes de introducir sentencias de selección (`if`/`else`) o estructuras repetitivas.

---

## 🎯 Objetivos de Aprendizaje

La competencia que se pretende alcanzar es **Conoce y aplica un lenguaje de programación para la resolución de problemas.**

Para ello, tenemos estos ejemplos diseñados

## 🎯 Objetivos de Aprendizaje

1. **Salida Básica y Caracteres de Escape:** Comprender el funcionamiento de `print()`, el uso de comillas simples/dobles y secuencias de escape como `\n` y `\t`[cite: 1].
2. **Variables y Tipos de Datos:** Identificar la tipificación dinámica de Python (`int`, `float`, `str`, `bool`), aplicar concatenación o suma según el tipo de dato e inspeccionar tipos con `type()`[cite: 2].
3. **Entrada de Datos y Conversión de Tipos (*Casting*):** Leer datos desde teclado con `input()` y realizar conversiones explícitas a enteros (`int`) y flotantes (`float`).
4. **Operadores Aritméticos y Jerarquía:** Comprender la prioridad de evaluación operacional ($() \rightarrow ** \rightarrow *, /, //, \% \rightarrow +, -$), así como el comportamiento de la división entera (`//`), módulo (`%`) y repetición de cadenas (`*`)[cite: 4].
5. **Asignación Compuesta:** Aplicar atajos sintácticos (`+=`, `-=`, `*=`, `/=`, `//=`, `%=`) para la actualización acumulativa de variables[cite: 5].
6. **Manipulación de Cadenas e Inmutabilidad:** Utilizar métodos básicos (`.strip()`, `.upper()`, `.lower()`, `.title()`, `.replace()`) y comprobar que las cadenas no sufren cambios sin una reasignación explícita[cite: 6].
7. **Uso de Librerías Estándar (`random` y `math`):** Importar módulos mediante `import` o `from ... import` para la generación de aleatorios y resolución de cálculos matemáticos avanzados[cite: 7, 8].
8. **Salidas Formateadas y Distribución de Espacios (`f-strings`):** Formatear valores numéricos (control de decimales `:.2f` y separador de miles `:,`) y maquetar tablas o tickets mediante alineaciones (`<`, `>`, `^`) y anchos fijos de campo[cite: 9, 10].

---

## 📁 Estructura del Repositorio

| Archivo | Descripción / Conceptos Clave |
| :--- | :--- |
| `U2E1 - Salida en Python.py` | Uso de `print()`, comillas simples/dobles, comillas anidadas, comillas escapadas (`\"`), saltos de línea (`\n`) y tabulaciones (`\t`)[cite: 1]. |
| `U2E2 - Manejo de Variables.py` | Declaración de variables, concatenación vs. suma con `+`, cálculo de promedios, uso de booleanos e inspección de tipos con `type()`[cite: 2]. |
| `U2E3 - Lectura desde teclado y almacenamiento en variables.py` | Captura de datos con `input()`, conversión de datos (*casting*) a `int` y `float`, y despliegue estructurado[cite: 3]. |
| `U2E4 - Operadores Aritméticos y Jerarquía.py` | Operadores básicos (`+`, `-`, `*`, `/`, `//`, `%`, `**`), multiplicación de cadenas para separadores (`"-" * 50`) y demostración paso a paso del orden de evaluación[cite: 4]. |
| `U2E5 - Operadores de Asignación Compuesta.py` | Modificación acumulativa de variables (`+=`, `-=`, `*=`, `/=`, `//=`, `%=`) aplicada a la economía de un videojuego[cite: 5]. |
| `U2E6 - Métodos sobre Cadenas STR.py` | Limpieza de texto con `.strip()`, transformaciones de caso (`.upper()`, `.lower()`, `.title()`), reemplazo con `.replace()` y demostración de la inmutabilidad de `str`[cite: 6]. |
| `U2E7 - Uso de Random.py` | Generación de flotantes (`random()`), enteros en rango cerrado (`randint()`) y selección aleatoria sobre listas (`choice()`). Comparación entre `import random` y `from random import ...`[cite: 7]. |
| `U2E8 - Funciones del paquete math.py` | Constantes (`pi`, `e`, `inf`), redondeo/truncamiento (`ceil`, `floor`, `trunc`), potencias, raíces, valor absoluto, trigonometría en radianes, logaritmos, factorial y MCD (`gcd`)[cite: 8]. |
| `U2E9 - Salidas con Formato.py` | Comparación entre `print` tradicional con comas y `f-strings`. Formateo monetario con dos decimales (`:.2f`), remoción de decimales (`:.0f`) y separador de miles (`:,.2f`)[cite: 9]. |
| `U2E10 - Distribución en Salida.py` | Maquetación en consola mediante `f-strings` especificando anchos de campo y alineaciones: izquierda (`<`), derecha (`>`) y centrado (`^`)[cite: 10]. |

---

## 💻 Descripción de los Módulos

### 1. Salida Básica en Python (`U2E1 - Salida en Python.py`)
Muestra la flexibilidad de la función `print()` para desplegar información en consola[cite: 1]:
* **Comillas:** Permite usar comillas dobles `""` o simples `''`, o bien anidarlas/escaparlas (`\"`) para incluir citas dentro del texto[cite: 1].
* **Secuencias de escape:** Introducción a `\n` para saltos de línea y `\t` para tabular datos y crear columnas simples[cite: 1].

### 2. Manejo de Variables y Tipos (`U2E2 - Manejo de Variables.py`)
Explora la naturaleza dinámica de los tipos de datos en Python[cite: 2]:
* **Diferenciación del operador `+`:** Concatenación si se utiliza entre cadenas (`str`) o adición matemática si se aplica entre números (`int`, `float`)[cite: 2].
* **Inspección de tipos:** Uso de la función `type()` para verificar el tipo detectado por el intérprete[cite: 2].

### 3. Lectura desde Teclado (`U2E3 - Lectura desde teclado y almacenamiento en variables.py`)
Demuestra cómo recibir interacción del usuario a través de la consola[cite: 3]:
* **Captura y Casting:** Dado que `input()` siempre retorna un texto (`str`), se aplican las funciones `int()` y `float()` para transformar el dato a valor numérico antes de su procesamiento[cite: 3].

### 4. Operadores Aritméticos y Jerarquía (`U2E4 - Operadores Aritméticos y Jerarquía.py`)
Cubre la totalidad de los operadores matemáticos de Python y detalla las reglas de evaluación[cite: 4]:
* **Operadores especiales:** División real `/` (retorna siempre `float`), división entera `//` (descarta decimales) y módulo `%` (obtiene el residuo)[cite: 4].
* **Jerarquía:** Expresiones comparativas que muestran el impacto directo de los paréntesis en el resultado final[cite: 4].

### 5. Operadores de Asignación Compuesta (`U2E5 - Operadores de Asignación Compuesta.py`)
Atajos sintácticos para modificar el valor almacenado en una variable previamente definida[cite: 5]:
* **Operaciones directas:** Ejemplos prácticos de `+=`, `-=`, `*=`, `/=`, `//=`, `%=` aplicados al control de un inventario de puntos y monedas en un juego[cite: 5].

### 6. Métodos sobre Cadenas y Su Inmutabilidad (`U2E6 - Métodos sobre Cadenas STR.py`)
Procesamiento básico de cadenas de caracteres[cite: 6]:
* **Limpieza y transformación:** Uso de `.strip()` para quitar espacios indeseados, `.title()`, `.upper()`, `.lower()` para ajuste de casos y `.replace()` para la sustitución de fragmentos[cite: 6].
* **Demostración de Inmutabilidad:** Muestra cómo las llamadas a métodos sobre cadenas no alteran la variable original a menos que el resultado sea reasignado[cite: 6].

### 7. Uso del Paquete `random` (`U2E7 - Uso de Random.py`)
Muestra la generación de valores aleatorios mediante la librería estándar[cite: 7]:
* **Funciones principales:** Generación de decimales en $[0.0, 1.0)$ con `random()`, enteros en rango cerrado $[a, b]$ con `randint()`, y selección sobre secuencias con `choice()`[cite: 7].
* **Sintaxis de importación:** Análisis del uso de `import random` versus `from random import random`[cite: 7].

### 8. Funciones del Paquete `math` (`U2E8 - Funciones del paquete math.py`)
Uso del módulo matemático para operaciones avanzadas[cite: 8]:
* **Herramientas de cálculo:** Uso de constantes (`pi`, `e`), funciones de redondeo (`ceil`, `floor`, `trunc`), potencias/raíces (`pow`, `sqrt`), conversión de grados a radianes (`radians`) y funciones trigonométricas[cite: 8].

### 9. Salidas con Formato (`U2E9 - Salidas con Formato.py`)
Evolución de la salida estándar a la presentación formateada mediante `f-strings`[cite: 9]:
* **Sintaxis con llaves:** Inserción directa de variables y cálculos dentro de `{}`[cite: 9].
* **Formatos numéricos:** Control estricto de decimales (`:.2f`) y formateo de montos financieros con comas en miles (`:,.2f`)[cite: 9].

### 10. Distribución en Salida (`U2E10 - Distribución en Salida.py`)
Técnicas de alineación y maquetación de texto en consola usando `f-strings`[cite: 10]:
* **Alineación de columnas:** Definición de anchos fijos de campo con alineación a la izquierda (`:<15`), derecha (`:>10`) y centrado (`:^12`) para la creación de reportes estructurados[cite: 10].

---

## 🚀 Requisitos e Instalación

Para ejecutar cualquiera de estos scripts solo necesitas tener instalado **Python 3.6+**:

```bash
# Clonar el repositorio
git clone [https://github.com/tu-usuario/fundamentos-programacion-python.git](https://github.com/tu-usuario/fundamentos-programacion-python.git)

# Entrar al directorio del proyecto
cd fundamentos-programacion-python

# Ejecutar cualquiera de los ejemplos
python "U2E1 - Salida en Python.py"
