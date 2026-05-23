# 🧩 POO en Python – Abstracción con ABC

Este repositorio contiene ejercicios prácticos sobre **abstracción** en la Programación Orientada a Objetos (POO) usando Python. Cada ejercicio muestra cómo definir clases abstractas con `ABC` y `abstractmethod`, y cómo implementarlas en subclases concretas.

"""

## 📦 Contenido

### Ejercicio 1 – Electrodoméstico y Licuadora
Se define una clase abstracta `Electrodomestico` con el método abstracto `encender()`. La subclase `Licuadora` lo implementa mostrando la marca y las velocidades disponibles.

### Ejercicio 2 – CuentaBancaria, Ahorros y Corriente
Se define una clase abstracta `CuentaBancaria` con los métodos abstractos `cobrar_comision()` y `mostrar_info()`. Las subclases `CuentaAhorros` (genera rendimiento del 2%) y `CuentaCorriente` (cobra comisión fija de $8.000) los implementan de forma diferente.

### Ejercicio 3 – Categoría, ProductoFísico y ProductoDigital
Se combina una clase normal `Categoria` con una clase abstracta `Producto` que tiene los métodos `calcular_precio_final()` y `mostrar_ficha()`. Las subclases `ProductoFisico` (suma $5.000 de envío) y `ProductoDigital` (sin envío) los implementan según su tipo.

"""

## 🛠️ Requisitos

- Python 3.x  
- No requiere librerías externas

## ▶️ Cómo ejecutar

```bash
python ejercicio1.py
python ejercicio2.py
python ejercicio3.py
```

## 📚 Conceptos aplicados

- Clases abstractas con `ABC`
- Métodos abstractos con `@abstractmethod`
- Herencia y uso de `super()`
- Composición de objetos (Ejercicio 3)
