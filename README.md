# M15 - ¿Cuándo y dónde tenemos que pescar centollas en el Canal Beagle?

**Mentora:** Lucía Bergagna

**Email:** lucia.bergagna@mi.unc.edu.ar

## Descripción y objetivo del proyecto

Se trabajará con datos reales sobre las abundancias de **centollas y centollones**, dos especies de cangrejos presentes en el Canal Beagle. Se pretende explorar la variabilidad espacial y temporal de las poblaciones de ambas especies.

Dado que la sobrepesca de ambos recursos está causando un decaimiento de sus abundancias, el objetivo del proyecto es ofrecer una recomendación a la autoridad de aplicación de estos recursos pesqueros para contribuir a asegurar la persistencia de ambas especies.

Los datos provienen de la pesca de ejemplares en el Canal Beagle durante seis temporadas:

- Enero de 1996
- Abril de 1996
- Julio de 1996
- Octubre de 1996
- Octubre de 1997
- Octubre de 1998

Adicionalmente, se dispone de datos correspondientes a la temporada:

- Julio de 1997 

Cada fila del conjunto de datos representa un individuo, que se describe mediante diez variables relacionadas con sus características biológicas y morfológicas:

- Especie
- Sexo
- Estado del caparazón
- Largo y ancho del caparazón
- Largo y ancho de la pinza derecha
- Presencia de cirripedios
- Presencia de huevos
- Presencia de parásitos

Además, se registró la **profundidad del punto de muestreo** y su ubicación mediante **latitud y longitud**, junto con un punto de referencia en el mapa.

La columna `tipo` permite calcular las abundancias de las especies en cada punto de muestreo. El valor de esta columna se repite tantas veces como animales fueron pescados en ese punto, considerando una determinada cantidad de trampas.

## Preguntas que orientan el proyecto

A lo largo del proyecto se buscará responder, entre otras, las siguientes preguntas:

- ¿Cuáles son las diferencias de tamaño y abundancia entre machos y hembras? ¿Y entre las distintas especies?
- ¿Hay una población más abundante que otra en el Canal Beagle?
- ¿Cuándo tienen huevos las hembras de cada especie?
- ¿Quiénes tienen más parásitos y quiénes presentan más epibiontes?
- ¿Hay preferencia de alguna especie por determinada profundidad?
- ¿Dónde y cuándo se recomienda no pescar? ¿Por qué?

## Datos

Los datos utilizados en el proyecto original se encuentran disponibles en:

https://github.com/luciabergagna-jpg/centoll

## Organización del repositorio

El repositorio se organiza principalmente por integrante. Cada integrante trabajará sobre sus propios archivos y subirá sus notebooks y materiales al repositorio.

La estructura general será:

    /
    ├── README.md
    │
    ├── datos/
    │   ├── centollas_mentoria.csv
    │   └── jul97.csv
    │
    ├── fernando/
    │   ├── fernando_tp1.ipynb
    │   ├── fernando_tp2.ipynb
    │   ├── fernando_tp3.ipynb
    │   └── ...
    │
    ├── francisco/
    │   └── ...
    │
    ├── mariano/
    │   └── ...
    │
    ├── rodrigo/
    │   └── ...
    │
    └── trabajo_comun/
        ├── entregas/
        │   ├── tp1_final.ipynb
        │   └── ...
        └── correcciones/
        │   ├── tp1_final_correcciones.ipynb
        │   └── ...

### Carpeta `datos`

Se almacenan los datos de la campaña de julio del 97' además de los datosoriginales del proyecto `centollas_mentoria.csv`, también disponibles en el github oficial de la mentoría. 

### Carpetas de cada integrante

Cada integrante tendrá una carpeta propia para almacenar sus trabajos.

Los notebooks se identificarán indicando el nombre y el trabajo correspondiente. Por ejemplo:

    integrante_1_tp1.ipynb
    integrante_1_tp2.ipynb
    integrante_1_tp3.ipynb

Además de los archivos `.ipynb`, podrán incorporarse otros formatos necesarios para el proyecto, como `.pdf` para infografías, presentaciones u otros materiales.

### Carpeta `trabajo_comun`

La carpeta `trabajo_comun` contendrá los archivos que sean producto de la integración de los trabajos individuales, incluyendo el notebook común/final del proyecto.

La idea es que cada integrante trabaje principalmente sobre sus propios archivos y que los aportes sean posteriormente integrados en los archivos comunes.

Se incluye un subdirectorio para guardar las `entregas` y otro para mantener un registro de las `correcciones` hechas por la mentora.

## Forma de trabajo

El flujo de trabajo será sencillo:

1. Cada integrante trabaja principalmente en los archivos de su propia carpeta.
2. Los notebooks pueden desarrollarse utilizando **Google Colab** y **Google Drive**.
3. Una vez realizado un aporte, se sube la versión correspondiente al repositorio de GitHub.
4. GitHub conserva el historial de versiones de los archivos, por lo que no es necesario crear múltiples copias como `final_v2`, `final_v3`, etc.
5. Los aportes individuales se utilizarán posteriormente para construir y actualizar los archivos comunes.
6. Se procurará evitar que varias personas modifiquen simultáneamente el mismo archivo común para reducir conflictos y pérdida de cambios.

### Versionado

GitHub permite conservar el historial de modificaciones de los archivos. Por este motivo, se recomienda mantener un mismo archivo y actualizarlo en lugar de crear diferentes versiones manuales.

Por ejemplo, se utilizará:

    integrante_1_tp1.ipynb

y no:

    integrante_1_tp1_v2.ipynb
    integrante_1_tp1_final.ipynb
    integrante_1_tp1_final2.ipynb

Cada actualización quedará registrada en el historial del repositorio.

## Prácticos y fechas de entrega

- **31/07** — Práctico 1: análisis y visualización
- **07/09** — Práctico 2: análisis exploratorio y curación de datos
- **25/09** — Práctico 3: aprendizaje supervisado o no supervisado
- **26/10** — Video de presentación final de mentoría
- **04/12 y 05/12** — Jornadas: presentación de mentorías

## Integrantes

- Fernando Luna
- Francisco Capobianco
- Mariano Baggini
- Rodrigo Navarro
