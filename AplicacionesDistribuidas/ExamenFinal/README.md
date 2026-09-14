# Examen final del PFC — Aplicaciones Distribuidas (Séptimo semestre)

Resultados del examen final del Proyecto Fin de Curso, ISR-701, PPA 2026-2027.

- **Página publicada:** https://gleiston-guerrero.github.io/informes/AplicacionesDistribuidas/ExamenFinal/
- **Alcance de la evaluación:** último commit de cada repositorio, **sin límite de fecha**. Revisado el 14 de septiembre de 2026.
- **Peso:** la entrega del proyecto vale el **100 %** de la nota. No interviene ninguna otra calificación.
- **Docente:** Dr. Gleiston Cicerón Guerrero Ulloa, Ph.D.

## Contenido

| Archivo | Qué es |
|---|---|
| `index.html` | Índice con el resumen de los cuatro equipos, las notas individuales y los enlaces |
| `FUVV.html` | Hoja de cálculo, aporte e informes individuales del equipo FUVV — SCLI |
| `ACC.html` | ídem — TicketFold |
| `AGLS.html` | ídem — TiendaTech |
| `BCEL.html` | ídem — AcadTrace |

La rúbrica está incorporada en la hoja de cálculo de cada página: cada fila lleva su peso, su calificación
y lo que encontré al comprobarla, de modo que no hace falta un documento aparte.

## Cómo se calcula la nota

De todo lo exigido al proyecto, una parte estaba resuelta y verificada con anterioridad y no vuelve a
puntuar. Lo demás se califica, y cada elemento cuenta dos veces: tiene un **peso** —los pesos suman 10—
sobre el que recibe una calificación, y esa calificación dividida entre su máximo da un **factor** que
multiplica.

    Nota = (f1 × f2 × … × fn) × (p1 + p2 + … + pn)

El factor vale 1 solamente cuando el elemento está terminado y correcto al cien por cien. Un elemento en
cero deja el multiplicador en cero y con él la nota. Por eso, junto a cada nota se publica también la suma
de puntos: es la medida de cuánto trabajo hay hecho.

La nota del equipo se reparte después a cada integrante según su aporte al repositorio, medido sobre el
historial completo, y ningún integrante puede superar la nota del equipo.

## Criterios de piso

Vigentes, expuestos y **no aplicados** en esta evaluación: aquí la nota sale únicamente de la rúbrica.
En una evaluación ordinaria, el incumplimiento de cualquiera de ellos deja la calificación en cero.

1. Subir al SGA un PDF con carátula de identificación que muestre, en una sola línea y de forma legible, la dirección del repositorio donde está el trabajo.
2. Que el PDF se regenere clonando el repositorio y compilando el archivo principal, con las instrucciones de compilación escritas en el README.
3. Que todo el trabajo esté integrado en la rama principal en el commit de la entrega.
4. Que cada integrante sepa explicar el código y las mediciones que se le atribuyen.

## Cómo se auditó

Se clonaron los cuatro repositorios y se evaluó el último commit de cada uno, sin fecha límite. Se
ejecutaron las suites de pruebas, se midió la cobertura sin los filtros de cada proyecto, se recalcularon
desde los datos crudos las cifras publicadas en cada documento, se ejecutaron las verificaciones de sumas
contando cuántas pasan y cuántas fallan, y se comprobó en cada caso que las pruebas pudieran fallar
rompiendo una aserción o el dato. El aporte individual se midió con `git log --no-merges --numstat` sobre
el historial completo, atribuyendo por el correo del autor del commit.

Respecto de la evaluación anterior, de los 42 elementos calificados **32 subieron, 9 quedaron igual y 1
bajó**. La columna *Antes* de cada hoja de cálculo muestra ese movimiento.
