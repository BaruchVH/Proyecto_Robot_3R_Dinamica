# Proyecto final: Modelo dinámico de un robot 3R

Este repositorio contiene el desarrollo del proyecto final de la asignatura de Robótica, cuyo objetivo fue obtener los datos físicos de un robot manipulador 3R a partir de un modelo CAD y generar su modelo dinámico.

## Contenido

- `Proyecto_Robot_3R_Dinamica.ipynb`: notebook principal del proyecto.
- `imagenes/`: capturas del modelo CAD y componentes del robot.
- `.gitignore`: archivo para evitar subir archivos temporales.

## Descripción

El proyecto incluye:

- Obtención de masas, centros de masa e inercias desde CAD.
- Conversión de unidades al Sistema Internacional.
- Modelo cinemático directo.
- Jacobiano.
- Modelo dinámico mediante Euler-Lagrange.
- Evaluación de torques articulares en una trayectoria de prueba.

## Resultado principal

La articulación con mayor demanda de torque fue `tau_2`, con un torque máximo absoluto de aproximadamente `1.960078 N·m`.

## Autores

- Baruch Villarreal Hinojosa
- Luis Ángel Pérez Castro

## Asignatura

Robótica — Facultad de Ingeniería, UNAM  
Semestre 2026-2
