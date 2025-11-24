# 📘 Ecuación de Euler–Lagrange aplicada a un manipulador robótico 🤖

Este proyecto fue creado como parte de un estudio práctico sobre la **ecuación de Euler–Lagrange** y su aplicación directa en el análisis y modelado dinámico de un **manipulador robótico planar de 2 grados de libertad (2R)**.  
El objetivo es combinar la teoría clásica con una implementación moderna en Python, mostrando paso a paso cómo se construye el modelo dinámico de un robot desde sus fundamentos físicos.

---

## Objetivo

Comprender el origen, la deducción y la aplicación práctica de la **ecuación de Euler–Lagrange** para describir el movimiento de sistemas físicos y, finalmente, aplicarla a un robot manipulador.  
El notebook busca que el lector pueda:
- Entender la relación entre la energía cinética, potencial y las ecuaciones de movimiento.  
- Ver cómo se deriva el modelo dinámico completo de un robot.  
- Visualizar su movimiento real en un espacio tridimensional (x, y, z).  

---

## Qué incluye este repositorio

- `Euler_Lagrange_Manipulador_Robotico.ipynb`  
  Un notebook de Google Colab donde podrás encontrar:
  - Explicaciones teóricas y fórmulas matemáticas presentadas de forma clara.  
  - Derivaciones simbólicas de distintos sistemas (masa–resorte, péndulo, sistema de dos masas).  
  - Desarrollo completo del modelo dinámico de un **robot 2R** utilizando la ecuación de Euler–Lagrange.  
  - Un **ejemplo numérico con animación 3D**, donde se observa el movimiento del robot en tiempo real.

---

## ⚙️ Cómo usarlo

1. Descarga el archivo `.ipynb`.  
2. Sube el notebook a tu **Google Drive**.  
3. Ábrelo con **Google Colab** (clic derecho → *Abrir con → Colab*).  
4. Ejecuta las celdas una por una.  
5. Al final, verás una animación del manipulador moviéndose en el plano **(x, y, z)**.  

> 💡 *Tip:* Si quieres modificar el comportamiento del robot, puedes cambiar los valores de masa, longitud o amplitud del movimiento dentro del código.

---

## 🧠 Tecnologías utilizadas

- **Python 3**  
- **SymPy** → para cálculos simbólicos (ecuaciones de Euler–Lagrange).  
- **NumPy** → para operaciones numéricas.  
- **Matplotlib (3D)** → para graficar y animar el robot en un sistema espacial.  

Para ejecutarlo localmente:
```bash
pip install sympy numpy matplotlib
