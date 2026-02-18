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
```


## práctica: Generación de Patrón Circular en Blender con Python

##  Descripción
En esta práctica se desarrolla un script en Python dentro de Blender para generar automáticamente un patrón circular compuesto por múltiples círculos alrededor de un círculo central.

Se usa una estructura de control `while` para evitar la repetición manual de código y mejorar la eficiencia del programa.

---

##  Objetivos

- Automatizar la creación de figuras en Blender mediante scripting.
- Aplicar conceptos matemáticos como seno y coseno.
- Utilizar ciclos para generar patrones geométricos.

---

## Requisitos

- Blender 3.x o superior  
- Python básico  
- Editor de scripting de Blender  

---

## Cómo ejecutar el script

1. Abrir Blender.
2. Ir a la pestaña **Scripting**.
3. Crear un nuevo script.
4. Copiar el código del archivo `script.py`.
5. Ejecutar con **Run Script**.

El patrón aparecerá automáticamente en la escena.

---

##  Explicación del Código
<img width="625" height="96" alt="image" src="https://github.com/user-attachments/assets/1f35aab3-1eec-4ac7-9112-80dc0cdc3482" />
radio: tamaño de cada círculo.
angulo_actual: controla la posición angular.
paso_angular: determina cada cuántos grados se crea un nuevo círculo

<img width="701" height="102" alt="image" src="https://github.com/user-attachments/assets/b9da5c68-81b0-43cc-af7c-3f9902d56850" />

El ciclo se ejecuta hasta completar los 360°, formando un círculo completo.
Evita escribir el mismo bloque de código múltiples veces.

<img width="485" height="150" alt="image" src="https://github.com/user-attachments/assets/8536b212-afd0-43bb-93d2-082e70306be5" />

Creacion automatica de los circulos


###  Limpieza de la escena
```python
bpy.ops.object.select_all(action='SELECT')
bpy.ops.object.delete()
