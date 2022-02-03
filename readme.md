# SISTEMA DE DISENO

https://www.notion.so/Design-system-1bdbab2c4c354f80944c1fb93d3743ff

https://atlassian.design/

## Que es un sistema de diseno?

Los sistemas de diseño están en todas partes, su función tiene que ver con la planeación y la construcción de productos (no necesariamente digitales).

Hace muchos años, un hombre llamado Malcom McLean transportaba mercancías en sus barcos, pero la descarga de todos estos objetos era muy compleja, todo tenía tamaños y pesos distintos. Para resolver este problema, McLean trabajo con un grupo de ingenieros y crearon los containers o contenedores, cajas de metal que agilizan este proceso gracias la estandarización de todos los sistemas y medios de transporte de estos contenedores.

Esto mismo sucede cuando trabajamos con software, buscamos una manera de agilizar nuestros desarrollo estandarizando todos estos procesos. Los sistemas de diseño son conjuntos de reglas para un producto que se modifica dependiendo de las necesidades del mismo, son una decisión de negocio. Cualquier persona del equipo de producto debe estar involucrada en este proyecto y poder consultar toda esta documentación.

Para crear un sistema de diseño podemos usar diferentes herramientas como Bear, Notion o Evernote, lo importante es que podamos escribir y organizar estos sistemas.

## PRINCIPIOS

### 1.📝 Accesibilidad:

Todo tipo de usuario debe poder acceder a la plataforma.

- 1.1. Predecible: Debe ser fácil saber lo que sucederá luego de hacer una acción.
- 1.2. Operable: Los usuarios deben saber como poder usar la plataforma intuitivamente.
- 1.3. Entendible: El sistema debe ser entendible para el usuario final. El idioma no puede ser mandarín si es para hispanos.
- 1.4. Robusta: Debe ser capaz de albergar a varios tipos de usuarios: Daltónicos, ciegos, etc…

### 🛠 Consistencia:

Tratar de que todo sea de la misma manera. Esto hará que el usuario pueda usar la plataforma de mejor manera y menos confuso.

### ♻ Reusable:

Evitar tener que volver a hacer trabajo que ya se hizo. Por ejemplo, si se creo un botón, que ese botón no se tenga que volver a hacer o modificar.

### 🚻 Compartible:

Compartirlo y que las personas puedan volver a acceder desde cualquier lugar.

### Otros principios:

- 🧑 Control de usuario: El usuario debe sentir que él tiene el control sobre el software.
- 🙏 Perdonar: Nuestro software debe permitir al usuario hacer las cosas de nuevo. Por ejemplo, si escribe una contraseña mal, permitir que la vuelva a poner.
- ✔ Percepcion de Estabilidad: Darle a entender al usuario que todo se mantiene igual para que su aprendizaje sea más rápido.

“La combinación y creación de estos principios son los que nos permitirán crear elementos gráficos para nuestro software 🚀”

## PARADIGMAS

### Procedural

Permite la construcción de funciones que a futuro se van a reconstruir a sí mismas. Se basa en objetos ya hechos para obtener resultados diferentes. Por ejemplo, cuando se usa código se utiliza el concepto procedural.

### Atómico

Le da una organización a los elementos: átomos, moléculas, organismos, templates, páginas. Es decir, ir desde los elementos más sencillos como las etiquetas más básicas, hasta los elementos mayores que corresponden a la unión de varios átomos, moléculas, organismos y templates para obtener una página.

### DRY

Don’t Repeat Yourself. No repetir los mismos elementos.

## COMPONENTE

Los componentes forman parte de un todo, así como las velas de un pastel, el piso de los edificios o las partes de un motor cada una con su funcionalidad. Lo mismo pasa con las interfaces, vamos a construir diferentes elementos y herramientas para que los usuarios logren cumplir sus objetivos.

Todos los componentes tienen una entrada y una salida, el usuario realiza una acción y los elementos deben responder de alguna forma (feedback), esta es la forma de comunicamos con los usuarios, trabajamos haciendo conversaciones para informar que todo esta funcionando correctamente y qué pasos deben seguir a continuación. Este proceso de comunicación lo conocemos como interacción.

Partes de un componente:

- Nombre (así evitamos diferentes definiciones y establecemos los objetivos y funciones de nuestros componentes)
- Descripción y solución (en qué problema estamos trabajando y cómo deberíamos implementar estas soluciones)
- Behavior (el comportamiento de nuestros componentes dentro del sistema)
- States (las variaciones y distintos comportamientos que pueden tener nuestros componentes dependiendo de su contexto)

## FUNDATIONS

Los sistemas de diseño son un conjunto de reglas que organizamos con nuestros equipos, y los fundations son las partes más básicas que podemos configurar en nuestro sistema. Vamos a repasar cada una de estas bases mientras escribimos la documentación en Notion:

- Tipografía
- Colores
- Layout y spaces (son las formas y espacios fundamentales que utilizamos para ordenar los elementos de nuestro sistema)
- Iconografía
- Styles (nuestra marca puede presentarse con estilos juguetones o realistas, lo importante es definir tan claro como sea posible qué intentamos transmitir)
- Tono (con qué personalidad o de qué forma debemos hablar con nuestra audiencia)

### Tipografia

Cuando trabajamos con tipografía para software debemos tener en cuenta las implicaciones que estas pueden generar si trabajamos para dispositivos móviles o los requerimientos técnicos de alguna pantalla en particular. Un buen lugar para encontrar tipografías listas para el desarrollo y diseño de nuestros productos es Google Fonts.

Para definir y clasificar las características y peculiaridades en los elementos de nuestro diseño podemos basarnos las etiquetas de HTML para títulos y encabezados (H1, H2, H3, H4, H5 y H6), párrafos (p) y párrafos más pequeños (small). Podemos definir que los títulos se trabajen en negrita y con tamaños de fuente más grandes, lo importante es que estas reglas se acomoden al sistema de diseño que estamos trabajando.

https://chrome.google.com/webstore/detail/whatfont/jabopobgcpjmedljpbcaablpmlmfcogm

#### Cómo evitar colores constrastantes

Cuando utilizamos colores demasiado contrastantes podemos generar efectos visuales algo molestos, problemas en el render o lineas blancas y negras en los bordes de los elementos. Para solucionar estos problemas visuales debemos elegir nuestros colores con mucho más cuidado, moviendo los colores hacia alguna tonalidad para evitar colores demasiado contrarios.

### Colores

Los colores también deben llevar algún tipo de clasificación ya que definen el estilo visual de nuestro sistema. La paleta de colores define el estilo de tu sistema de diseño y ayuda a definir el sistema de diseño, diferenciando la identidad de la marca y del resto de efectos y elementos visuales.

Muchos sistemas de diseño clasifican sus colores según sus productos (un color para ventas, otro para servicio al cliente, etc), otros utilizamos Material Design y clasificamos los colores como actions colors, _secondary colors _ y otros niveles de clasificación. En realidad no importa, podemos tomar cualquier otro paradigma de fundamentos de color para nuestros sistemas, lo importante es clasificar el uso de estos colores y asegurarnos de que todo el equipo los entiende.

Para escoger estos colores debemos tener en cuenta los colores de la marca, los colores principales (colores de acción o call to actions), colores secundarios, los grises y los colores de fondo. El trabajo se puede complicar un poco cuando tenemos en cuenta todos estos colores, pero el resultado será mucho mejor, los colores funcionaran correctamente entre todos.

### Reglas de espaciado

Las reglas de espaciado son muy útiles cuando trabajamos nuestros sistemas de diseño para anticipar la visualización de nuestras interfaces en diferentes dispositivos.

- Ritmo: Qué tan seguido aparecen elementos arriba o debajo de otros.
- Padding: Es el espacio dentro de nuestros elementos, nos ayuda a enfocar y transmitir los estilos de nuestra marca.
- Margin: Es el espacio entre elementos pero hacia afuera, nos permite generar ritmo visual o para separar elementos de secciones diferentes.
- Border: Trabajamos con el borde de los elementos, recuerda que las dimensiones o medidas de nuestros objetos se verán afectadas al aplicar o no aplicar estos bordes.
- Layout: Vamos a definir la forma general en que combinamos las columnas, headers y barras de navegación de nuestras plataformas, gracias a estas reglas podemos garantizar que nos adaptamos a todos los tamaños y dispositivos.

### Animacion

Los 12 principios de la animación son un conjunto de reglas creadas por Disney para la animación de personajes, pero muchos de estos principios son muy útiles para ciertos aspectos de la animación de elementos de nuestras interfaces:

- Anticipación: Vamos a a preparar a los usuarios para la acción que viene a continuación, por ejemplo, antes de desconectar la señal de un teléfono podemos animar el icono del avión y transmitir que no señal durante algún tiempo.
- Estirar y encoger: Nos ayuda a generar drama sobre algún elemento, por ejemplo, para dramatizar la animación de un botón cuando el usuario ha cometido un error o alguna acción incorrecta.
- Entradas y salidas lentas: Nos permite introducir o remover elementos de la plataforma, tal vez conozcas estas animaciones como Fade In y Fade Out.
- Acciones secundarias: Todas las microinteracciones trabajan con este principio, estas animaciones nos ayudan a transmitir o dar información adicional como respuesta a alguna acción de los usuarios.
- Timing: Mientras más detalles añadimos a las animaciones, más rápidas o lentas se pueden percibir. Podemos utilizar estos efectos visuales para transmitir apuro o tranquilidad mientras la plataforma esta cargando.
- Exageración: Así como las acciones secundarias, podemos exagerar los movimientos de nuestros elementos para transmitir alguna sensación, por ejemplo, cuando el usuario quiere eliminar su cuenta.

También vamos a utilizar Animate.css, una librería para trabajar con todo tipo de animaciones sin mucho trabajo, también nos facilita el proceso de documentación de las reglas de animación de nuestro sistema.

### Voz y tono

Los textos o copies que acompañan nuestros diseños también hace parte de la forma en que te comunicas con tus usuarios. Al incluir la voz y el tono de nuestros productos en el sistema de diseño conseguimos que todo el equipo tenga una guía sobre la personalidad de la marca, recuerda que toda esta documentación debe contribuir a la consistencia y comunicación con nuestros equipos.

Para definir la voz y el tono de nuestros sistemas debemos tener en cuenta los siguientes aspectos:

- Buzzwords: las palabras más usadas de nuestro producto
- Phrases: vamos a construir una librería de frases clave de nuestro producto
- Objetivo: el objetivo o la misión de nuestro producto en términos de voz y tono ayuda a que el equipo tenga orientación a la hora de crear nuevos textos o frases
- Características: definimos la personalidad de la marca, así tendremos mucho más contexto y podremos crear mejores copies para nuestra marca

### Iconografia

Los iconos son muy útiles para comunicar o resaltar características y funcionalidades de nuestros productos, podemos construir nuestras propias librerías de iconos personalizados o utilizar librerías como Font Awesome y completar los iconos que hagan falta si no tenemos un equipo tan grande.

Para definir las reglas y la documentación de una iconografía consistente debemos tener en cuenta los siguientes aspectos:

- Grid: Las medidas y lineamientos que deben seguir todos los iconos
- Shapes: Las formas o figuras que podemos utilizar
- Size: Qué tamaño deben tener nuestros iconos para estar alineados con la tipografía y el resto de la plataforma
- Styles: Cómo deben estar construidos visualmente nuestros iconos, podemos utilizar colores planos o podemos trabajar en iconos mucho más realistas, etc, lo importante es estar alineados con las reglas de nuestro sistema

### Hitos

Los hitos son características muy particulares o incluso personales de nuestros productos, las mejores marcas incluso pueden definirse y marcar su presencia sin necesidad de utilizar logos o nombres, tal es el caso de las animaciones de carga de Google o Slack.

## UI Kit

Los UI Kits son parte fundamental del sistema de diseño. Son librerías donde se alojan todos los elementos y componentes diseñados del producto. Un buen UI Kit es escalable y flexible a múltiples cambios

### Un sistema basado en personas

Un sistema de diseño se asegura que todo lo que estás diseñando se convierta en software, debemos asegurarnos de que todos los elementos estén conectados para hacer nuestro trabajo más eficiente.

Los sistemas de diseño nos ayudan a construir software en equipo, involucrando al equipo de desarrollo, de marketing, de finanzas, etc, todos aquellos que contribuyen a la hora de crear un nuevo software y ayudan a que el trabajo fluya y sea más eficiente.

## Iteracion

El proceso de creación de software no es tan definitivo como la creación de otros tipos de producto, son productos vivos que siguen mutando y desarrollándose en el tiempo. Los sistemas de diseño también pueden prever la forma de iterar, es decir, mejorar todos los días las construcciones y la forma de construir del equipo, lo más importante es que entre todos nos pongamos de acuerdo de manera fácil, rápida y efectiva.

Para organizar el proceso de iteraciones debemos documentar todos los cambios y problemas que nos encontramos para que todo el equipo este actualizado y logremos entender el trabajo de la misma forma. Vamos a seguir los siguientes pasos:

- Darle un nombre a la iteración
- Describir por qué estamos iterando, ¿qué problema vamos a resolver?
- ¿Qué solución encontramos a estos problemas?
- Cambios de estimación de conflictos, la duración y la dificultad estimada para trabajar esta iteración
