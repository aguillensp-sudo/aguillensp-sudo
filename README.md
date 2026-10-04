# Hola, soy Álvaro

Fundador de [Nortex Systems](https://nortexsys.com), consultora de software a medida, IA agéntica y
transformación digital para pymes. Trabajo desde Madrid.

Me interesa construir sistemas con agentes de IA que se puedan **verificar**: especificar antes de
programar, medir lo que produce cada modelo y dejar por escrito lo que falló.

## Proyectos

| Proyecto | Qué es | Estado |
| --- | --- | --- |
| [**Bearingworld.io**](https://github.com/aguillensp-sudo/RinWorld.io) | Plataforma B2B para distribuidores de rodamientos: búsqueda conversacional (Claude) y negociación con cifrado de extremo a extremo. React, TypeScript, Supabase. [Demo](https://rin-world-io.vercel.app) | En desarrollo. 1.710 pruebas unitarias y más de 140 de Playwright, CI con despliegue automático |
| [**Paperdrop for Ninox**](https://github.com/nortexsys/Ninox_Tickets) | App Android (Flutter) que lee tickets y facturas en el dispositivo y los guarda en la base de Ninox del usuario. Validación determinista (dígitos de control, aritmética, tipos de IVA) en lugar de confiar en el OCR | MVP en construcción |
| [**ninox-agent-skill**](https://github.com/aguillensp-sudo/ninox-agent-skill) | Skill para agentes que trabajan con la API de Ninox: las trampas verificadas del camino de escritura (un 500 suele ser un error de mapeo, los campos con fórmula, nunca reintentar a ciegas una creación) | Publicado |
| [**Nexcuba**](https://github.com/nortexsys/Nexcuba) | Plataforma de ecosistema empresarial. Next.js, especificaciones con OpenSpec, e2e de accesibilidad, SEO y rendimiento | En desarrollo |
| [**Automatizacion_BFI**](https://github.com/aguillensp-sudo/Automatizacion_BFI) | Aplicación de escritorio para Windows que extrae movimientos de extractos bancarios en PDF y los inserta en Ninox, sin escribir nada hasta que el usuario confirma y releyendo cada registro creado | En uso |
| [web-nortexsys](https://github.com/nortexsys/web-nortexsys) · [web-julsaindustrial](https://github.com/nortexsys/web-julsaindustrial) | Webs en Next.js, con portal de cliente y panel de administración en la segunda | Publicadas |

## Cómo trabajo

- **Especificación primero.** Spec-Driven Development con OpenSpec; el comportamiento está escrito
  antes que el código.
- **Las reglas son comprobaciones.** Si una norma importa, la CI la hace cumplir: pureza del núcleo,
  guardas de privacidad, tipos, tests y despliegue.
- **Medir en vez de suponer.** En Bearingworld, cada corrida del arnés que genera pantallas
  registra coste real, reintentos y trabajo a mano; los hallazgos quedan en un registro.
- **El modelo que escribe el código no escribe los tests que lo evalúan.**

## Stack

TypeScript · React · Next.js · Python · Dart y Flutter · Supabase y PostgreSQL · Playwright y
Vitest · GitHub Actions · Claude y otros modelos de lenguaje.
