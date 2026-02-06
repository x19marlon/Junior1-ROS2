# ¿Cómo usar esta guia?

## Notas
Antes de comenzar con estos ejercicios asegurate de lo siguiente:
* Estar en tu workspace de ROS2
* Build 
    
        colcon build

* Source el workspace 
        
        source install/setup.bash

EL repositorio esta pensado para que a medida que avances los ejercicios sean más retadores esto con el fin de que aprendas a los golpes como me lo enseñó mi papá. 

## Estrucutras del repositorio 

El repositorio tiene ejercicios en 3 dificultades **1, 2, 3**.

// Aqui va un tree :v 

Explicacion de los niveles de dificulta:

## nivel 1 

Estos ejercios son codigos básicos de python donde aprenderás como ejecutar nodos en conjunto y refinaras tus conocimientos de publicador - suscriptor para que ya puedas crear los tuyos propios.

## nivel 2 

El nivel 2 ya te pide que tu mismo crees el codigo, te encargas de crear nodos, que a partir de un publicador y suscriptor cumpliran tareas y automatizaras cálculos básicos.
## nivel 3 

Esta es la prueba final para saber si ya eres un artesano de los topicos, la idea es que le pases por parametros ( teclado ) los datos a tu publicador para que el suscriptor puedan hacer los cálculos necesarios para que se cumplan las tareas que se te piden.

## nivel extra

Crea un publicador que le mande a un suscriptor los datos necesarios para que puedas mover un servo 45, 90 y 0 grados.
