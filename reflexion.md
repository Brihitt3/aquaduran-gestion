# 6. Reflexión Final

## 6.1. Aprendizajes sobre Git y GitHub
Este proyecto permitió aplicar de forma práctica los fundamentos del control de versiones estudiados en la unidad. Documentar un problema real el desabastecimiento de agua en Durán— usando únicamente archivos Markdown demostró que Git no es una herramienta exclusiva para código, sino un sistema robusto para gestionar cualquier tipo de trabajo colaborativo por versiones.

El uso de ramas propias (`requisitos`, `evidencias`) permitió mantener `main` siempre estable, integrando cada avance solo después de completarlo, en lugar de
trabajar directamente sobre la rama principal.

--- 

## 6.2. Sobre los commits progresivos
Uno de los aprendizajes más importantes fue la disciplina de realizar commits pequeños y descriptivos por cada avance real (definición del problema, solución,
requisitos, planificación, evidencias), en vez de una sola carga final. Esto hizo visible el proceso de construcción del proyecto y no solo el resultado.

---

## 6.3. Sobre la resolución de conflictos
Para este punto, se optó por explicar correctamente el procedimiento de resolución de conflictos en lugar de forzar uno artificialmente, tal como lo permiten las instrucciones de la actividad. Un conflicto de fusión ocurre cuando dos ramas modifican la misma línea de un archivo de forma distinta y Git no puede decidir automáticamente cuál versión conservar. El procedimiento correcto es:

1. Identificar el archivo en conflicto (`git status` o el aviso en el Pull Request de GitHub).

2. Abrir el archivo y ubicar los marcadores `<<<<<<< HEAD`, `=======` y `>>>>>>> nombre-rama`.

3. Analizar ambas versiones y decidir cómo combinarlas o cuál conservar.

4. Eliminar manualmente los marcadores, dejando solo el contenido final deseado.

5. Marcar el archivo como resuelto (`git add archivo`), confirmar con `git commit` y sincronizar con `git push`.

Comprender este flujo es tan importante como ejecutarlo, ya que en un entorno de trabajo real los conflictos son inevitables y saber resolverlos con criterio evita pérdida de información.

---
## 6.4. Dificultad encontrada
El principal reto fue coordinar el trabajo colaborativo sin perder la coherencia del proyecto: decidir qué actividades podía realizar el compañero sin que implicara "desarrollar" el proyecto principal, y estructurar las ramas para que el historial reflejara con claridad el aporte de cada persona.

---

## 6.5. Aprendizaje principal

Más allá del manejo técnico de comandos, el proyecto reforzó que Git y GitHub son ante todo herramientas de trazabilidad y comunicación: un buen historial de
commits y un flujo ordenado de ramas permite que cualquier persona entienda cómo evolucionó el proyecto, quién aportó qué, y por qué se tomaron ciertas decisiones algo fundamental en cualquier trabajo colaborativo real.

