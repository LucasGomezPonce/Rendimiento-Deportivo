# 📊 Análisis de Rendimiento Deportivo

Este proyecto es una herramienta interactiva desarrollada en Python que permite **analizar y visualizar datos de rendimiento deportivo** en disciplinas como atletismo, aplicando filtros y cálculos estadísticos sobre los participantes.

## 🚀 Funcionalidades

El programa ofrece las siguientes funcionalidades a través de un menú interactivo:

1. **Mostrar todos los participantes**  
2. **Filtrar por deporte**  
3. **Filtrar por distancia**  
4. **Filtrar por marcas mejores que un valor límite**  
5. **Filtrar por rango de edad**  
6. **Calcular el promedio de marcas**  
7. **Mostrar la mejor marca registrada**  
8. **Mostrar la peor marca registrada**  
9. **Mejor marca por categoría de edad**  
10. **Salir del programa**

## 🧱 Estructura del Proyecto

El proyecto está dividido en varios módulos para mantener una buena organización del código:

- `main.py` – Contiene el menú principal y la lógica de interacción con el usuario.  
- `calculos.py` – Funciones para calcular promedios, mejores y peores marcas.  
- `filtros.py` – Funciones para filtrar participantes por deporte, distancia, edad, etc.  
- `utils.py` – Funciones utilitarias para interactuar con el usuario (como elegir deporte/distancia).  
- `participantes.py` – Base de datos simulada con los participantes y sus marcas.

## 🏃‍♂️ Estructura de los Participantes

Los participantes están representados como diccionarios con información como:

```python
{
    "nombre": "Juan Pérez",
    "edad": 25,
    "deporte": "Atletismo",
    "distancia": 100,
    "marca": 10.75,  # en segundos
    "categoría": "Adulto"
}

