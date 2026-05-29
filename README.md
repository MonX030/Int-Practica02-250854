# Int-Practica02-250854
---

En esta practica aprenderemos a utilizar las herramientas Git Github para el control de versiones de proyectos de desrrollo de Software, aplicandoi principios de buenas practicas en Documentacion ,Desarrollo Colaborativo y Respaldo en la Nube del Proyecto Integrador.

Elaborado por ""Ruben Morales Reyes""

Materia "Proyecto Integrador"

Docente "M.T.I Marco Antonio Ramirez Hernandez"

Periodos"Mayo - Agosto2026"

## Comandos Basicos pra Maquetado de la Documnetacion utilizando el estandar de Markdown (.md)
---
Markdown es el estandar utilizando por Github, para estilizar (maquetar) la documentacion de proyectos , lo que permite a usuarios y colaboradores del proyecto entender el contexto y operacion del mismo.

## 1. Encabezados o Titulos (HEADERS)
**EJEMPLOS**
# Encabezado de nivel 1
## Encabezado de nivel 2
### Encabezado de nivel 3
#### Encabezado de nivel 4
##### Encabezado de nivel 5
###### Encabezado de nivel 6
####### Encabezado de nivel 7 - *El estandar solo permite 6 niveles para títulos,a partir del séptimo será presentado como texto plano (sin estilo)*

## 2. Separadores (SEPARATORS)

Si se desea marcar una separacion visual de los contenidos podemos utilizar una línea horizontal indicando tres caracteres - continuos,en el maquetado

**EJEMPLO**

### Título de la sección 

---

Texto despuén del separador 
### 3. Párrafos (PARAGRAPHS)

Son Utilizados para presentar grandes secciones de texto que decriben detalladamente el contenido de las secciones de la documentacion,detallan procesos, explican código teórico.

**EJEMPLO:**

Párrafo 1: Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 vEste texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 

Párrafo 2: este texto es del párrafo 2 este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2veste texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2veste texto es del párrafo 2este texto es del párrafo 2,el estandar de markdown distingue los párrafos con un doble de línea de texto, si no se párrafos con un doble salto de texto,si no desea alinear ,es decir estará alineado a la izquierda por defecto

En caso de que necesitemos alinear el párrafo a **izquierda**, **derecha**,**centrado** o **justificado**, deberemos utilizar una etiqueta '''<p>''' con la propiedad aling y la direccion deseada. 

<p align="left">Párrafo alineado a la izquierda   párrafo alineado a la izquierda párrafo alineado a la izquierdapárrafo alineado a la izquierda párrafo alineado a la izquierda párrafo alineado a la izquierda párrafo alineado a la izquierda párrafo alineado a la izquierda párrafo alineado a la izquierda  párrafo alineado a la izquierda  párrafo alineado a la izquierda  párrafo alineado a la izquierda  párrafo alineado a la izquierda  párrafo alineado a la izquierda  párrafo alineado a la izquierda  párrafo alineado a la izquierda  párrafo alineado a la izquierda  párrafo alineado a la izquierda  párrafo alineado a la izquierda  párrafo alineado a la izquierda 

<p alig="right"> Párrafo alineado a la derecha párrafo alineado a la derecho párrafo alineado a la derechopárrafo alineado a la derechopárrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho

<p align="justify"> Párrafo justificado  párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado


### 4. Enfatizado de Texto

- Texto en Negritas; Para resaltar texto importante que no sea un titulo por que esto inicialmente están en negrita deberemos encerrar el texto 
deseado entre dobles asteriscos(**).

Ejemplo; Este *texto* estará en **negrita**.

Texto en cursiva o  (italico) Para hacer referencia a texto utilizando el formato inclinado o italico bastará con encerrar el texto deseado enre dos asteriscos simples(*)

Ejemplo;Este texto estara *Inclinado*.

Texto en Cursiva y Negrita Para lograr esta estilizacion en la documentacion basta con juntar ambas configuracines , es decir encerramos el texto en un triple asterisco (***)

Ejemplo; ***Este texto esta en Negrita e Itálico***

-Texto Tachado : En algunas ocaciones es necesario dar formato al texto con un efecto de como es incorrecto, generalmente esta idea se trasmite por que el texto esta tachado, , es decir con una línea que mar5aca por la mitad Para lograr este efecto que tenemos quee encerrar el texto entre una doble tilde de (~).

Ejemplo; se dice haya no ~haiga~.

Texto Subrayado;Este tipo de texto de formato el texto queda sobre una l9inea inferiosr para denotar su relevancia ,este formato no tiene una vewrsion rapida en el estándar MARKDOWN, pero dado su similiaridad a HTML podemos utilizar las etiquetass ''' <u>''' y '''</u>'''.

Ejemplo: El <u>texto</u> debe estar <u>subrayado</u>.

-Texto en Superindice: En algunas ocaciones se requiere dar formato a formulas estadisticas que requiere potencias entre otras applicaciones,podemos utilizar el tag de HTML    '''<sub>´´´´ y </sub> para delimitar el formato.

Ejenmplo: Para elevar x al cuadrado tendriamos lo siguente  x<sup> 2 </sup>

- Texto en Subindice : En el caso de Quimica se utilizan subindices para represenatr formulas,para ello podemos utilizar el formato de texto con la etiqueta HTML '''<sub> y </sub>'''.

Ejemplo: La formula del Agua es H<sub >2</sub> 0.

### 5. Listas 

Cuando realizamos documentacion utilizando el estandar de MARKDOWN ,es comun que tengamos que listar elementos, requisitos de Hardware ,requisitos de software o enumerar pasos de como el software debe de ser instalado paso a paso,por eso debemos saber como crear listas de las cuales hay de 3 tipos : **Ordenadas(Números)**,**Desordenadas(Viñetas)** y **Mixtas(Viñetas y Numeros)**.

1. Listas Ordenadas Estas listas deberan estar numeradas con un numero seguido por un punto y un espacio en blanco para comenzar con el listado.

1. PC
2. WIFI
3. MODEM
4. SMARTPHONE
6. SMART TV
5. TABLET

2.Estas listas no llevan un numero ,sino una viñeta (simbolo),y suele lsitar elementos que no requieren un orden especifico.

- Pan
- Leche
- Huevo
- Azucar 

3. Listas Mixta

Son Aquellos que mezcla ambos elementos

- 3° A DSM 
 1. Juan

 2. Pedro

 3. Alejandra

- 3° B DSM
1. Romina
2. Daniel
-3° C DSM
1. Yahir
2. Liseth
3. Jeovany
4. Erick

### 6. Bloques de Codigo (CODE BLOCKS ) o Citas (BLOCK QUOTES) 

Estos estilos se utilizan para llamar la atencion del lector ,en pasos que son importantes ,realizar alguan reseña o segmentar lineas de codigo que se deberán ingresar en una terminal de comandos o líneas de ejecuccion.

-Cuadro de Citas(Block Quotes)
Son cajas estilizadas en colores grises por defecto con un márgen más claro.

Ejemplo 

Para listar las carpetas y archivos desde una terminal de comandos en el sistema operativo de windows debemos utilixar el comando 

>C:/dir

Después oprimimos la tecla *Enter*.

Tambien podemos utilizar texto multilinea 

EJEMPLO: 

pasos para instalar MySQL

> - Descargar el archivo instalador desde la pagina poagaina oficial ww.mysql.com
> - Instalar el servidor de Bases de datos 
> - Definir el puerto y contraseña para el usuario **root**
> - Inicializamos el servidor de basess de datos
> - Conectarnos a la base de datos para veridfrciar que se instalo correctamente.

-Bloques de codigo


