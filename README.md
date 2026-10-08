<div align="center">
  <h1>DARLA NOTA</h1>
  <img width="400" height="400" alt="Darla" src="https://github.com/user-attachments/assets/b5e85b05-82c9-496c-a040-06fd4a09d793"/>
  <br>
  <i>"La inigualable Darla Nota"</i>
</div>

---

# 1. Visión general
## 1.1. Descripción
Tu nombre es **Darla Nota**, y eres profesora en un colegio. Tu misión es corregir los exámenes de tus alumnos y mantener el orden en el aula. A medida que vas corrigiendo a tus alumnos, y echando a los que suspenden, otros vendrán a tomar su puesto, subiendo así la dificultad, pues los nuevos alumnos pueden tener más nivel.

En el juego tendrás en el escritorio una pila de exámenes por corregir, uno por cada alumno en tu clase. Tendrás que hacer una revisión del examen comparando sus respuestas con la lista de soluciones y dando una nota final. Al mismo tiempo, los alumnos que no esten haciendo nada en clase, podrán causar caos en el aula (peleandose, jugando con la silla, etc); tendrás que balancear la corrección de exámenes junto con mantener el orden en clase. También podrás comprar mejoras a lo largo de la partida y superar eventos aleatorios.

Tu reputación de profesora depende de las notas de tus alumnos, pero se verá afectada negativamente si corriges mal o si hay demasiados problemas en el aula. Si tu reputación cae muy bajo, la partida termina.

El juego se controla en un ambiente 3D (el aula), donde tendrás que navegar entre los pupitres para interactuar con los alumnos. En tu escritorio principal tendrás que revisar las distintas hojas de soluciones (dependiendo del tipo de examen) y compararlas con las respuestas dadas por los alumnos en los exámenes.  

## 1.2. Pilares de diseño
- **Correción de exámenes:** La forma principal de ganar puntos, mediante un sencillo minijuego de mirar las respuestas.
- **Balancear el caos:** Controlar que los problemas en clase no lleguen a demasiado nivel mientras que intentas seguir corrigiendo exámenes.
- **Gestión del aula:** Comprar distintas mejoras para la clase y controlar a los alumnos que participan en esta, pudiendo expulsar a los que menos te convengan y manteniendo a los que sí si juegas correctamente.
- **Cumplimiento de objetivos:** Conseguir ciertos objetivos planteados en unos momentos específicos, como corregir X cantidad de exámenes, o tener a ciertos alumnos de un tipo, etc.

## 1.3. Setting
> Eres la nueva profesora en la escuela, y te han asignado el Aula 33. Empiezas corrigiendo los exámenes de tus niños y a medida que se corre la voz de la buena profe que eres, más y más alumnos comienzan a venir a tu clase, ¡todo el mundo quiere ir a la clase de Darla Nota! Mientras que tu número de alumnos crece, el superintendente pide más y más de ti *¿Podrás dar la nota y convertirte en la mejor profesora del universo?*

# 2. Gameplay
## 2.1. Core loop
El *core loop* del juego consiste en mantener tu reputación de profesora por encima de cierto nivel. Para ello, el caos en el aula no debe subir demasiado, a la vez que consigues corregir a tus alumnos sin cometer fallos y cumples los objetivos del superintendente.

Durante la partida, se repite este ciclo:
1. Los alumnos que no tengan un exámen en la pila por corregir realizan el examen. Al acabar se colocan en orden de llegada en tu pila.
2. Corriges el último exámen de la pila.
3. Mientras corriges, los alumnos que no tengan nada que hacer y hayan entregado su exámen tienen la posibilidad de hacer distintas acciones en el aula.
4. Reactivamente, tendrás que controlar la clase y a tus alumnos, lo que te distrae de corregir el exámen.
5. Al terminar un exámen, le colocas la nota final y se entrega al alumno al colocarlo a la derecha, consiguiendo así puntos de reputación.

## 2.2. Desarrollo de la historia
La historia toma lugar en el Aula 33.

Comienzas corrigiendo a **niños** y a medida que avances en la partida, las noticias sobre la popularidad de Darla Nota se expanden y empiezan a meter a **adolescentes** e incluso **adultos** en tu clase, subiendo así la dificultad.

Con el tiempo, empiezan a venir alumnos de todas las formas, como **alienígenas**, **inteligencias artificiales**, **ex convictos**, **demonios**, etc. La clase se vuelve más y más caótica hasta que acaba la partida con el despido de Darla Nota, la cuál se mueve a otra escuela para empezar nuevamente.

## 2.3. Finales
La partida termina si la popularidad de Darla Nota disminuye demasiado, despidiéndose y teniendo que irse a otra escuela a impartir clase.

Posiblemente, exista un final en el caso de que el jugador se mantenga vivo mucho tiempo, pero no está decidido aún. Este final dependerá de las acciones del jugador.

# 3. Mecánicas
## 3.1. Escritorio de Darla Nota
Es la zona de trabajo principal de Darla Nota. Desde aquí es donde corrige los exámenes de los alumnos.
### 3.1.1. Silla de profesora
Pinchando en la silla de la profesora, Darla Nota se sienta en su escritorio, lo que le hace incapaz de moverse hasta que se levante pulsando un botón. Esto hace que sea más simple de controlar las cosas del escritorio.

### 3.1.2. Exámenes
Cada examen viene con preguntas y respuestas aleatorizadas de una lista predeterminada. Todos los puntos conseguibles en un exámen suman 10, y los exámenes son de distintas asignaturas, siendo del color de la asignatura asignada:
 -(DEFINIR ASIGNATURAS)

En la parte superior muestra el nombre del alumno y a la derecha se puede introducir la nota sacada con botones de + y -. Debajo del exámen hay varías preguntas que se pueden marcar cómo correctas o incorrectas, sumando automáticamente la nota arriba, pero se puede cambiar con los botones antes mencionados. Abajo del todo, hay botones para navegar entre las hojas (en caso de haber más de una), y en la parte superior derecha un botón para finalizar la corrección y entregar el examen.

### 3.1.3. Hojas de soluciones
En tu cajón se encuentran unas carpetas (por colores) con el temario de cada asignatura. Pinchar en una carpeta la hace aparecer en tu mesa. Puedes navegar entre las hojas para encontrar la información que buscas.
Todas las respuestas tienen una solución objetivamente correcta o incorrecta, basándose en la información en las carpetas.

### 3.1.4. Pila de exámenes
La pila de exámenes se va reduciendo o ampliando dependiendo de los exámenes que quedan por corregir. Se puede distinguir el color de cada exámen en la lista para saber la asignatura, pero inicialmente nada más. Al principio, la máquina ordenadora siempre te entrega el último examen de la lista, es decir, el más antiguo.

## 3.2. Alumnos
En el aula entrarán tantos alumnos como sillas libres. Cada alumno tendrá sus estadísticas propias que determinará su comportamiento y respuestas de los exámenes.

Cuando un alumno no ha entregado su examen, entrará en modo “**Exámen**” en donde tardará un tiempo (determinado por las estadísticas del estudiante) en terminarlo y colocarlo en la lista. Una vez hecho esto, el alumno entrará en modo “**Espera**” donde tendrá posibilidades de hacer distintas acciones, como por ejemplo pelearse, dormirse, preguntar a la profesora, etc. Si estas acciones generan caos en el aula, y tienden a hacerlo, será la misión del jugador detenerlas lo antes posible, o correrá el riesgo de que afecte demasiado a su reputación. Para ello, las misiones se detendrán interactuando con los alumnos o haciendo ciertos minijuegos. Tras terminar una acción, tendrá un pequeño *cooldown* antes de poder hacer otra acción.

El alumno seguirá en modo “**Espera**” hasta que su exámen sea corregido, entonces entrará en modo “**Lectura**”, y tardará unos segundos en leer y comprobar el examen. Tras finalizar el modo lectura tiene tres opciones dependiendo del examen y del alumno:
**Modo “Acción”:** Depende de la nota y del alumno específico, pudiendo enfadarse con la profesora, o actuar contra otros alumnos. Es el caso más raro, pero no poco frecuente. Tras esto, entrará de nuevo en el modo “**Exámen**” o se irá del aula.
**Modo “Celebrar”:** En caso de aprobar, y no hacer una acción, el alumno simplemente celebrará durante unos segundos antes de entrar nuevamente en el modo “**Exámen**”.
**Modo “Suspenso”:** No hace ninguna acción, pero al no haber aprobado, el alumno se va del aula. Tras un rato, es sustituido por otro.

### 3.2.1. Estadísticas de alumnos
Al generar un alumno nuevo, el juego aleatoriza las siguientes estadíticas:
- **Concentración:** El tiempo que tardan en finalizar el examen (cuánto más alta, más rápido).
- **Conducta:** Controla la probabilidad de que realice eventos (muy baja equivale a pocos eventos).
- **Capacidad:** Determina la nota que tiende a sacar en los exámenes.
- **Notoriedad:** Cantidad que afectan sus acciones a tu reputación.
- **Insistencia:** La dificultad que tiene el jugador de finalizar una acción (cuanto más alta, más complicado). *Está determinada por el **grupo**, no por el **tipo** del alumno*

### 3.2.2. Tipos de alumnos
Las estadísticas del alumno determinan su tipo, lo cual afecta a su apariencia y a las acciones que tiende a tomar:
| **Tipo** | **Descripción** | **Acciones más frecuentes** |
| --------- | --------- | --------- | 
| Genérico | Estadísticas que no cumplen ninguno de los siguientes casos. | Todas |
| Empollón | Alta capacidad y concentración. | Levantar la mano |
| Revoltoso | Alta conducta. | Hacer ruido |
| Violento | Alta conducta y notoriedad. | Pelearse |
| Lento | Baja capacidad y concentración. | Dormirse |


### 3.2.3. Grupos de alumnos
A medida que avance la partida, irán apareciendo distintos grupos de estudiantes. Esto afectará a las estadísticas, con ciertos modificadores de cada grupo, y a sus acciones disponibles (por ejemplo, un Niño podrá hacer cosas como dormirse en clase, mientras que un Superviviente puede plantar un campamento en el aula).
Al principio de la partida comienzan con solo **Niños**, como nivel más sencillo, pero luego comienzan también a llegar **Adolescentes** y luego **Universitarios**. Tras eso, irán entrando aleatoriamente otros tipos de alumnos.

| **Grupo** | **Descripción** | **Modificadores** |
| --------- | --------- | --------- |
| Niños | Surgen durante la primera fase del juego para que el jugador se prepare. | Alumnos iniciales. Insistencia baja. |
| Adolescentes | Presentan el primer avance de dificultad. | Alumnos siguientes. Insistencia media. |
| Universitarios | Último paso de la progresión “normal”. A partir de aquí comienzan a aparecer sin orden. | Alumnos avanzados. Insistencia moderada. |
| Minorías | Aparecen durante todo el juego pero con menos posibilidad. | Alumnos con estadísticas exageradas. Insistencia media. |
| Robots | Su cerebro son Inteligencias Artificiales, por lo que no son del todo fiables. | Alumnos con alta conducta y capacidad alta o baja. Insistencia baja. |
| Alienígenas | Han llegado de otro planeta escuchando las leyendas de Darla Nota. | Alumnos con alta capacidad, notoriedad y conducta. Insistencia alta. |
| Supervivientes | El mundo se ha ido a la mierda, solo quedan estos supervivientes. | Alumnos con alta conducta y baja notoriedad. Insistencia alta. |
| Demonios | Son negativos para el aula, pero cuantos más tengas, más probabilidad hay de que atraigana ángeles. | Alumnos con alta conducta y notoriedad. Insistencia muy alta. |
| Ángeles | Toda profesora querría tenerlos en su aula… siempre y cuando no actuen… | Alumnos con alta capacidad, concentración y baja conducta, pero con MUCHA notoriedad. Insistencia muy alta. |

## 3.3. Reputación
La reputación es lo que determina la calidad de tu trabajo como profesora.  Si tu reputación cae demasiado bajo, te despiden y acaba la partida. Tu reputación depende principalmente del cumplimiento de objetivos, de mantener el orden en clase y de aprobar los exámenes correctos. También se podrá ver modificada por la nota media que saquen tus alumnos, habilidades y modificadores que el jugador compre durante la partida. 

### 3.3.1. Superintendente
Es quien te contrata. Tu reputación depende de lo que él opine de ti. 
Cada X tiempo (o en momentos concretos de la partida), el superintendente entrará y hará una valoración de tu trabajo. Además, si no te despide, te dará una lista de objetivos. El cumplir o no cumplir con los objetivos afectará a tu reputación de forma destacable. 

## 3.4. Movimiento y apuntado
Cuando el jugador no está sentado en la silla, se puede mover libremente por el aula. Para apuntar, se mueve el ratón y se interactua con un puntero en el centro de la pantalla. Algunas acciones harán que los alumnos también se muevan por el aula, o incluso fuera de esta.

## 3.5. Tienda
Interactuar con la pizarra te llevará a la sección de la tienda, donde podrás gastar tu sueldo en comprarte complementos de la clase o escritorio. Estos se mantendrán entre partidas.

### 3.5.1. Sueldo
Darla Nota recibe una cantidad de dinero por el tiempo trabajado. Cumplir los objetivos del superintendente te aumentará el sueldo.

## 3.6. Modificadores
Cada cierto tiempo, el juego se pausará y se le presentarán al jugador 3 posibles modificadores. El jugador podrá elegir uno que tome efecto durante el resto de la partida.

# 4. Intefaz
## 4.1. Controles y plataformas
## 4.2. HUD
## 4.3. Audio

# 5. Mundo del juego
## 5.1. Personajes

# 6. Estética y contenido

# 7. Experiencia de juego

# 8. Referencias
Las principales inspiraciones de nuestro diseño son:
- **Papers, please:** Por la mécanica de mantenerse en la misma habitación mientras trabajas con documentos.
- **Smile for me:** Por la apariencia de espacios 3D con modelos 2D dibujados a mano para los personajes.
- **Vampire Survivor:** Por los modificadores aleatorios.
- **Hades:** Por la progresión *rogue like y aleatoriedad de sus encuentros.

---
