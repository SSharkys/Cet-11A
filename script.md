/\* ![](Aspose.Words.a00c62db-f5b0-4d5c-ad6d-1f216f396eb6.001.png)

═══════════════════════════════════════════ ════════

` `ORIENTA — script.js

═══════════════════════════════════════════ ════════ \*/

/\* ══════════════════════════════════════

` `DATA — QUESTIONS

══════════════════════════════════════ \*/ const questions = [

` `{

` `text: "¿Qué actividad disfrutas más en tu 

tiempo libre?",

` `type: "single",

` `options: [

` `{ text: "Armar o reparar cosas con mis 

manos", areas: ["ingenieria", "tecnologia"] 

},

` `{ text: "Leer, escribir o aprender cosas 

nuevas", areas: ["social", "humanidades"] },

` `{ text: "Ayudar a otras personas con sus 

problemas", areas: ["salud", "social"] },

` `{ text: "Crear arte, música o 

diseño", areas: ["arte"] },

` `{ text: "Resolver acertijos o jugar 

videojuegos", areas: ["tecnologia", 

"ciencias"] },

` `{ text: "Organizar eventos o liderar 

grupos", areas: ["negocios", "social"] },

` `]

` `},

` `{

` `text: "¿Cuál de estas asignaturas escolares te 

resulta más interesante?",

` `type: "single",

` `options: [![ref1]

` `{ text: "Matemáticas o Física", areas: 

["ingenieria", "ciencias", "tecnologia"] },

` `{ text: "Biología o Química", areas: 

["salud", "ciencias"] },

` `{ text: "Historia o Filosofía", areas: 

["humanidades", "social"] },

` `{ text: "Lengua y Literatura", areas: 

["humanidades", "arte"] },

` `{ text: "Arte o Música", areas: 

["arte"] },

` `{ text: "Economía o Administración", areas: 

["negocios"] },

` `]

` `},

` `{

` `text: "Imagina que debes trabajar en un 

proyecto. ¿Cuál prefieres?",

` `type: "single",

` `options: [

` `{ text: "Diseñar una app o página 

web", areas: ["tecnologia"] },

` `{ text: "Investigar una enfermedad y sus 

soluciones", areas: ["salud", "ciencias"] },

` `{ text: "Crear una campaña 

publicitaria", areas: ["arte", 

"negocios"] },

` `{ text: "Analizar datos económicos de un 

país", areas: ["negocios", "ciencias"] },

` `{ text: "Escribir un cuento o guión de 

película", areas: ["humanidades", "arte"] },

` `{ text: "Construir un puente o edificio a 

escala", areas: ["ingenieria"] },

` `]

` `},

` `{

` `text: "¿Cómo prefieres trabajar 

habitualmente?",

` `type: "single",

` `options: [

` `{ text: "Solo/a, concentrado/a en mis ![ref1]

ideas", areas: ["tecnologia", 

"arte", "ciencias"] },

` `{ text: "Con personas, escuchando y 

ayudando", areas: ["salud", "social"] 

},

` `{ text: "En equipo, dirigiendo y 

organizando", areas: ["negocios", 

"ingenieria"] },

` `{ text: "Al aire libre o en contacto con la 

naturaleza", areas: ["ciencias", "salud"] },

` `{ text: "Presentando ideas y convenciendo a 

otros", areas: ["negocios", "social"] },

` `]

` `},

` `{

` `text: "¿Cuál de estos logros te haría sentir 

más orgulloso/a?",

` `type: "single",

` `options: [

` `{ text: "Curar a muchos 

pacientes", areas: 

["salud"] },

` `{ text: "Crear la próxima gran aplicación o 

red social", areas: ["tecnologia"] },

` `{ text: "Ganar un premio por una obra 

artística", areas: ["arte"] },

` `{ text: "Fundar tu propia empresa 

exitosa", areas: ["negocios"] },

` `{ text: "Defender derechos de personas 

vulnerables", areas: ["social", 

"humanidades"] },

` `{ text: "Diseñar infraestructura que mejore 

ciudades", areas: ["ingenieria"] },

` `]

` `},

` `{

` `text: "¿Qué tipo de problemas disfrutas 

resolver?",

` `type: "single",

` `options: [![ref1]

` `{ text: "Problemas técnicos o de 

lógica", areas: ["tecnologia", 

"ingenieria"] },

` `{ text: "Problemas relacionados con la salud 

de personas", areas: ["salud"] },

` `{ text: "Conflictos sociales o 

injusticias", areas: ["social", 

"humanidades"] },

` `{ text: "Desafíos creativos o 

estéticos", areas: ["arte"] },

` `{ text: "Retos financieros o de 

gestión", areas: ["negocios"] },

` `{ text: "Preguntas sobre cómo funciona el 

universo", areas: ["ciencias"] },

` `]

` `},

` `{

` `text: "¿Cuántas horas puedes estar frente a una 

pantalla trabajando?",

` `type: "single",

` `options: [

` `{ text: "Me encanta, no me molesta nada",

areas: ["tecnologia", "arte"] },

` `{ text: "Algunas horas, necesito moverme", 

areas: ["salud", "ingenieria"] },

` `{ text: "Prefiero trato con personas",

areas: ["social", "salud"] },

` `{ text: "Trabajo en campo o laboratorio",

areas: ["ciencias", "ingenieria"] },

` `]

` `},

` `{

` `text: "¿Qué valoras más en un trabajo?",

` `type: "multi",

` `hint: "Selecciona todas las que apliquen.",

` `options: [

` `{ text: "Buen salario y estabilidad",

areas: ["negocios", "ingenieria"] },

` `{ text: "Ayudar a la gente directamente",

areas: ["salud", "social"] },![ref1]

` `{ text: "Libertad creativa",

areas: ["arte", "humanidades"] },

` `{ text: "Resolver desafíos intelectuales",

areas: ["ciencias", "tecnologia"] },

` `{ text: "Liderar equipos grandes",

areas: ["negocios"] },

` `{ text: "Horarios flexibles",

areas: ["tecnologia", "arte"] },

` `]

` `},

` `{

` `text: "Si tuvieras que describir tu habilidad 

más fuerte, ¿cuál sería?",

` `type: "single",

` `options: [

` `{ text: "Analizar información y encontrar 

patrones", areas: ["ciencias", "tecnologia"] },

` `{ text: "Comunicarme muy bien con 

otros", areas: ["social", 

"humanidades"] },

` `{ text: "Diseñar o crear cosas 

visualmente", areas: ["arte"] },

` `{ text: "Organizar y gestionar 

recursos", areas: ["negocios"] },

` `{ text: "Aplicar conocimiento 

técnico", areas: ["ingenieria", 

"tecnologia"] },

` `{ text: "Empatizar y apoyar a las 

personas", areas: ["salud", "social"] },

` `]

` `},

` `{

` `text: "¿Qué tipo de contenido consumes más en 

internet?",

` `type: "single",

` `options: [

` `{ text: "Tutoriales de programación o 

tecnología", areas: ["tecnologia"] },

` `{ text: "Videos de ciencia o 

documentales", areas: ["ciencias", ![ref1]

"salud"] },

` `{ text: "Arte, música, diseño o 

moda", areas: ["arte"] },

` `{ text: "Noticias sociales, política o 

cultura", areas: ["social", "humanidades"] },

` `{ text: "Emprendimiento, inversión o 

economía", areas: ["negocios"] },

` `{ text: "Bricolaje, ingeniería y 

construcción", areas: ["ingenieria"] },

` `]

` `},

` `{

` `text: "¿Cuál de estos escenarios te emociona 

más?",

` `type: "single",

` `options: [

` `{ text: "Operar a un paciente y salvarle la 

vida", areas: ["salud"] },

` `{ text: "Lanzar una startup 

tecnológica", areas: ["tecnologia", 

"negocios"] },

` `{ text: "Exponer tu obra en una galería de 

arte", areas: ["arte"] },

` `{ text: "Publicar una investigación 

científica", areas: ["ciencias"] },

` `{ text: "Ganar un caso importante en un 

tribunal", areas: ["humanidades", "social"] },

` `{ text: "Ver una obra de ingeniería que 

diseñaste", areas: ["ingenieria"] },

` `]

` `},

` `{

` `text: "¿Cuántos años estás dispuesto/a a 

estudiar?",

` `type: "single",

` `options: [

` `{ text: "2–3 años (carrera técnica corta)",

areas: ["tecnologia", "arte"] },

` `{ text: "4–5 años (carrera universitaria)",

areas: ["negocios", "ingenieria", "ciencias"] },![ref1]

` `{ text: "6–7 años (carrera larga)",

areas: ["salud", "humanidades"] },

` `{ text: "No me importa si es lo que amo",

areas: ["salud", "ciencias", "social"] },

` `]

` `},

` `{

` `text: "¿Te imaginas trabajando en otro país 

algún día?",

` `type: "single",

` `options: [

` `{ text: "Sí, me encantaría vivir en el 

extranjero", areas: ["negocios", "tecnologia", 

"arte"] },

` `{ text: "Tal vez, pero prefiero mi 

país", areas: ["social", "salud"] 

},

` `{ text: "No, quiero contribuir en mi 

comunidad local", areas: ["social", 

"humanidades"] },

` `{ text: "Dependería del proyecto o 

empresa", areas: ["ingenieria", 

"ciencias"] },

` `]

` `},

` `{

` `text: "Selecciona las habilidades que crees 

tener o querer desarrollar:",

` `type: "multi",

` `hint: "Puedes elegir varias.",

` `options: [

` `{ text: "Programación o lógica 

computacional", areas: ["tecnologia"] },

` `{ text: "Escritura y 

argumentación", areas: ["humanidades", 

"social"] },

` `{ text: "Dibujo, diseño o 

fotografía", areas: ["arte"] },

` `{ text: "Investigación y análisis de 

datos", areas: ["ciencias", "tecnologia"] },![ref1]

` `{ text: "Liderazgo y gestión de 

proyectos", areas: ["negocios", "ingenieria"] 

},

` `{ text: "Atención y cuidado de 

personas", areas: ["salud", "social"] },

` `]

` `},

` `{

` `text: "¿Qué materia escolar se te da mejor sin 

esfuerzo?",

` `type: "single",

` `options: [

` `{ text: "Matemáticas", areas: 

["ingenieria", "ciencias", "tecnologia"] },

` `{ text: "Ciencias naturales", areas: 

["salud", "ciencias"] },

` `{ text: "Ciencias sociales", areas: 

["social", "humanidades"] },

` `{ text: "Arte o música", areas: 

["arte"] },

` `{ text: "Idiomas", areas: 

["humanidades", "negocios"] },

` `{ text: "Educación física", areas: 

["salud"] },

` `]

` `},

` `{

` `text: "Cuando hay un problema en tu grupo, tú 

sueles...",

` `type: "single",

` `options: [

` `{ text: "Tomar el control y organizar a 

todos", areas: ["negocios", "ingenieria"] 

},

` `{ text: "Escuchar a cada uno y 

mediar", areas: ["social", 

"salud"] },

` `{ text: "Proponer ideas creativas para 

resolverlo", areas: ["arte", "humanidades"] },

` `{ text: "Analizar la situación y buscar la ![ref1]

solución", areas: ["ciencias", "tecnologia"] },

` `{ text: "Apoyar emocionalmente a quien más lo 

necesita", areas: ["salud", "social"] },

` `]

` `},

` `{

` `text: "¿Cuál de estas carreras llamó tu 

atención antes de este test?",

` `type: "single",

` `options: [

` `{ text: "Medicina o 

Enfermería", areas: ["salud"] },

` `{ text: "Ingeniería o 

Arquitectura", areas: ["ingenieria"] },

` `{ text: "Diseño, Cine o Bellas 

Artes", areas: ["arte"] },

` `{ text: "Derecho o Ciencias 

Políticas", areas: ["humanidades", "social"] 

},

` `{ text: "Administración o 

Economía", areas: ["negocios"] },

` `{ text: "Computación o Ciencia de 

Datos", areas: ["tecnologia", "ciencias"] },

` `]

` `},

` `{

` `text: "¿En qué tipo de empresa o institución te 

ves trabajando?",

` `type: "single",

` `options: [

` `{ text: "Hospital o 

clínica", areas: ["salud"] },

` `{ text: "Empresa tecnológica o 

startup", areas: ["tecnologia", "negocios"] 

},

` `{ text: "Estudio creativo, cine o 

publicidad", areas: ["arte"] },

` `{ text: "Institución pública o 

ONG", areas: ["social", "humanidades"] 

},![ref1]

` `{ text: "Empresa constructora o 

ingenieril", areas: ["ingenieria"] },

` `{ text: "Laboratorio o centro de 

investigación", areas: ["ciencias"] },

` `]

` `},

` `{

` `text: "¿Cómo reaccionas cuando tienes que 

hablar en público?",

` `type: "single",

` `options: [

` `{ text: "Me encanta, disfruto mucho",

areas: ["social", "negocios", "humanidades"] },

` `{ text: "Lo hago bien aunque me pone 

nervioso", areas: ["negocios", "ingenieria"] },

` `{ text: "Prefiero expresarme de otra 

manera", areas: ["arte", "ciencias"] },

` `{ text: "Me incomoda pero lo hago cuando 

debo", areas: ["tecnologia", "salud"] },

` `]

` `},

` `{

` `text: "¿Qué papel juegas mejor en un equipo de 

trabajo?",

` `type: "single",

` `options: [

` `{ text: "El/la experto/a técnico/a que 

resuelve todo", areas: ["tecnologia", 

"ingenieria"] },

` `{ text: "El/la líder que organiza y toma 

decisiones", areas: ["negocios"] },

` `{ text: "El/la creativo/a que propone ideas 

originales", areas: ["arte", "humanidades"] },

` `{ text: "El/la que cuida el bienestar del 

equipo", areas: ["salud", "social"] },

` `{ text: "El/la investigador/a que aporta 

datos", areas: ["ciencias"] },

` `]

` `},

];

/\* ══════════════════════════════════════![ref1]

` `DATA — CAREERS

══════════════════════════════════════ \*/ const careersData = [

` `{

` `id: "medicina",

` `name: "Medicina",

` `area: "salud",

` `icon: "🩺",

` `shortDesc: "Diagnostica y trata enfermedades 

para preservar la salud humana.",

` `description: "La Medicina es la ciencia y arte 

de diagnosticar, tratar y prevenir enfermedades. 

Los médicos trabajan en hospitales, clínicas, 

investigación y salud pública, dedicando sus 

carreras a mejorar la calidad de vida de las personas.",

` `duration: "6–7 años + especialización",\
` `skills: ["Empatía", "Pensamiento crítico", 

"Comunicación", "Biología avanzada", "Resistencia 

emocional"],

` `subjects: ["Anatomía", "Fisiología", 

"Farmacología", "Patología", "Pediatría", 

"Cirugía"],

` `jobs: ["Médico general", "Cirujano/a", 

"Pediatra", "Psiquiatra", "Investigador/a médico", 

"Médico de urgencias"],

` `},

` `{

` `id: "ingenieria-software",

` `name: "Ingeniería de Software",

` `area: "tecnologia",

` `icon: "💻",

` `shortDesc: "Diseña y desarrolla aplicaciones y 

sistemas informáticos.",

` `description: "La Ingeniería de Software combina 

la creatividad y la lógica para construir desde 

aplicaciones móviles hasta sistemas que mueven la 


economía global. Es una de las carreras con mayor ![ref1]

demanda y versatilidad del siglo XXI.",

` `duration: "4–5 años",

` `skills: ["Lógica", "Programación", "Resolución 

de problemas", "Trabajo en equipo", "Aprendizaje 

continuo"],

` `subjects: ["Algoritmos", "Bases de datos", 

"Desarrollo web", "Inteligencia artificial", 

"Ciberseguridad"],

` `jobs: ["Desarrollador/a web", "Ingeniero/a de 

datos", "Arquitecto/a de software", "DevOps", 

"Analista de sistemas"],

` `},

` `{

` `id: "psicologia",

` `name: "Psicología",

` `area: "salud",

` `icon: "🧠",

` `shortDesc: "Estudia el comportamiento humano y 

promueve el bienestar mental.",

` `description: "La Psicología explora la mente y 

la conducta humana. Los psicólogos trabajan en 

salud mental, organizaciones, educación y deporte, 

ayudando a las personas a entenderse y superar sus desafíos.",

` `duration: "5 años",

` `skills: ["Empatía", "Escucha activa", 

"Análisis", "Paciencia", "Comunicación"],

` `subjects: ["Psicología clínica", 

"Neurociencias", "Estadística", "Psicología 

organizacional", "Psicología del desarrollo"],

` `jobs: ["Psicólogo/a clínico", "Terapeuta", 

"Coach ejecutivo", "Psicólogo/a educativo", 

"Investigador/a"],

` `},

` `{

` `id: "diseño-grafico",

` `name: "Diseño Gráfico",

` `area: "arte",

` `icon: "🎨",

` `shortDesc: "Comunica ideas y mensajes a través ![ref1]

de elementos visuales.",

` `description: "El Diseño Gráfico fusiona arte y 

tecnología para crear comunicación visual efectiva. 

Desde logos y branding hasta interfaces digitales y 

animación, los diseñadores dan vida a las ideas de 

personas y marcas.",

` `duration: "4 años",

` `skills: ["Creatividad", "Manejo de software", 

"Estética", "Pensamiento conceptual", "Atención al 

detalle"],

` `subjects: ["Tipografía", "Diseño editorial", 

"Ilustración digital", "UX/UI", "Fotografía", 

"Color y composición"],

` `jobs: ["Diseñador/a de marca", "Director/a de 

arte", "Diseñador/a UX/UI", "Ilustrador/a", "Motion designer"],

` `},

` `{

` `id: "derecho",

` `name: "Derecho",

` `area: "social",

` `icon: "⚖",

` `shortDesc: "Interpreta y aplica las leyes para 

defender derechos y resolver conflictos.",

` `description: "El Derecho es la ciencia que 

estudia el conjunto de normas que rigen la 

convivencia en sociedad. Los abogados defienden 

derechos, resuelven conflictos y trabajan en 

justicia, empresa, política y derechos humanos.",

` `duration: "5–6 años",

` `skills: ["Argumentación", "Lectura crítica", 

"Lógica jurídica", "Comunicación oral", "Ética"],

` `subjects: ["Derecho constitucional", "Derecho 

civil", "Derecho penal", "Derecho internacional", "Procesal"],

` `jobs: ["Abogado/a litigante", "Asesor/a legal", 

"Juez/a", "Diplomático/a", "Notario/a"],

` `},

` `{

` `id: "administracion",![ref1]

` `name: "Administración de Empresas",

` `area: "negocios",

` `icon: "📊",

` `shortDesc: "Planifica, organiza y dirige los 

recursos de una organización.",

` `description: "La Administración de Empresas 

forma profesionales capaces de gestionar 

organizaciones de todo tipo, desde startups hasta 

multinacionales, con visión estratégica, liderazgo 

y conocimiento financiero.",

` `duration: "4–5 años",

` `skills: ["Liderazgo", "Finanzas", 

"Negociación", "Toma de decisiones", "Gestión de personas"],

` `subjects: ["Contabilidad", "Marketing", 

"Finanzas corporativas", "Estrategia", "Recursos 

humanos"],

` `jobs: ["Gerente general", "Consultor/a de 

negocios", "Emprendedor/a", "Director/a 

financiero", "Analista de mercado"],

` `},

` `{

` `id: "biologia",

` `name: "Biología",

` `area: "ciencias",

` `icon: "🔬",

` `shortDesc: "Estudia los seres vivos y los 

procesos naturales del planeta.",

` `description: "La Biología abarca desde la 

genética molecular hasta los ecosistemas. Sus 

egresados trabajan en investigación, conservación 

ambiental, biotecnología, farmacéuticas y 

educación.",

` `duration: "5 años",

` `skills: ["Investigación", "Análisis", "Rigor 

científico", "Trabajo en laboratorio", 

"Observación"],

` `subjects: ["Genética", "Ecología", 

"Bioquímica", "Microbiología", "Evolución", 

"Botánica"],![ref1]

` `jobs: ["Investigador/a científico", "Biólogo/a 

marino", "Biotecnólogo/a", "Conservacionista", 

"Docente universitario"],

` `},

` `{

` `id: "arquitectura",

` `name: "Arquitectura",

` `area: "ingenieria",

` `icon: "🏛",

` `shortDesc: "Diseña y construye espacios que 

mejoran la vida de las personas.",

` `description: "La Arquitectura combina arte, 

ciencia e ingeniería para crear espacios 

funcionales y estéticos. Los arquitectos trabajan 

en diseño residencial, urbanismo, patrimonio y 

diseño sostenible.",

` `duration: "5–6 años",

` `skills: ["Creatividad", "Geometría espacial", 

"Cálculo", "Software CAD", "Comunicación visual"],

` `subjects: ["Diseño arquitectónico", "Historia 

del arte", "Estructuras", "Urbanismo", 

"Sustentabilidad"],

` `jobs: ["Arquitecto/a de proyectos", 

"Urbanista", "Diseñador/a de interiores", 

"Restaurador/a de patrimonio", "Investigador/a"],

` `},

` `{

` `id: "ciencias-politicas",

` `name: "Ciencias Políticas",

` `area: "social",

` `icon: "🌍",

` `shortDesc: "Analiza el poder, los sistemas 

políticos y las relaciones internacionales.",

` `description: "Las Ciencias Políticas forman 

expertos en el análisis del poder, la democracia, 

las políticas públicas y las relaciones 

internacionales, fundamentales para la sociedad 

moderna.",

` `duration: "4–5 años",

` `skills: ["Análisis crítico", "Escritura", ![ref1]

"Negociación", "Pensamiento global", 

"Comunicación"],

` `subjects: ["Teoría política", "Relaciones 

internacionales", "Derecho constitucional", 

"Políticas públicas", "Economía"],

` `jobs: ["Analista político", "Diplomático/a", "Asesor/a gubernamental", "Periodista político", "Consultor/a internacional"],

` `},

` `{

` `id: "comunicacion",

` `name: "Comunicación y Periodismo",

` `area: "humanidades",

` `icon: "📰",

` `shortDesc: "Informa, crea contenido y da voz a 

historias que importan.",

` `description: "La Comunicación y el Periodismo 

forman profesionales capaces de narrar, informar y 

generar contenido en múltiples formatos: prensa, 

televisión, radio, podcast y medios digitales.",

` `duration: "4–5 años",

` `skills: ["Escritura", "Investigación 

periodística", "Redes sociales", "Edición de 

video", "Creatividad"],

` `subjects: ["Periodismo digital", "Comunicación 

corporativa", "Redacción", "Marketing de 

contenidos", "Fotografía"],

` `jobs: ["Periodista", "Comunicador/a 

corporativo", "Community manager", "Locutor/a", 

"Productor/a de contenido"],

` `},

` `{

` `id: "ingenieria-civil",

` `name: "Ingeniería Civil",

` `area: "ingenieria",

` `icon: "🏗",

` `shortDesc: "Diseña y construye la 

infraestructura que mueve al mundo.",

` `description: "La Ingeniería Civil transforma la 

sociedad construyendo puentes, carreteras, ![ref1]

edificios, represas y sistemas de agua. Es una de 

las disciplinas más antiguas y con más impacto en 

el desarrollo humano.",

` `duration: "5 años",

` `skills: ["Matemáticas", "Física aplicada", 

"Gestión de proyectos", "Software BIM", 

"Liderazgo"],

` `subjects: ["Mecánica de materiales", 

"Hidráulica", "Geotecnia", "Cálculo estructural", 

"Topografía"],

` `jobs: ["Ingeniero/a estructural", "Director/a 

de obras", "Consultor/a vial", "Inspector/a de 

proyectos", "Docente"],

` `},

` `{

` `id: "gastronomia",

` `name: "Gastronomía",

` `area: "arte",

` `icon: "󰞽",

` `shortDesc: "Crea experiencias culinarias 

combinando tradición, arte y técnica.",

` `description: "La Gastronomía va mucho más allá 

de cocinar: es una carrera sobre cultura, 

creatividad, nutrición y emprendimiento. Los chefs 

trabajan en restaurantes, televisión, consultoría 

gastronómica y emprendimientos propios.",

` `duration: "3–4 años",

` `skills: ["Creatividad", "Precisión", "Trabajo 

bajo presión", "Gestión de costos", "Liderazgo de cocina"],

` `subjects: ["Técnicas culinarias", "Pastelería", 

"Nutrición", "Gestión de restaurantes", "Historia 

de la cocina"],

` `jobs: ["Chef ejecutivo/a", "Pastelero/a", "Food 

stylist", "Consultor/a gastronómico", 

"Emprendedor/a foodie"],

` `},

];

/\* ══════════════════════════════════════![ref1]

` `DATA — UNIVERSITIES

══════════════════════════════════════ \*/

const universitiesData = [

` `{

` `name: "Universidad de Buenos Aires (UBA)",

` `country: "Argentina",

` `city: "Buenos Aires",

` `emoji: "🇦🇷",

` `careers: ["Medicina", "Derecho", "Ingeniería", 

"Psicología", "Ciencias Exactas"],

` `url: "https://www.uba.ar",

` `},

` `{

` `name: "Universidad Nacional Autónoma de México 

(UNAM)",

` `country: "México",

` `city: "Ciudad de México",

` `emoji: "🇲🇽",

` `careers: ["Medicina", "Derecho", 

"Arquitectura", "Comunicación", "Ingeniería"],

` `url: "https://www.unam.mx",

` `},

` `{

` `name: "Pontificia Universidad Católica de Chile 

(PUC)",

` `country: "Chile",

` `city: "Santiago",

` `emoji: "🇨🇱",

` `careers: ["Medicina", "Ingeniería", "Diseño", 

"Administración", "Biología"],

` `url: "https://www.uc.cl",

` `},

` `{

` `name: "Universidad de los Andes",

` `country: "Colombia",

` `city: "Bogotá",

` `emoji: "🇨🇴",

` `careers: ["Administración", "Ingeniería", 

"Economía", "Derecho", "Artes"],

` `url: "https://www.uniandes.edu.co",![ref1]

` `},

` `{

` `name: "Universidad de São Paulo (USP)",

` `country: "Brasil",

` `city: "São Paulo",

` `emoji: "🇧🇷",

` `careers: ["Medicina", "Ingeniería", "Derecho", 

"Biología", "Arquitectura"],

` `url: "https://www.usp.br",

` `},

` `{

` `name: "Tecnológico de Monterrey (TEC)",

` `country: "México",

` `city: "Monterrey",

` `emoji: "🇲🇽",

` `careers: ["Ingeniería de Software", "Negocios", 

"Diseño", "Biotecnología", "Medicina"],

` `url: "https://www.tec.mx",

` `},

` `{

` `name: "Universidad Católica de Lima (PUCP)",

` `country: "Perú",

` `city: "Lima",

` `emoji: "🇵🇪",

` `careers: ["Derecho", "Comunicaciones", 

"Ingeniería Civil", "Administración", 

"Psicología"],

` `url: "https://www.pucp.edu.pe",

` `},

` `{

` `name: "Universidad Central de Venezuela (UCV)",

` `country: "Venezuela",

` `city: "Caracas",

` `emoji: "🇻🇪",

` `careers: ["Medicina", "Arquitectura", 

"Derecho", "Ciencias", "Economía"],

` `url: "https://www.ucv.ve",

` `},

` `{

` `name: "Universidad de Chile",![ref1]

` `country: "Chile",

` `city: "Santiago",

` `emoji: "🇨🇱",

` `careers: ["Medicina", "Ingeniería", "Derecho", 

"Arte", "Ciencias Sociales"],

` `url: "https://www.uchile.cl",

` `},

` `{

` `name: "Universidad ORT Uruguay",

` `country: "Uruguay",

` `city: "Montevideo",

` `emoji: "🇺🇾",

` `careers: ["Diseño Industrial", "Tecnología", 

"Gastronomía", "Comunicación", "Negocios"],

` `url: "https://www.ort.edu.uy",

` `},

` `{

` `name: "Universidad Javeriana",

` `country: "Colombia",

` `city: "Bogotá",

` `emoji: "🇨🇴",

` `careers: ["Medicina", "Psicología", 

"Comunicación", "Arquitectura", "Ingeniería"],

` `url: "https://www.javeriana.edu.co",

` `},

` `{

` `name: "ITBA — Instituto Tecnológico de Buenos 

Aires",

` `country: "Argentina",

` `city: "Buenos Aires",

` `emoji: "🇦🇷",

` `careers: ["Ingeniería Informática", "Ingeniería 

Industrial", "Bioingeniería", "Ciencia de Datos"],

` `url: "https://www.itba.edu.ar",

` `},

];

/\* ══════════════════════════════════════

` `AREA COLORS & LABELS

══════════════════════════════════════ \*/![ref1]

const areaConfig = {

` `salud: { label: "Salud",

color: "#679C7D", bg: "#E5F0EB" },

` `tecnologia: { label: "Tecnología",

color: "#78628A", bg: "#F0EBF6" },

` `arte: { label: "Arte & Diseño",

color: "#D6B98D", bg: "#FBF5ED" },

` `ciencias: { label: "Ciencias",

color: "#4E7A63", bg: "#E5F0EB" },

` `social: { label: "Ciencias Sociales", 

color: "#5C4A6E", bg: "#F0EBF6" },

` `humanidades: { label: "Humanidades",

color: "#B8946A", bg: "#FBF5ED" },

` `negocios: { label: "Negocios",

color: "#A8CBBA", bg: "#E5F0EB" },

` `ingenieria: { label: "Ingeniería",

color: "#78628A", bg: "#F0EBF6" },

};

/\* ══════════════════════════════════════

` `STATE

══════════════════════════════════════ \*/ let currentQ = 0;

let answers = {}; // { questionIndex: 

[optionIndex, ...] }

let testMode = "single";

/\* ══════════════════════════════════════

` `NAVBAR

══════════════════════════════════════ \*/

const navbar = 

document.getElementById("navbar");

const hamburger = 

document.getElementById("hamburger");

const navLinks = document.getElementById("nav-

links");

window.addEventListener("scroll", () => {

` `navbar.classList.toggle("scrolled", 

window.scrollY > 20);![ref1]

});

hamburger.addEventListener("click", () => {

` `navLinks.classList.toggle("open");

});

// close nav on link click (mobile)

navLinks.querySelectorAll("a").forEach(a => {

` `a.addEventListener("click", () => 

navLinks.classList.remove("open")); });

/\* ══════════════════════════════════════

` `TEST LOGIC

══════════════════════════════════════ \*/

const testLanding = 

document.getElementById("test-landing");

const testQuestions = 

document.getElementById("test-questions");

const testResults = 

document.getElementById("test-results");

const startBtn = 

document.getElementById("start-test-btn");

const prevBtn = 

document.getElementById("prev-btn");

const nextBtn = 

document.getElementById("next-btn");

const progressBar = 

document.getElementById("progress-bar");

const progressLabel = 

document.getElementById("progress-label");

const questionText = 

document.getElementById("question-text");

const optionsContainer = 

document.getElementById("options-container");

const retakeBtn = 

document.getElementById("retake-btn");

function showPanel(panel) {

` `[testLanding, testQuestions, ![ref1]

testResults].forEach(p => 

p.classList.remove("active"));

` `panel.classList.add("active");

}

startBtn.addEventListener("click", () => {

` `currentQ = 0;

` `answers = {};

` `showPanel(testQuestions);

` `renderQuestion();

});

retakeBtn.addEventListener("click", () => {

` `showPanel(testLanding);

});

function renderQuestion() {

` `const q = questions[currentQ];

` `testMode = q.type;

` `// progress

` `const pct = ((currentQ) / questions.length) \* 

100;

` `progressBar.style.width = Math.max(5, pct) + "%";

` `progressLabel.textContent = `Pregunta ${currentQ 

\+ 1} de ${questions.length}`;

` `questionText.textContent = q.text;

` `// hint

` `let hint = 

optionsContainer.parentElement.querySelector(".mult

i-hint");

` `if (hint) hint.remove();

` `if (q.type === "multi") {

` `const h = document.createElement("p");

` `h.className = "multi-hint";

` `h.textContent = q.hint || "Puedes seleccionar 

varias opciones.";

optionsContainer.insertAdjacentElement("beforebegin![ref1]

", h);

` `}

` `optionsContainer.innerHTML = "";

` `const selected = answers[currentQ] || [];

` `q.options.forEach((opt, i) => {

` `const btn = document.createElement("button");\
` `btn.className = "option-btn" + 

(selected.includes(i) ? " selected" : "");

` `btn.textContent = opt.text;

` `btn.addEventListener("click", () => 

selectOption(i, btn));

` `optionsContainer.appendChild(btn);

` `});

` `prevBtn.disabled = currentQ === 0;

` `updateNextBtn();

` `optionsContainer.classList.add("fade-in");\
` `setTimeout(() => 

optionsContainer.classList.remove("fade-in"), 600);

}

function selectOption(index, btn) {

` `if (!answers[currentQ]) answers[currentQ] = [];

` `if (testMode === "single") {

` `answers[currentQ] = [index];

` `document.querySelectorAll(".option-

btn").forEach(b => b.classList.remove("selected"));

` `btn.classList.add("selected");

` `} else {

` `const pos = answers[currentQ].indexOf(index);

` `if (pos === -1) {

` `answers[currentQ].push(index);

` `btn.classList.add("selected");

` `} else {

` `answers[currentQ].splice(pos, 1);

` `btn.classList.remove("selected");![ref1]

` `}

` `}

` `updateNextBtn();

}

function updateNextBtn() {

` `const hasAnswer = answers[currentQ] && 

answers[currentQ].length > 0;

` `nextBtn.disabled = !hasAnswer;

` `nextBtn.textContent = currentQ === 

questions.length - 1 ? "Ver resultados ✓" : "Siguiente →";

}

prevBtn.addEventListener("click", () => {

` `if (currentQ > 0) { currentQ--; renderQuestion(); 

}

});

nextBtn.addEventListener("click", () => {

` `if (currentQ < questions.length - 1) {

` `currentQ++;

` `renderQuestion();

` `} else {

` `computeResults();

` `}

});

/\* ══════════════════════════════════════

` `COMPUTE RESULTS

══════════════════════════════════════ \*/

function computeResults() {

` `const scores = {};

` `Object.keys(areaConfig).forEach(a => scores[a] = 

0);

` `questions.forEach((q, qi) => {

` `const selected = answers[qi] || [];

` `selected.forEach(oi => {

` `q.options[oi].areas.forEach(area => {![ref1]

` `scores[area] = (scores[area] || 0) + 1;

` `});

` `});

` `});

` `// sort areas by score

` `const sorted = Object.entries(scores)

.sort((a, b) => b[1] - a[1])

.filter(([, v]) => v > 0);

` `const max = sorted[0]?.[1] || 1;

` `const topAreas = sorted.slice(0, 5);

` `// headline

` `const topArea = sorted[0]?.[0];\
` `const topLabel = topArea ? 

areaConfig[topArea]?.label : "Explorador/a";

` `document.getElementById("results-

headline").textContent =

` ``Tu perfil apunta a ${topLabel}`;

` `// bars

` `const barsEl = document.getElementById("affinity-

bars");

` `barsEl.innerHTML = "";

` `topAreas.forEach(([area, score]) => {

` `const cfg = areaConfig[area] || { label: area, 

color: "#679C7D", bg: "#E5F0EB" };

` `const pct = Math.round((score / max) \* 100);

` `const item = document.createElement("div");

` `item.className = "affinity-item";

` `item.innerHTML = `

` `<span class="affinity-label">${cfg.label}

</span>

` `<div class="affinity-track">

` `<div class="affinity-fill" data-

pct="${pct}" 

style="background:${cfg.color};width:0%"></div>

` `</div>

` `<span class="affinity-score">${pct}%</span>![ref1]

` ``;

` `barsEl.appendChild(item);

` `});

` `// animate bars

` `setTimeout(() => {

` `document.querySelectorAll(".affinity-

fill").forEach(el => {

` `el.style.width = el.dataset.pct + "%";

` `});

` `}, 100);

` `// recommended careers

` `const topAreaNames = sorted.slice(0, 3).map(([a]) 

=> a);

` `const recommended = careersData

.filter(c => topAreaNames.includes(c.area))

.slice(0, 6);

` `const resultsEl = 

document.getElementById("results-careers");

` `resultsEl.innerHTML = "";

` `recommended.forEach((career, i) => {

` `const pct = Math.round(((scores[career.area] 

|| 0) / max) \* 100);

` `const card = document.createElement("div");\
` `card.className = "result-career-card fade-in";\
` `card.style.animationDelay = i \* 0.08 + "s";\
` `card.innerHTML = `

` `<div class="result-match">${pct}% 

compatibilidad</div>

` `<h4>${career.icon} ${career.name}</h4>

` `<p>${career.shortDesc}</p>

` ``;

` `card.addEventListener("click", () => 

openCareerModal(career));

` `resultsEl.appendChild(card);

` `});

` `showPanel(testResults);

` `// scroll to results![ref1]

` `setTimeout(() => {

` `document.getElementById("test-

section").scrollIntoView({ behavior: "smooth" });

` `}, 100);

}

/\* ══════════════════════════════════════

` `CAREER MODAL

══════════════════════════════════════ \*/

const modal = 

document.getElementById("career-modal");

const modalClose = document.getElementById("modal-

close");

const modalContent= document.getElementById("modal-

content");

function openCareerModal(career) {

` `const cfg = areaConfig[career.area] || {};

` `modalContent.innerHTML = `

` `<div class="modal-icon">${career.icon}</div>\
` `<span class="modal-area-tag" 

style="background:${cfg.bg};color:${cfg.color}">${c

fg.label || career.area}</span>

` `<h2>${career.name}</h2>

` `<p>${career.description}</p>

` `<div class="modal-grid">

` `<div class="modal-info-box">

` `<h4>Duración</h4>

` `<p>${career.duration}</p>

` `</div>

` `<div class="modal-info-box">

` `<h4>Habilidades clave</h4>

` `<div class="modal-tags">

` `${career.skills.map(s => `<span 

class="modal-tag">${s}</span>`).join("")}

` `</div>

` `</div>

` `<div class="modal-info-box">

` `<h4>Materias principales</h4>

` `<div class="modal-tags">![ref1]

` `${career.subjects.map(s => `<span 

class="modal-tag modal-tag-purple">${s}

</span>`).join("")}

` `</div>

` `</div>

` `<div class="modal-info-box">

` `<h4>Salidas laborales</h4>

` `<div class="modal-tags">

` `${career.jobs.map(j => `<span 

class="modal-tag">${j}</span>`).join("")}

` `</div>

` `</div>

` `</div>

` ``;

` `modal.classList.add("open");

` `document.body.style.overflow = "hidden";

}

modalClose.addEventListener("click", closeModal);

modal.addEventListener("click", e => { if (e.target 

=== modal) closeModal(); });

document.addEventListener("keydown", e => { if 

(e.key === "Escape") closeModal(); });

function closeModal() {

` `modal.classList.remove("open");

` `document.body.style.overflow = "";

}

/\* ══════════════════════════════════════

` `CAREERS GRID

══════════════════════════════════════ \*/

const careersGrid = 

document.getElementById("careers-grid");

const filterBar = 

document.getElementById("filter-bar");

function renderCareers(filter = "all") {

` `careersGrid.innerHTML = "";

` `const list = filter === "all"![ref1]

? careersData

: careersData.filter(c => c.area === filter || 

areaConfig[c.area]?.label.toLowerCase().replace("& 

","").includes(filter));

` `list.forEach((career, i) => {

` `const cfg = areaConfig[career.area] || {};

` `const card = document.createElement("div");

` `card.className = "career-card fade-in";  card.style.animationDelay = (i \* 0.06) + "s";

` `card.innerHTML = `

` `<div class="career-card-icon">${career.icon}

</div>

` `<div class="career-area">${cfg.label || 

career.area}</div>

` `<h3>${career.name}</h3>

` `<p>${career.shortDesc}</p>

` `<div class="career-card-footer">

` `<span class="career-

duration">${career.duration}</span>

` `<span class="career-more">Ver más →</span>

` `</div>

` ``;

` `card.addEventListener("click", () => 

openCareerModal(career));

` `careersGrid.appendChild(card);

` `});

}

filterBar.addEventListener("click", e => {

` `const btn = e.target.closest(".filter-btn");

` `if (!btn) return;

` `filterBar.querySelectorAll(".filter-

btn").forEach(b => b.classList.remove("active"));

` `btn.classList.add("active");

` `renderCareers(btn.dataset.filter);

});

renderCareers();

/\* ══════════════════════════════════════![ref1]

` `UNIVERSITIES GRID

══════════════════════════════════════ \*/

const universitiesGrid = 

document.getElementById("universities-grid");

const uniSearch = 

document.getElementById("uni-search");

function renderUniversities(query = "") {

` `const q = query.toLowerCase();

` `universitiesGrid.innerHTML = "";

` `const list = universitiesData.filter(u =>

` `!q ||

` `u.name.toLowerCase().includes(q) ||\
` `u.country.toLowerCase().includes(q) ||\
` `u.city.toLowerCase().includes(q) ||\
` `u.careers.some(c => 

c.toLowerCase().includes(q))

` `);

` `if (list.length === 0) {

` `universitiesGrid.innerHTML = `<p 

style="color:var(--ink-muted);grid-column:1/-1">No 

se encontraron resultados para "${query}".</p>`;

` `return;

` `}

` `list.forEach((uni, i) => {

` `const card = document.createElement("div");

` `card.className = "uni-card fade-in";

` `card.style.animationDelay = (i \* 0.07) + "s";

` `card.innerHTML = `

` `<div class="uni-card-header">

` `<span class="uni-emoji">${uni.emoji}</span>\
` `<span class="uni-country-

tag">${uni.country}</span>

` `</div>

` `<h3>${uni.name}</h3>

` `<div class="uni-location">📍 ${uni.city}, 

${uni.country}</div>![ref1]

` `<div class="uni-careers">

` `${uni.careers.map(c => `<span class="uni-

career-tag">${c}</span>`).join("")}

` `</div>

` `<a href="${uni.url}" target="\_blank" 

rel="noopener noreferrer" class="uni-link">

` `Visitar sitio oficial

` `<svg xmlns="http://www.w3.org/2000/svg" 

viewBox="0 0 24 24" fill="none" 

stroke="currentColor" stroke-width="2" stroke-

linecap="round" stroke-linejoin="round">

` `<path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/>

` `</svg>

` `</a>

` ``;

` `universitiesGrid.appendChild(card);

` `});

}

uniSearch.addEventListener("input", e => 

renderUniversities(e.target.value));

renderUniversities();

/\* ══════════════════════════════════════

` `INTERSECTION OBSERVER — fade-in on scroll

══════════════════════════════════════ \*/

const observer = new IntersectionObserver(entries 

=> {

` `entries.forEach(entry => {

` `if (entry.isIntersecting) {

` `entry.target.style.opacity = "1";\
` `entry.target.style.transform = 

"translateY(0)";

` `}

` `});

}, { threshold: 0.08 });

document.querySelectorAll(".step-card").forEach(el ![](Aspose.Words.a00c62db-f5b0-4d5c-ad6d-1f216f396eb6.003.png)

=> {

` `el.style.opacity = "0";

` `el.style.transform = "translateY(20px)";\
` `el.style.transition = "opacity .5s ease, 

transform .5s ease";

` `observer.observe(el);

});

[ref1]: Aspose.Words.a00c62db-f5b0-4d5c-ad6d-1f216f396eb6.002.png
