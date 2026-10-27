<!-- l10n-sync: source-file="workshop/00-overview.md" -->
# 🎮 Mona Mayhem — Taller de GitHub Copilot

---

> **Duración:** ~1 hora  
> **Nivel:** Intermedio  
> **Stack:** Astro / Node.js / TypeScript

Construye una aplicación de arcade retro para comparar las contribuciones de GitHub — **Mona Mayhem** — mientras aprendes toda la variedad de flujos de trabajo de GitHub Copilot. El taller ofrece **dos itinerarios**: una experiencia con VS Code y otra con GitHub Copilot CLI.

---

## 🎯 Elige tu itinerario

- **Itinerario de VS Code** — trabaja dentro del editor y practica Chat, Plan Mode, Agent Mode, agentes en segundo plano y el ciclo de revisión integrado.
- **Itinerario del CLI** — trabaja en el terminal y practica `copilot`, el contexto con `@file`, `/plan`, ediciones autónomas, `/fleet`, `/delegate` y `/review`.

Sigue el itinerario que mejor se adapte a tu forma de trabajar.

---

## 📋 Lista rápida de comprobación

Antes de empezar, verifica lo siguiente:

- [ ] GitHub Copilot está habilitado en tu cuenta
- [ ] Node.js está instalado
- [ ] Git está instalado y configurado
- [ ] Tienes preparados el navegador y el terminal

<!-- track:vscode:start -->
- [ ] VS Code **v1.107+** (sin actualizaciones pendientes)
- [ ] Has iniciado sesión en la extensión de **GitHub Copilot**
- [ ] El panel de Chat está abierto y Agent está listo
<!-- track:vscode:end -->

<!-- track:cli:start -->
- [ ] GitHub Copilot CLI está instalado y disponible como `copilot`
- [ ] Has iniciado sesión en el CLI con `/login`
- [ ] Te sientes cómodo usando comandos slash como `/help`, `/plan` y `/review`
<!-- track:cli:end -->

> 💡 **Consejo:** Usa el DevContainer para disponer de un entorno preconfigurado y empezar rápido con VS Code.

---

## 🧠 Qué aprenderás

| # | Habilidad | Descripción |
|---|-----------|-------------|
| 1 | **Ingeniería de contexto** | Enseñar a Copilot cómo es tu código base con instrucciones, referencias y restricciones claras |
| 2 | **Planificar primero** | Diseñar la arquitectura antes de implementar |
| 3 | **Implementación agéntica** | Dejar que Copilot realice tareas de programación en varios pasos bajo tu supervisión |
| 4 | **Diseño iterativo** | Usar Copilot para transformar los elementos visuales y refinar los detalles de interacción |
| 5 | **Flujos de trabajo paralelos** | Repartir el trabajo entre agentes, sesiones o tareas delegadas |

<!-- track:vscode:start -->
### Enfoque en las funcionalidades de VS Code

- **Chat + modo Ask** para explorar
- **Plan Mode** para prompts de arquitectura y diseño
- **Agent Mode** para implementar en varios archivos
- **Agentes en segundo plano y en la nube** para pulir en paralelo
<!-- track:vscode:end -->

<!-- track:cli:start -->
### Enfoque en las funcionalidades de Copilot CLI

- **Sesiones interactivas del CLI** con `copilot`
- **`/plan` y Shift+Tab** para planificar de forma estructurada
- **Ediciones autónomas** con aprobaciones en línea y `/diff`
- **`/fleet`, `/delegate` y `/review`** para trabajar en paralelo y aplicar controles de calidad
<!-- track:cli:end -->

---

## 📚 Partes del taller

| Parte | Título | Descripción |
|------|-------|-------------|
| [**01**](01-setup.md) | Configuración e ingeniería de contexto | Crea tu repositorio, prepara el entorno y proporciona a Copilot el contexto adecuado |
| [**02**](02-plan-and-scaffold.md) | Planificación y estructura inicial | Diseña la API y la arquitectura de páginas antes de implementar |
| [**03**](03-agent-mode.md) | Construcción del juego | Conecta la página de batalla y los gráficos de contribuciones con ayuda agéntica |
| [**04**](04-design-vibes.md) | Diseño visual primero | Convierte la estructura inicial en una experiencia de arcade retro |
| [**05**](05-polish.md) | Pulido y trabajo en paralelo | Usa flujos multiagente para mejorar la experiencia de usuario, la resiliencia y la calidad |
| [**06**](06-bonus.md) | Bonus y extensiones | Explora funcionalidades abiertas, formas de compartir y experimentos adicionales |

---

## 💡 Consejos profesionales

1. **Mantén el navegador abierto** — observa las actualizaciones en directo mientras programas.
2. **Haz commits con frecuencia** — guarda puntos de control limpios mientras iteras.
3. **Perfecciona el plan antes de implementar** — los mejores planes producen mejores resultados.
4. **Revisa los cambios de Copilot** — usa la vista de diferencias o las herramientas de revisión del CLI en lugar de aceptarlos a ciegas.

<!-- track:vscode:start -->
5. **Usa puntos de control y Deshacer** en el chat si una iteración se desvía.
<!-- track:vscode:end -->

<!-- track:cli:start -->
5. **Usa `/session`, `/context` y `/share file`** para inspeccionar o conservar tu trabajo.
<!-- track:cli:end -->
