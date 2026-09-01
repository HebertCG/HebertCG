<div align="center">

<h1>🤖⚙️</h1>

<h1>Hola, soy Hebert Cornejo</h1>

<p>
🚀 Automatizador de Procesos &nbsp;|&nbsp; 🌐 Desarrollador Web Freelance &nbsp;|&nbsp; 🇵🇪 Desde Piura, Perú
</p>

<a href="https://www.linkedin.com/in/hebertcornejo/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>
<a href="https://instagram.com/hebert_cg">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">
</a>
<a href="mailto:TU-CORREO@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
</a>

</div>

---

## 🎯 Sobre mí

Me dedico a que la gente deje de copiar y pegar cosas a mano. 🙂

✨ Si un negocio tiene a tres personas transcribiendo pedidos de WhatsApp a un Excel, ahí hay un problema que se resuelve con código — y esa es justo la parte que más me gusta.

🇵🇪 Trabajo como freelance desde Piura con restaurantes, delivery, talleres de autos y consultorios médicos. Nada de proyectos de práctica: todo lo que hay acá está corriendo con clientes de verdad.

🔍 **Actualmente enfocado en:**

- 🤖 Bots de WhatsApp que reservan, cotizan y confirman solos, sin que nadie conteste
- 🔗 Conectar herramientas que no se hablaban entre sí, con n8n y APIs
- 🧠 Meter modelos de IA dentro de los flujos sin que puedan romper nada
- ⚡ Landing pages que cargan rápido de verdad, no solo en la demo

---

## 💻 Tecnologías que uso con frecuencia

### 🤖 Automatización

<p>
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n">
  <img src="https://img.shields.io/badge/WhatsApp_Cloud_API-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp Cloud API">
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI">
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
</p>

### 🌐 Web e infraestructura

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,react,angular,tailwind,html,css,vite,nodejs,postgres,supabase,docker,nginx,vercel,cloudflare,git,github,vscode&perline=9" alt="Stack web">
</p>

---

## 🎮 Misión actual: que ningún negocio siga haciendo a mano lo que puede hacer solo

Cada repo de acá es un negocio real que dejó de perder horas. 🎯

📁 **[Automatizacion_Jagguar](https://github.com/HebertCG/Automatizacion_Jagguar)** · [🔴 demo en vivo](https://automatizacion-jagguar.vercel.app)
Un taller de detailing perdía consultas de madrugada y tardaba 10 mensajes en cerrar una cita. Ahora hay 8 workflows de n8n, un bot de 64 nodos que entiende texto, audio e imágenes, y un panel con CRM, métricas y agenda. Los plantones se acabaron pidiendo 20% de adelanto. 🚗

📁 **[Automatizacion_Guidos](https://github.com/HebertCG/Automatizacion_Guidos)**
Un delivery donde los pedidos solo existían dentro del chat y alguien revisaba los vouchers de Yape a ojo en plena hora pico. Ahora hay una máquina de 7 estados en PostgreSQL, OCR que lee los vouchers, pantalla de cocina en tiempo real y una app aparte para el motorizado. 🛵

📁 **[Automatizacion_Tayanti](https://github.com/HebertCG/Automatizacion_Tayanti)**
Un restaurante que solo tomaba reservas en horario de atención y las copiaba a mano. Ahora un bot atiende 24/7 con memoria de conversación, y el personal ve todo en un panel con KPIs del día. 🍽️

---

## 🌐 Y también hago webs

📁 **[thenorthofoncopathology](https://github.com/HebertCG/thenorthofoncopathology)** · [🔗 en vivo](https://thenorthofoncopathology-coral.vercel.app)
Red de anatomía patológica oncológica con 6 sedes en el Perú. El reto era hablarle a tres públicos a la vez —pacientes, médicos que derivan e instituciones— así que el formulario los separa desde el inicio.
`React 18` `TypeScript` `Vite` `Tailwind` `Playwright`

📁 **[FabioPalacios](https://github.com/HebertCG/FabioPalacios)** · [🔗 en vivo](https://fabiopalacios.cornejogarciahebertjose.workers.dev)
Landing de un cirujano oncólogo en Piura. Toda la página existe para responder una sola pregunta: *"¿tengo que viajar a Lima para operarme?"*.
`Angular 22` `TypeScript` `Prerender` `Cloudflare Workers`

---

## 🧠 Cómo funciona por dentro lo que construyo

Uso la misma arquitectura en los tres proyectos de automatización, y la voy afinando en cada uno:

```mermaid
flowchart LR
  A["Cliente en WhatsApp"] --> B["WhatsApp Cloud API"]
  B --> C["n8n"]
  C --> D["OpenAI: texto, audio, imagen"]
  D --> C
  C --> E[("PostgreSQL: logica en funciones SQL")]
  E --> F["Panel del personal: Realtime + RLS"]
  F --> E
  E --> G["Notificacion automatica al cliente"]
```

💡 **El truco está en dónde vive la lógica:** todas las reglas del negocio están en funciones de PostgreSQL, no en el modelo de IA ni en el navegador. Así el bot puede equivocarse hablando, pero nunca puede romper los datos.

---

## 🤝 ¿Trabajamos juntos?

📌 Primero un **diagnóstico gratis**: reviso tu proceso y te digo con honestidad si vale la pena automatizarlo. A veces la respuesta es que no. 🤷

📌 Después un **prototipo funcionando** antes de que pagues todo.

📌 Y al final una **entrega documentada**, para que puedas seguir sin depender de mí.

---

<div align="center">

⚙️ Automatizando desde **Piura (Perú)** 🇵🇪 para donde haga falta 🌎

✨ *Si lo haces dos veces a mano, probablemente se puede automatizar* ✨

</div>
