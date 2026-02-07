# Práctica: Creación de un Polígono 2D en Blender con Python

# Descripción
En esta práctica se desarrolla un script en Python para Blender que permite generar automáticamente un polígono 2D a partir de parámetros definidos por el usuario, como el número de lados y el radio.
El objetivo es entender cómo funciona la creación de geometría mediante scripting y cómo aplicar conceptos matemáticos como la trigonometría para posicionar vértices en un plano.

## Objetivos

- Aplicar funciones trigonométricas para calcular coordenadas.
- Entender la estructura básica de una malla (vertices y aristas).
- Utilizar Python como herramienta de modelado procedural.

## Requisitos

- Blender 3.0 o superior  
- Editor de scripting de Blender  

## Cómo ejecutar el script
1. Abrir Blender.
2. Ir a la pestaña **Scripting**.
3. Crear un nuevo archivo.
4. Copiar el contenido de `script.py`.
5. Presionar **Run Script**.

El polígono aparecerá automáticamente en la escena.

```python
import bpy
import math
