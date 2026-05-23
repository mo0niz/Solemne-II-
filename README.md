# Solemne-II-
## Pensamiento computacional
## Nombre del proyecto: Vórtice Óptico
*Por Isidora Muñoz*


**¿Qué es el proyecto?**

Vórtice Óptico es un sistema visual interactivo desarrollado en p5.js inspirado en el Op Art. La obra genera dos estructuras geométricas compuestas por rectángulos que responden continuamente a la interacción del usuario mediante deformaciones espaciales, variaciones de profundidad y movimiento aparente.

El sistema funciona mediante reglas computacionales que transforman una composición geométrica simple en una experiencia visual dinámica y reactiva.

**¿Qué se ve en pantalla?**

La composición está formada por dos túneles ópticos construidos a partir de rectángulos repetidos en blanco y negro. Ambas estructuras se encuentran separadas por un eje vertical central que organiza visualmente la composición.

A medida que el usuario mueve el cursor, los rectángulos modifican su posición y profundidad aparente, generando una ilusión de movimiento y distorsión espacial.

Además, existe una oscilación continua que provoca que la composición nunca permanezca completamente estática.

**Elementos visuales utilizados**

*-Rectángulos concéntricos.*

*-Contraste blanco y negro.*

*-Eje central vertical.*

*-Repetición modular.*

*-Deformación geométrica.*

*-Movimiento continuo.*

*-Simetría bilateral.*

*-Profundidad aparente.*

**Descripción conceptual**

*Idea central:*

El proyecto explora cómo una estructura geométrica repetitiva puede generar sensaciones de movimiento, profundidad y transformación visual sin representar movimiento físico real.

La propuesta toma como referencia algunos principios fundamentales del Op Art, particularmente la repetición, el contraste y la percepción visual. En lugar de reproducir una obra existente, estos principios son reinterpretados mediante programación interactiva para construir un sistema capaz de modificar continuamente su comportamiento.

El usuario deja de ser un observador pasivo y se convierte en un agente que altera directamente la percepción visual de la composición.

**Corriente de diseño: Op Art**

El Op Art fue un movimiento artístico que exploró fenómenos perceptuales mediante patrones geométricos, contrastes visuales y estructuras repetitivas capaces de producir ilusiones ópticas.

Las obras de este movimiento generan sensaciones de vibración, movimiento o profundidad utilizando únicamente elementos gráficos bidimensionales.

**Referentes**

*Victor Vasarely*:
Sus composiciones utilizan estructuras geométricas repetidas y deformadas para producir ilusiones espaciales complejas. La utilización de módulos repetitivos y transformaciones progresivas influyó directamente en la construcción de los túneles ópticos presentes en el proyecto.

*Bridget Riley*:
Sus investigaciones sobre percepción visual, ritmo y movimiento aparente inspiraron la búsqueda de efectos dinámicos producidos exclusivamente mediante relaciones geométricas.

**Imagen de referencia**

![Op Art](solemne%20PC/op%20art.webp)

**Decisiones de diseño**

*¿Por qué elegí rectángulos?*:
Los rectángulos concéntricos permiten construir estructuras visuales capaces de generar sensación de profundidad utilizando únicamente repetición y escala.
Su geometría simple facilita la comprensión de las deformaciones producidas por el sistema y mantiene una relación directa con diversos referentes históricos del Op Art.
La repetición progresiva de rectángulos genera una lectura visual similar a un túnel o corredor espacial, reforzando la ilusión de profundidad.

**¿Por qué elegí blanco y negro?**

El contraste extremo entre blanco y negro es uno de los recursos visuales más característicos del Op Art.
Eliminar el color permite concentrar la atención en:

-La forma.

-El ritmo visual.

-La repetición.

-La deformación geométrica.

-La percepción del movimiento.

-Esta decisión busca potenciar las ilusiones ópticas sin introducir elementos visuales innecesarios.

**¿Por qué existen dos túneles?**

La utilización de dos estructuras genera equilibrio visual y tensión espacial dentro de la composición.
Además:

-Refuerza la simetría.

-Organiza la lectura visual.

-Produce contraste entre ambos lados.

-Amplifica la percepción de profundidad.

-La línea central actúa como eje organizador y referencia espacial para el observador.

**¿Por qué el usuario modifica la geometría?**

Porque gracias a la posición del cursor que fue incorporada como variable principal del sistema, el usuario puede interactuar con ella.

-La interacción permite modificar:

-Profundidad aparente.

-Separación entre elementos.

-Intensidad de deformación.

-Movimiento visual.

De esta manera el comportamiento de la obra depende directamente de las acciones del usuario.

**¿Por qué existe movimiento continuo?**

El sistema incorpora una animación constante basada en funciones matemáticas relacionadas con el tiempo.
Esta decisión responde a dos objetivos:

*Conceptual*
Simular la vibración visual característica de muchas obras asociadas al Op Art.

*Técnico*
Generar un output dinámico que evoluciona continuamente incluso cuando el usuario no interactúa.


## Input / Output y Sistema

**Inputs**

El sistema recibe información mediante:

Mouse X
Controla la separación y expansión de los rectángulos.

Mouse Y
Controla la profundidad aparente y el nivel de deformación espacial.

Mouse Pressed
Modifica características visuales adicionales del sistema.

**Procesamiento**

1 El sistema detecta la posición actual del cursor.

2 Calcula los parámetros de deformación correspondientes.

3 Recorre cada rectángulo mediante un bucle.

4 Aplica transformaciones progresivas a cada elemento.

5 Evalúa condiciones específicas mediante estructuras condicionales.

6 Actualiza continuamente la composición en cada frame.

7 Dibuja nuevamente la escena.

**Reglas del sistema**

-Los rectángulos más externos poseen mayores dimensiones.

-Los rectángulos internos construyen la sensación de profundidad.

-La posición del cursor modifica la geometría de ambas estructuras.

-Los colores alternan entre blanco y negro.

-La composición cambia continuamente a lo largo del tiempo.

-Las transformaciones responden a reglas matemáticas predefinidas.

**Outputs**

El sistema genera:

-Ilusión óptica de profundidad.

-Sensación de movimiento.

-Distorsiones geométricas.

-Variaciones espaciales.

-Composición visual dinámica.

-Respuesta inmediata a la interacción.
