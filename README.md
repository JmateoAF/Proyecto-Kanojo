# Proyecto Kanojo
## Game Design Document (GDD) — Versión 0.1

**Estado:** Concepto inicial  
**Plataforma objetivo inicial:** PC  
**Motor propuesto:** Godot 4  
**Equipo:** Dos desarrolladores en formación  
**Objetivo principal:** Aprender a desarrollar videojuegos creando una experiencia original que pueda compartirse con la comunidad.

---

## 1. Visión del proyecto

Proyecto Kanojo es un simulador de vida social en 3D, de estética anime y personajes chibi, centrado en las relaciones interpersonales, la exploración y la vida cotidiana de un protagonista que descubre una conexión sobrenatural con cien posibles almas gemelas.

El jugador podrá recorrer una escuela y sus alrededores, conocer personajes, participar en actividades, tomar decisiones y desarrollar relaciones a su propio ritmo.

La experiencia combinará una historia principal con exploración libre y un mundo dinámico en el que los personajes tengan rutinas, horarios y acontecimientos propios.

### Objetivos del equipo

- Aprender programación de videojuegos, diseño de sistemas, narrativa interactiva y gestión de proyectos.
- Desarrollar un prototipo pequeño antes de ampliar el alcance.
- Utilizar recursos provisionales mientras se adquieren habilidades artísticas.
- Crear una propiedad intelectual original, sin depender de personajes o elementos protegidos de otras obras.
- Procurar que el resultado pueda publicarse gratuitamente o a un precio accesible, según las posibilidades del equipo.

## 2. Pilares de diseño

### 2.1. Relaciones y personajes

Las relaciones son el centro de la experiencia. Los personajes deben tener personalidad, preferencias, rutinas y vínculos propios, en lugar de funcionar únicamente como objetivos románticos.

### 2.2. Un mundo vivo

El entorno debe transmitir que la vida continúa aunque el jugador no esté interactuando con cada personaje. Los horarios, el calendario y los acontecimientos darán estructura a la experiencia.

### 2.3. Libertad con dirección narrativa

La historia principal proporcionará objetivos y acontecimientos importantes, mientras que la exploración y las actividades opcionales permitirán avanzar a un ritmo personal.

### 2.4. Una experiencia amable y optimista

El tono general será alegre, acogedor y cómico, con situaciones románticas y momentos emotivos. El fanservice, si existe, será moderado y no explícito. El terror y el horror no forman parte de la dirección creativa deseada.

### 2.5. Alcance progresivo

La visión final puede ser ambiciosa, pero el desarrollo se organizará en pequeñas versiones jugables. Ningún sistema complejo será obligatorio para validar las primeras etapas.

## 3. Premisa narrativa

El protagonista descubre que está vinculado por un fenómeno sobrenatural a cien posibles almas gemelas. Esta conexión surge de un error o equivocación de origen celestial.

El fenómeno no identifica de antemano a cien personas predeterminadas. Quiénes serán esas personas se descubrirá a medida que avance la vida del protagonista.

La resonancia favorece la posibilidad de que surjan conexiones especiales, pero no crea amor instantáneo ni obliga a los personajes a mantener una relación. La confianza, el afecto y los vínculos se construyen mediante decisiones, experiencias y tiempo compartido.

### Preguntas narrativas pendientes

- ¿Quién o qué cometió el error celestial?
- ¿Por qué afecta al protagonista?
- ¿Qué significa exactamente estar vinculado a cien almas gemelas?
- ¿Existen consecuencias por ignorar una conexión o tomar decisiones incompatibles con ella?
- ¿Cómo se descubrirán las nuevas conexiones y qué las hará reconocibles?

Estas cuestiones deberán resolverse sin perder el tono amable y cómico del proyecto.

## 4. Personajes y relaciones

El diseño contempla una posible plantilla final de cien personajes vinculados a la premisa, pero no exige desarrollar los cien desde el inicio.

Cada personaje importante debería disponer progresivamente de:

- Identidad y descripción.
- Personalidad, intereses y preferencias.
- Horario y lugares habituales.
- Relaciones con otros personajes.
- Diálogos y acontecimientos propios.
- Variables de relación relevantes.
- Actividades y posibles rutas narrativas.

El sistema deberá admitir distintos ritmos de relación: conexiones que surgen rápidamente, vínculos que evolucionan gradualmente y relaciones grupales.

La resonancia será un elemento narrativo y mecánico, no un sustituto de la interacción entre personajes.

## 5. Mundo y estructura temporal

### Entorno inicial

El escenario inicial estará compuesto por una escuela y una pequeña zona de sus alrededores. El tamaño se ampliará solo cuando los sistemas básicos funcionen.

### Exploración

- Cámara libre durante la exploración.
- Controles de movimiento en tercera persona.
- Interacción contextual con personajes y objetos.
- Escenas cinematográficas en acontecimientos narrativos importantes.

### Calendario y rutinas

El mundo podrá incluir:

- Hora del día y días de la semana.
- Horarios escolares y actividades cotidianas.
- Ubicaciones habituales de los personajes.
- Eventos programados y acontecimientos especiales.
- Actividades que cambien según la fecha o el estado de las relaciones.

La simulación se desarrollará gradualmente. La primera versión solo necesitará un horario sencillo para uno o dos NPC.

## 6. Mecánicas principales

Las siguientes mecánicas constituyen la visión general y no tienen que estar todas presentes en el primer prototipo:

1. Explorar el entorno.
2. Hablar con personajes.
3. Elegir respuestas y acciones.
4. Participar en actividades compartidas.
5. Desarrollar y consultar relaciones.
6. Descubrir acontecimientos asociados a la resonancia.
7. Seguir el calendario y los horarios.
8. Desbloquear nuevas escenas, actividades y zonas.

## 7. Dirección artística y audio

La dirección artística propuesta es 3D estilizado, con personajes chibi y una presentación de inspiración anime.

Durante el prototipado se podrán utilizar recursos externos y modelos provisionales. No se exige crear personajes originales ni animaciones complejas antes de validar la jugabilidad.

Cuando sea posible, los recursos definitivos deberán compartir una dirección visual coherente en proporciones, materiales, colores, iluminación y animación.

Se mantendrá un registro de los recursos externos utilizados, sus autores, fuentes y licencias.

La música y los efectos de sonido se incorporarán según las necesidades de cada etapa.

## 8. Propuesta técnica inicial

### Motor

Godot 4, utilizando GDScript inicialmente.

### Organización conceptual

- **Jugador:** movimiento, cámara e interacción.
- **Mundo:** escenarios, navegación y elementos interactivos.
- **Personajes:** datos, comportamiento, diálogos y horarios.
- **Relaciones:** estado de los vínculos y cambios provocados por acontecimientos.
- **Calendario:** hora, día y eventos programados.
- **Narrativa:** diálogos, elecciones y escenas.
- **Interfaz:** menús, información y estado del juego.
- **Guardado:** persistencia de los datos relevantes de la partida.

La arquitectura definitiva se decidirá después de construir el prototipo. Se evitará diseñar sistemas generales excesivamente complejos antes de conocer las necesidades reales.

El proyecto se gestionará mediante control de versiones, con Git como opción inicial. Se documentarán las decisiones técnicas importantes.

## 9. Alcance del primer prototipo

El primer prototipo no intentará representar el juego completo. Su propósito será comprobar si la idea central resulta divertida y técnicamente realizable.

### Contenido previsto

- Una zona pequeña del patio escolar.
- Un personaje controlable.
- Cámara en tercera persona.
- Uno o dos NPC provisionales.
- Interacción y diálogo.
- Una elección del jugador.
- Una escena breve relacionada con la resonancia.
- Una actividad compartida sencilla.
- Un cambio visible en el estado de una relación.
- Una forma básica de reiniciar la experiencia o guardar el progreso, si resulta conveniente.

### Criterios para considerar el prototipo funcional

- El jugador puede moverse y orientarse con comodidad.
- Puede acercarse a un NPC e iniciar una interacción.
- Los diálogos y las elecciones funcionan de principio a fin.
- La elección provoca un cambio observable.
- La escena narrativa puede reproducirse sin errores bloqueantes.
- El equipo puede modificar personajes y diálogos sin rehacer todo el sistema.

## 10. Fases de desarrollo

**Fase A — Fundamentos:** aprender el editor, las escenas, los nodos, GDScript y el control de versiones.

**Fase B — Movimiento:** crear una zona sencilla, implementar al jugador y configurar la cámara.

**Fase C — Interacción:** añadir NPC, diálogos, elecciones y una primera escena narrativa.

**Fase D — Relaciones:** guardar estados sencillos y reflejar sus cambios en los acontecimientos.

**Fase E — Mundo dinámico:** introducir el reloj, el calendario y horarios básicos.

**Fase F — Episodio de prueba:** integrar las mecánicas en una experiencia corta y evaluable.

**Fase G — Ampliación:** revisar el diseño a partir de las pruebas y decidir qué sistemas y contenidos añadir a continuación.

## 11. Riesgos y medidas de control

### Alcance excesivo

Cien personajes con historias, animaciones, horarios y relaciones diferentes suponen una cantidad considerable de trabajo.

**Medida:** comenzar con uno o dos personajes y construir sistemas reutilizables solo cuando se demuestre que son necesarios.

### Falta de experiencia artística

Crear modelos, rigging, animaciones e interfaces originales puede consumir mucho tiempo.

**Medida:** usar recursos provisionales y mantener la dirección artística final como una tarea gradual.

### Complejidad técnica

La combinación de exploración 3D, cámara, diálogos, calendario y relaciones puede dificultar la depuración.

**Medida:** desarrollar, probar y documentar cada sistema por separado antes de integrarlo.

### Incompatibilidad de recursos externos

Los recursos pueden utilizar licencias diferentes o no compartir un estilo visual coherente.

**Medida:** mantener un inventario de licencias y sustituir progresivamente los recursos que no encajen con la versión final.

## 12. Decisiones pendientes

- Nombre definitivo del juego.
- Identidad, motivaciones y trasfondo del protagonista.
- Explicación definitiva del fenómeno celestial.
- Sistema concreto de relaciones y progresión.
- Estructura narrativa y condiciones de avance.
- Tamaño del mundo y alcance de las zonas.
- Dirección artística final.
- Modelo de publicación y distribución.
- Reparto de responsabilidades entre los dos desarrolladores.

---

**Principio rector:** construir primero una experiencia pequeña que demuestre el atractivo de las relaciones y la exploración. La visión de cien almas gemelas servirá como horizonte creativo, no como requisito para la primera versión.
