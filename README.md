# 🤖 ¿Cómo usar esta guía?

Esta guía está diseñada para ayudarte a aprender **ROS2 (Robot Operating System)** mediante ejercicios progresivos.  
A medida que avances, los ejercicios se volverán más complicados para reforzar tu comprensión de **nodos, publicadores y suscriptores**.

---

# 📝 Notas importantes

Antes de comenzar con los ejercicios asegúrate de lo siguiente:

### 1️⃣ Estar dentro de tu workspace de ROS2

```bash
cd ~/ros2_ws
```

### 2️⃣ Construir el workspace

```bash
colcon build
```
###  3️⃣ Activar (source) el workspace

```bash
source install/setup.bash
```

### 📂 Estructura del repositorio

El repositorio contiene ejercicios organizados por **niveles de dificultad:**

```bash
Junior1-ROS2
│
├── nivel_1/
│   ├── ejercicio_1
│   ├── ejercicio_2
│   ├── ejercicio_3
│
│
├── nivel_2/
│   ├── ejercicio_1
│   ├── ejercicio_2
│   ├── ejercicio_3
│
├── nivel_3/
│   ├── ejercicio_1
│   ├── ejercicio_2
│   ├── ejercicio_3
│
└── nivel_extra/
```
Cada nivel introduce nuevos conceptos y mayor complejidad.

### 🎯 Explicación de los niveles
#### 🟢 Nivel 1 — Fundamentos

Estos ejercicios contienen **código base en Python.**

Aquí aprenderás:

* Cómo ejecutar nodos en ROS2

* Cómo funcionan los publicadores (publishers)

* Cómo funcionan los suscriptores (subscribers)

* Cómo conectar nodos entre sí mediante tópicos

El objetivo es que entiendas la lógica básica para luego poder crear tus propios nodos.

#### 🟡 Nivel 2 — Creación de nodos

En este nivel ya deberás escribir tu propio código.

Vas a crear nodos que:

* Publiquen información

* Reciban mensajes mediante suscriptores

* Procesen datos

* Automaticen cálculos básicos

Aquí empezarás a construir sistemas más completos dentro de ROS2.

#### 🔴 Nivel 3 — Integración de tópicos

Este es el desafío final.

La idea es que:

* Recibas datos desde teclado

* Los envíes mediante un publicador

* Un suscriptor procese esa información

* Se ejecuten las tareas solicitadas

Si completas este nivel, ya tendrás una buena base para trabajar con tópicos en ROS2.

⭐ Nivel Extra

Crea un sistema donde:

* Un publicador envíe comandos

* Un suscriptor reciba los datos

* Se controle un servo motor

El servo debe poder moverse a:

* 0°

* 45°

* 90°

💡 Este ejercicio conecta ROS2 con hardware real, un paso importante en robótica.

## 🚀 Objetivo de esta guía

Que aprendas ROS2 **haciendo**, experimentando y resolviendo problemas reales.

En robótica, la mejor forma de aprender es:

**probar, equivocarse, arreglar y volver a intentar.**
