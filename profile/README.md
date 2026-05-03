<p align="center">
  <!-- Reemplazar con el logo oficial / Replace with official logo -->
  <img src="../assets/logo.png" alt="coDueño" width="200" />
</p>

<h1 align="center">coDueño</h1>

<p align="center">
  <b>El segundo cerebro inmobiliario de Argentina</b><br/>
  <i>Argentina's AI-powered property management second brain</i>
</p>

<p align="center">
  <img alt="Estado" src="https://img.shields.io/badge/estado-en%20desarrollo-yellow?style=flat-square" />
  <img alt="Plataforma" src="https://img.shields.io/badge/plataforma-Telegram-blue?style=flat-square&logo=telegram" />
  <img alt="IA" src="https://img.shields.io/badge/IA-Gemini-orange?style=flat-square" />
  <img alt="Mercado" src="https://img.shields.io/badge/mercado-Argentina-74ACDF?style=flat-square" />
</p>

---

## 🇦🇷 ¿Qué es coDueño?

**coDueño** es tu segundo cerebro para gestionar alquileres en Argentina. Te asiste a través de Telegram: pegás los mensajes que te llegan de prospectos e inquilinos, y la IA te propone la mejor respuesta, evalúa perfiles y lleva el historial por vos.

La filosofía es **Human-in-the-Loop**: vos siempre escribís y enviás — la IA nunca habla por vos, solo te ayuda a pensar mejor y más rápido.

### ¿Qué podés hacer con coDueño?

|  |  |
|---|---|
| 🧠 **Respuestas sugeridas** | Pegás el mensaje del prospecto y la IA te propone qué responder, con contexto de la propiedad y tus instrucciones |
| 🎯 **Scoring de prospectos** | Evaluación automática del perfil de cada interesado para que sepas con quién vale la pena avanzar |
| 🏠 **Gestión de propiedades** | Registrá activos, publicaciones y tickets de mantenimiento en un solo lugar |
| 💬 **Historial completo** | Cada conversación queda registrada con contexto para que nada se te escape |
| 💳 **Modelo flexible** | Pagá solo por los días que tus propiedades están activas — sin suscripciones fijas |

### ¿Cómo funciona?

```
1. Conectás tu Telegram a coDueño
2. Cargás tus propiedades e instrucciones en lenguaje natural
3. Un prospecto te escribe → vos pegás su mensaje en el bot
4. La IA analiza el contexto y te sugiere la respuesta ideal
5. Vos la revisás, la ajustás si querés, y la enviás vos mismo
```

> 🚧 **En desarrollo activo.** Próximamente disponible para propietarios argentinos.

---

## 🇬🇧 What is coDueño?

**coDueño** is your second brain for managing rentals in Argentina. It assists you through Telegram: paste the messages you receive from prospects and tenants, and the AI suggests the best reply, evaluates profiles, and keeps the full history for you.

The philosophy is **Human-in-the-Loop**: you always write and send — the AI never speaks on your behalf, it just helps you think faster and better.

### What can you do with coDueño?

|  |  |
|---|---|
| 🧠 **Suggested replies** | Paste a prospect's message and the AI proposes what to answer, with full context of the property and your instructions |
| 🎯 **Prospect scoring** | Automatic profile evaluation of every interested party so you know who is worth pursuing |
| 🏠 **Property management** | Register assets, listings, and maintenance tickets in one place |
| 💬 **Full history** | Every conversation is recorded with context so nothing slips through |
| 💳 **Flexible model** | Pay only for the days your properties are active — no fixed subscriptions |

### How does it work?

```
1. You connect your Telegram to coDueño
2. You load your properties and instructions in natural language
3. A prospect messages you → you paste their message into the bot
4. The AI analyzes the context and suggests the ideal reply
5. You review it, adjust if needed, and send it yourself
```

> 🚧 **Actively in development.** Coming soon for Argentine landlords.

---

## 📈 Para inversores · For investors

El mercado de gestión informal de alquileres en Argentina representa una oportunidad sin solución tecnológica consolidada. Los propietarios individuales dedican horas semanales a pensar qué responder, cómo filtrar interesados y llevar el seguimiento — coDueño acelera cada una de esas decisiones sin sacarle el control al dueño.

**Modelo de negocio:**
- SaaS por créditos: 1 crédito = 1 día de actividad por propiedad
- Pago nativo con MercadoPago
- El costo del cliente escala con su uso real, sin fricción de suscripciones

The informal rental management market in Argentina represents an opportunity with no consolidated technological solution. Individual landlords spend hours weekly deciding how to respond, filtering prospects, and tracking follow-ups — coDueño accelerates every one of those decisions without removing the owner's control.

**Business model:**
- Credit-based SaaS: 1 credit = 1 active day per property
- Native MercadoPago payments
- Customer cost scales with actual usage, no subscription friction

Para consultas · For inquiries: **hola@codueño.com.ar**

---

## 🛠️ Para desarrolladores · For developers

### Stack

| Capa · Layer | Tecnología · Technology |
|---|---|
| Backend | Python 3.11+, FastAPI |
| Base de datos · Database | PostgreSQL, SQLAlchemy 2.0 |
| IA · AI | Google Gemini |
| Pagos · Payments | MercadoPago |
| Infraestructura · Infrastructure | Docker, GCP |
| Mensajería · Messaging | Telegram Bot API |

### Arquitectura · Architecture

coDueño está construido como un ecosistema de microservicios con topología de red dual. Solo el núcleo cognitivo tiene acceso directo a la base de datos — los demás componentes son stateless y se comunican exclusivamente a través de APIs internas. Esto garantiza aislamiento de datos y escalabilidad horizontal.

coDueño is built as a microservices ecosystem with a dual-network topology. Only the cognitive core has direct database access — all other components are stateless and communicate exclusively through internal APIs. This ensures data isolation and horizontal scalability.

### Repositorios · Repositories

La mayoría de los repositorios de esta organización son privados. Algunos componentes serán abiertos al público en el futuro.

Most repositories in this organization are private. Some components will be open-sourced in the future.

Interesado en colaborar · Interested in collaborating: **dev@codueño.com.ar**

---

<p align="center">
  Hecho con ❤️ para el mercado argentino &nbsp;·&nbsp; Made with ❤️ for the Argentine market
</p>
