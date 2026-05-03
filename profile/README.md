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

**coDueño** es un asistente inteligente para propietarios que gestionan alquileres en Argentina. Conectá tu Telegram, cargá tus propiedades e instrucciones, y dejá que la IA se encargue de las conversaciones con prospectos e inquilinos — en tu nombre, a cualquier hora.

La filosofía es **Human-in-the-Loop**: la IA actúa, pero vos siempre tenés la última palabra.

### ¿Qué podés hacer con coDueño?

|  |  |
|---|---|
| 🤖 **Atención automática** | La IA responde consultas de prospectos 24/7 siguiendo tus instrucciones |
| 🎯 **Scoring de prospectos** | Evaluación automática del perfil de cada interesado antes de que inviertas tu tiempo |
| 🏠 **Gestión de propiedades** | Registrá activos, publicaciones y tickets de mantenimiento en un solo lugar |
| 💬 **Historial completo** | Cada conversación queda registrada con contexto para que nada se te escape |
| 💳 **Modelo flexible** | Pagá solo por los días que tus propiedades están activas — sin suscripciones fijas |

### ¿Cómo funciona?

```
1. Conectás tu Telegram a coDueño
2. Cargás tus propiedades e instrucciones en lenguaje natural
3. Un prospecto te escribe → la IA responde, filtra y registra
4. Vos recibís un resumen y decidís el próximo paso
```

> 🚧 **En desarrollo activo.** Próximamente disponible para propietarios argentinos.

---

## 🇬🇧 What is coDueño?

**coDueño** is an intelligent assistant for landlords managing rentals in Argentina. Connect your Telegram account, load your properties and instructions, and let the AI handle conversations with prospects and tenants — on your behalf, at any hour.

The philosophy is **Human-in-the-Loop**: the AI acts, but you always have the final say.

### What can you do with coDueño?

|  |  |
|---|---|
| 🤖 **Automatic handling** | AI answers prospect inquiries 24/7 following your instructions |
| 🎯 **Prospect scoring** | Automatic profile evaluation of every interested party before you invest your time |
| 🏠 **Property management** | Register assets, listings, and maintenance tickets in one place |
| 💬 **Full history** | Every conversation is recorded with context so nothing slips through |
| 💳 **Flexible model** | Pay only for the days your properties are active — no fixed subscriptions |

### How does it work?

```
1. You connect your Telegram to coDueño
2. You load your properties and instructions in natural language
3. A prospect messages you → AI responds, filters, and records
4. You receive a summary and decide the next step
```

> 🚧 **Actively in development.** Coming soon for Argentine landlords.

---

## 📈 Para inversores · For investors

El mercado de gestión informal de alquileres en Argentina representa una oportunidad sin solución tecnológica consolidada. Los propietarios individuales dedican horas semanales a tareas repetitivas que coDueño automatiza sin quitarles el control.

**Modelo de negocio:**
- SaaS por créditos: 1 crédito = 1 día de actividad por propiedad
- Pago nativo con MercadoPago
- El costo del cliente escala con su uso real, sin fricción de suscripciones

The informal rental management market in Argentina represents an opportunity with no consolidated technological solution. Individual landlords spend hours weekly on repetitive tasks that coDueño automates without removing their control.

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
