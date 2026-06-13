<div align="center">

# ⚡ ASSET NEXUS LIVE — Community Edition ⚡

### 🎮 El sistema operativo de IA para creadores de Fortnite / UEFN
#### _The AI operating system for Fortnite / UEFN creators_

<br/>

![Made with React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-3D-000000?style=for-the-badge&logo=three.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-⚡-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-Backend-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)

![Self-Hosted](https://img.shields.io/badge/100%25-SELF--HOSTED-00E5FF?style=for-the-badge)
![Free](https://img.shields.io/badge/PRECIO-GRATIS-37E0A0?style=for-the-badge)
![Local First](https://img.shields.io/badge/LOCAL-FIRST-7C5CFF?style=for-the-badge)
![Hecho en Colombia](https://img.shields.io/badge/Hecho%20en-COLOMBIA-FCD116?style=for-the-badge)

<br/>

> **🇪🇸 Genera modelos 3D, terrenos, miniaturas y más — con IA, desde una sola plataforma que corre en TU computador.**
>
> **🇬🇧 Generate 3D models, terrains, thumbnails and more — AI-powered, from one platform that runs on YOUR machine.**

</div>

---

## 🟢 Importante: esto se **instala**, no se "ejecuta en la nube"

Esta es la **edición comunitaria, gratuita y auto-hospedable** de Asset Nexus Live.

| | |
|---|---|
| ✅ **Es una app instalable** | La descargas y la corres en **tu propio computador**. |
| ✅ **Local-first** | Tú controlas tus datos y tus recursos. |
| ✅ **Gratis** | Sin suscripción. La comunidad la puede usar y mejorar. |
| ❌ **NO es un ejecutable (.exe) suelto** | Es un proyecto que instalas con un comando (o doble clic). |
| ❌ **NO corre en nuestra nube** | La versión en la nube **genera costos** (servidores, GPU, APIs) y **requiere conexión permanente**. Por eso liberamos la versión que **tú** alojas. |

> 💡 **En cristiano:** la nube cuesta dinero y necesita internet siempre. Esta versión la instalas en tu máquina, así cualquiera la puede usar **sin pagarle servidores a nadie**. Tú pones tus propias llaves y tu propia capacidad.

---

## ✨ Módulos (las "Gems")

| Gem | Qué hace | Estado |
|-----|----------|--------|
| 🌍 **GAIA** | Terrenos 3D procedurales (heightmaps 16-bit) con vista previa en tiempo real | 🟢 Activo |
| 🎨 **SPECTRA** | Miniaturas optimizadas para la pestaña Discovery de Fortnite | 🟢 Activo |
| ⏳ **KRONOS** | Forja rápida de 3D | 🟢 Activo |
| 🗿 **TITAN** | Modelos y concept art 3D con IA (GLB/OBJ/FBX) | 🟢 Activo |
| 🧠 **PERSEUS** | Generación de código **Verse** para UEFN | 🔜 Próximamente |
| 🕸️ **EXODIA** | Pipeline visual de agentes IA | 🔜 Próximamente |
| 🐉 **SLYFER** | Copiloto en tiempo real | 🔜 Próximamente |

---

## 🚀 Instalación rápida (Windows)

**Requisito previo:** tener [Node.js](https://nodejs.org) (versión LTS).

### Opción A — Doble clic (la más fácil)
1. Descarga este repositorio (botón verde **Code → Download ZIP**) y descomprímelo.
2. Doble clic en **`install.bat`** → instala todo solo.
3. Abre el archivo **`.env`** y pon tus datos de Supabase (ver abajo).
4. Doble clic en **`start.bat`** → abre la app en `http://localhost:8080`.

### Opción B — Terminal
```bash
git clone https://github.com/neurosystemsia-afk/assetnexus.livefree.git
cd assetnexus.livefree
npm install
cp .env.example .env   # edita .env con tus datos
npm run dev
```

---

## 🔑 Configuración (para que la generación funcione)

La **interfaz** funciona apenas la instalas. Para que los módulos **generen** de verdad necesitas tus **propias llaves** (es lo que hace que sea gratis y self-hosted):

1. **Supabase** (gratis en [supabase.com](https://supabase.com)) → copia `VITE_SUPABASE_URL` y `VITE_SUPABASE_PUBLISHABLE_KEY` en tu `.env`.
2. **Proveedores de IA** (NVIDIA, fal, etc.) → se configuran como _secrets_ en tu proyecto Supabase, no en el código.

> Sin estas llaves la app abre y navega perfecto, pero la generación no devuelve resultados. Tú pones tus llaves, tú controlas tus costos. 🔐

---

## 🧩 ¿Qué incluye esta edición comunitaria?

✅ **Incluido:** módulos de generación (Titan, Spectra, Gaia, Kronos), interfaz completa, visor 3D, instaladores.

❌ **No incluido** (es la parte privada/comercial): panel de administración, sistema de pagos y créditos, módulos de seguridad, y el **algoritmo propietario de optimización** del autor.

> Si la mejoras, **compártelo**. Esa es la idea. 🤝

---

## 🛠️ Stack

`React 18` · `TypeScript` · `Vite` · `Tailwind` · `shadcn/ui` · `Three.js / React-Three-Fiber` · `Supabase` · `Framer Motion`

---

<div align="center">

## 🏛️ Hecho por

**Daniel Velásquez Cícero** — Fundador & CEO
**NEURO SYSTEM I.A. S.A.S.** 🇨🇴 (NIT: 901.985.131-1)

_Construido con disciplina, resiliencia y orgullo colombiano._
_Built with discipline, resilience and Colombian pride._

<br/>

⭐ **Si te sirve, deja una estrella y comparte con la comunidad UEFN** ⭐

![License](https://img.shields.io/badge/Licencia-Community-00E5FF?style=for-the-badge)

</div>
