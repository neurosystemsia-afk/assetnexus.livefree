<div align="center">

# 🚧 ASSET NEXUS LIVE — Community Edition (EN CONSTRUCCIÓN) 🚧

### 🎮 El sistema operativo de IA para creadores de Fortnite / UEFN
#### _The AI operating system for Fortnite / UEFN creators_

<br/>

![Estado](https://img.shields.io/badge/ESTADO-EN%20CONSTRUCCIÓN-FF9800?style=for-the-badge)
![WIP](https://img.shields.io/badge/WORK%20IN%20PROGRESS-🚧-FFB020?style=for-the-badge)
![Made with React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-3D-000000?style=for-the-badge&logo=three.js&logoColor=white)

![Local First](https://img.shields.io/badge/META-LOCAL%20%2F%20INSTALABLE-7C5CFF?style=for-the-badge)
![Hecho en Colombia](https://img.shields.io/badge/Hecho%20en-COLOMBIA-FCD116?style=for-the-badge)

</div>

---

> ## 🚧 AVISO: Proyecto en construcción activa
>
> **🇪🇸 Esto es un trabajo en progreso.** Estamos **adaptando** Asset Nexus Live (originalmente una app de nube) para convertirla en una aplicación **instalable y local**. Todavía **NO está terminada**: hay módulos en migración, piezas por pulir y cosas que pueden no funcionar aún. Se comparte de forma abierta para construir **junto a la comunidad**.
>
> **🇬🇧 This is a work in progress.** We're **adapting** Asset Nexus Live (originally a cloud app) into a **locally installable** application. It is **not finished yet** — modules are being migrated, things are being polished, and some parts may not work. Shared openly to build **together with the community**.

---

## 🎯 Qué estamos construyendo (y por qué)

El objetivo de esta edición es **transformar** la plataforma para que:

| Meta | Estado |
|------|--------|
| 📦 Que sea **instalable** (no un ejecutable suelto, no la nube) | 🟡 En progreso |
| 💻 Que corra **localmente en tu propio computador** | 🟡 En progreso |
| 🆓 Que sea **gratis** para la comunidad UEFN | 🟢 Sí |
| 🔧 Que cualquiera pueda **mejorarla** | 🟢 Sí |

> 💡 **¿Por qué local y no en la nube?** La versión en la nube **genera costos** (servidores, GPU, APIs) y **necesita conexión permanente**. Por eso estamos adaptando esta versión para que **tú la alojes en tu máquina**, con tus propios recursos y tus propias llaves. Así la puede usar cualquiera sin pagarle servidores a nadie.

---

## ✨ Módulos (las "Gems") — estado actual

> ⚠️ Los estados pueden cambiar mientras avanza la construcción.

| Gem | Qué hará | Estado |
|-----|----------|--------|
| 🌍 **GAIA** | Terrenos 3D procedurales (heightmaps 16-bit) | 🟡 En adaptación |
| 🎨 **SPECTRA** | Miniaturas para la pestaña Discovery de Fortnite | 🟡 En adaptación |
| ⏳ **KRONOS** | Forja rápida de 3D | 🟡 En adaptación |
| 🗿 **TITAN** | Modelos / concept art 3D con IA | 🟡 En adaptación |
| 🧠 **PERSEUS** | Código **Verse** para UEFN | 🔜 Próximamente |
| 🕸️ **EXODIA** | Pipeline visual de agentes IA | 🔜 Próximamente |
| 🐉 **SLYFER** | Copiloto en tiempo real | 🔜 Próximamente |

---

## 🧪 Probarlo (modo desarrollo)

> Aún en construcción — espera ver cosas incompletas. Requiere [Node.js](https://nodejs.org) (LTS).

```bash
git clone https://github.com/neurosystemsia-afk/assetnexus.livefree.git
cd assetnexus.livefree
npm install
cp .env.example .env   # edita .env con tus datos de Supabase
npm run dev
```

En Windows también puedes usar **`install.bat`** y luego **`start.bat`** (doble clic).

La **interfaz** carga, pero la **generación** todavía depende de configurar Supabase + tus propias llaves de IA (y sigue en ajuste).

---

## 🗺️ Hoja de ruta (en construcción)

- [x] Liberar la base como proyecto abierto
- [x] Quitar secretos y partes privadas (admin, pagos, seguridad)
- [x] Acceso sin login para la comunidad
- [ ] Terminar la adaptación de cada módulo para correr 100% local
- [ ] Instalador de un solo paso más simple
- [ ] Documentación completa
- [ ] Soporte de modelos locales (para que sea gratis de verdad sin APIs de pago)

---

## 🧩 Nota honesta sobre el alcance

Esta edición **abierta** NO incluye: panel de administración, pagos/créditos, módulos de seguridad, ni el **algoritmo propietario** del autor. Esas piezas se mantienen privadas. Lo que se comparte es la **carcasa funcional** para que la comunidad la use y la mejore mientras el proyecto sigue creciendo.

---

<div align="center">

## 🏛️ Hecho por

**Daniel Velásquez Cícero** — Fundador & CEO
**NEURO SYSTEM I.A. S.A.S.** 🇨🇴 (NIT: 901.985.131-1)

_Construido con disciplina, resiliencia y orgullo colombiano._ 🇨🇴

<br/>

🚧 **Proyecto en construcción — vuelve pronto para ver avances** 🚧
⭐ Deja una estrella para seguir el progreso ⭐

</div>
