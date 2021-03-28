# Historia de osu! 2008

![](img/2008.jpg)

## Enero

peppy estuvo desaparecido en acción (del inglés MIA, Missed in action) en Japón desde el 17 de diciembre de 2007 hasta el 20 de enero de 2008. De alguna manera se las arregló para alejarse de la base de código de osu! durante un mes completo, por lo que no hubo actualizaciones importantes (mientras que la comunidad estaba bastante estancada durante este tiempo).

![](img/2008-01_01.jpg)

## Febrero

![](img/hard_rock.png "Hard Rock \(v1\)") ![](img/sudden_death.png "Sudden Death \(v1\)") ![](img/double_time.png "Double Time \(v1\)")

Los jugadores recibieron desafíos adicionales en forma de [mods](/wiki/Game_modifier) ([Hard Rock](/wiki/HR), [Sudden Death](/wiki/SD) y [Double Time](/wiki/DT)). La experiencia de juego se mejoró considerablemente con la adición de imágenes y sonidos de cuenta atrás, número y colores personalizados para los combos, clasificaciones de la sección O/X (Pasar/Fallar), intros de cuenta atrás, secuencias de comandos de colores de fondo, control de volumen por sección de tiempo y (quizás lo más importante) la introducción de soporte de [storyboard scripting](/wiki/Storyboard_Scripting). Se intentó pasar osu! al framework XNAv2, pero peppy decidió que la nueva versión era inútil y reducía el rendimiento general. A partir de ese momento se utilizó XNA1.1, que se adaptó a las necesidades de osu! con miles de líneas reescritas y "hacks" para hacer de osu! lo que era. También se implementó un nuevo motor de renderizado de texto, que permite mostrar fuentes muy nítidas en cualquier tamaño de letra. Lo que hace posible mostrar más información del [editor](/wiki/Beatmap_Editor) y hacer que el juego se vea mucho mejor en general.

## Marzo

![](img/relax.png "Relax \(v1\)") ![](img/half_time.png "Half Time \(v1\)")

Para contrarrestar los nuevos mods de febrero, llegaron los mods [Relax](/wiki/RL) (RX) y [Half Time](/wiki/HT) (HT) para facilitar la vida a los jugadores este mes. Ahora los usuarios pueden hacer capturas de pantalla e importar y exportar [replays](/wiki/Replay). Por primera vez, las animaciones pueden ser [storyboarded](/wiki/Storyboards) y se ha añadido la pantalla de selección de [skin](/wiki/Skinning). Las optimizaciones de rendimiento permitieron reducir en un 82% la carga de la pantalla de selección de canciones (mediante un nuevo formato para la base de datos local de mapas de ritmo). Se han realizado otros ajustes de rendimiento, como la introducción de la conmutación del límite de fotogramas y otras opciones gráficas. El proyecto [Bancho](/wiki/Glossary#bancho) se inició el 24 de marzo de 2008. La idea era crear un componente de servidor para la familia osu!, que maneja las comunicaciones entre usuarios y elimina la dependencia de [IRC](/wiki/Internet_Relay_Chat) (Internet Relay Chat).

## Abril

No es broma, Bancho se puso en marcha en abril, y también los paneles de usuario del [Extended Chat](/wiki/Chat_Console#extended-chat-console). Los usuarios ahora podían ver lo que otros usuarios estaban haciendo en sus paneles de usuario, así como interactuar con ellos haciendo clic para ser espectadores. Se estrenó el sistema de envío automático de errores, se implementó la compatibilidad con xfire y se renovaron el menú principal y la interfaz del editor (con nuevos iconos de [LuigiHann](https://osu.ppy.sh/users/1079)). La interfaz del chat se ha mejorado con el botón "mostrar chat", la finalización de pestañas y las alertas de resaltado de apodos. La pantalla de clasificación ahora muestra los puntos necesarios para alcanzar el siguiente rango.

## Mayo

![](img/taiko.png "Taiko Mod")

El modo [Taiko](/wiki/Game_mode/osu!taiko) vio la luz por primera vez en este mes, así como otra importante adición, el soporte de guiones gráficos `.osb`. También se han puesto a disposición los deslizadores multiparte y la mensajería privada en el chat.

## Junio

Se alcanzó un acontecimiento importante en la historia de osu! con la adición del modo de juego [Multi (multiplayer)](/wiki/Multi). Se ampliaron las opciones de diseño en cuanto a gráficos y sonidos. Por último, el chat multicanal fue posible por primera vez.

## Julio

El editor, multijugador, storyboard, los gráficos y la consola de chat han recibido numerosas mejoras este mes. La pantalla de Opciones recibió un nuevo diseño, y se introdujeron [custom key bindings](/wiki/Options/Keyboard_Bindings).

## Agosto

Siguiendo la tendencia marcada por julio, sería difícil encontrar un aspecto de osu! que no haya sido mejorado u optimizado en este mes. En el ámbito de las novedades, se han añadido etiquetas a los mapas de ritmo y se ha implementado la compatibilidad con múltiples monitores a nivel experimental. Se ha creado un nuevo método de desbloqueo del juego para evitar que la gente abuse de la función de pausa (que ahora requiere que los jugadores alineen su cursor al lugar donde estaba antes de la pausa para poder continuar).

Se han añadido las mejores puntuaciones personales en línea a la selección de canciones, cumpliendo así con una antigua petición que requería una optimización bastante importante de la base de datos. Se han introducido mejoras gráficas en la pantalla de clasificación y en varios elementos de la apariencia por defecto, con el fin de que resulten más limpios y nítidos que antes. Se ha implementado la visualización de los sprites de puntuación de la barra deslizante (10/30). Se han introducido mejoras en la configuración de las partidas multijugador, que permiten transferir el control del anfitrión. Se añadieron muchos nuevos [chat commands](/Chat_Console#commands-list) para la comodidad del usuario.

Se ha añadido un nuevo estado de clasificación "![](img/fire.gif) [Approved](/wiki/Approved)" para mapas de gran calidad pero que exceden la longitud de la clasificación, la dificultad u otros límites de alguna manera. Los mapas en este estado no se suman a las puntuaciones del jugador, pero tienen tablas de puntuación y actúan de otra manera como un mapa ![](img/heart.gif) [Ranked](/wiki/Ranked).

## Septiembre

![](img/flashlight.png "Flashlight \(v1\)") ![](img/spun_out.png "Spun Out \(v1\)") ![](img/auto.png "Auto \(v1\)")

Este mes se han presentado un montón de nuevos mods: [Flashlight](/wiki/FL), [Spun Out](/wiki/SO) y [Auto](/wiki/AT). Auto crea una IA que completa (casi) cualquier beatmap con una [accuracy](/wiki/Accuracy) perfecta, y también se puede acceder a ella a través del modo de prueba del editor. Los límites del diseño del beatmap se han ampliado con la adición de más elementos personalizables (including [comboburst images](/wiki/comboburst), la muestra de sonido de las palmas, la capacidad de asignar muestras de sonido a puntos finales individuales del deslizador y secciones de sincronización heredadas. La pantalla de selección de canciones también ha sido revisada.

## Octubre

Se avanzó en la implementación de OpenGL y en el debut del próximo modo de juego ([Catch the Beat](/wiki/Game_mode/osu!catch), en un entorno de pruebas privado. Se reescribieron muchas de las partes internas de osu!, lo que equivale a más de 4.000 líneas de código completamente renovado, con el fin de hacer que los modos de juego sean más modulares y que se puedan añadir futuros modos con mayor facilidad. Debido a estos grandes cambios, no hubo lanzamiento público en octubre.

## Noviembre

![](img/fruit_ryuuta.png "The catcher of Catch the Beat")

En noviembre se introdujo un nuevo modo de juego, Catch the Beat. Se estrenó la compatibilidad con OpenGL, lo que permite que osu! funcione en la mayoría de los sistemas. Otras novedades de esta actualización son la compatibilidad con la lista de amigos del juego, las pestañas de chat privadas, un nuevo tutorial/[offset wizard] (/wiki/Options/Offset_Wizard) y osu!direct (un descargador de mapas de ritmo en el juego para los supporters).

Debido a que la gente con un gran número de beatmaps se quejaba del tiempo de carga de osu!, peppy pasó innumerables días optimizando todo lo posible, lo que resultó en un aumento de rendimiento casi inconmensurable en una escala (algo más de 9.000). Los tiempos de carga de más de un minuto se redujeron a sólo milisegundos.

## Diciembre

El último mes de 2008 tuvo mucho que ver con el desarrollo de osu! En las segundas Navidades de osu! se implementó la primera versión del editor de guiones gráficos, lo que hizo que la creación de guiones fuera mucho más accesible para los usuarios. Se añadió un segundo modo multijugador: "Tag Play". Se trataba de un modo cooperativo en el que los jugadores se turnaban para interpretar un beatmap. Otra adición al modo multijugador fue la "Precisión como condición de victoria". Se integraron los estados de MSN y Yahoo, y los usuarios podían personalizar completamente las combinaciones de teclas y las palabras de activación del chat.

Se han añadido vistas previas en miniatura y audibles al listado de beatmaps en línea, lo que facilita la búsqueda de un beatmap que te gustaría reproducir.

Otro acontecimiento notable fue que las puntuaciones de [Catch the Beat](https://osu.ppy.sh/community/forums/topics/7996) se borraron durante este mes. Desde entonces, el multiplicador de puntuación de los mods se ha modificado también en el modo Catch the Beat.

## El Futuro

*"Piensa en grande, y espera en grande."* — peppy
