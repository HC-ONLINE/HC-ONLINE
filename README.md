# 👋 ¡Hola! Soy Andres Henriquez (HC-ONLINE)

Desarrollador e investigador especializado en la intersección entre la **seguridad ofensiva** y la **arquitectura de software**. Mi enfoque se centra en construir soluciones mantenibles, diseñando herramientas de auditoría, orquestación de LLMs y sistemas de identidad donde la seguridad no es un parche, sino el cimiento

---

## 1) Sobre mí — Resumen rápido

- 👨‍💻 **Rol:** Desarrollador backend enfocado en seguridad aplicada, diseño de APIs, control de acceso (IAM) y construcción de herramientas de auditoría.

- 🔭 **Actualmente trabajando en:**

  - **Auditoría y superficie de ataque:** herramientas como [CiberWebScan](https://github.com/HC-ONLINE/CiberWebScan) y [LexGuard](https://github.com/HC-ONLINE/LexGuard) enfocadas en análisis pasivo y detección de riesgo real.  
  - **Orquestación de modelos:** [ModelRouter](https://github.com/HC-ONLINE/ModelRouter), centrado en routing, fallback y observabilidad de LLMs.  
  - **Gestión de identidad (IAM):** sistemas de autenticación ([AccessManager](https://github.com/HC-ONLINE/AccessManager)) y autorización ([PermissionManager](https://github.com/HC-ONLINE/PermissionManager)) granular con separación clara entre autenticación y permisos.

- 🌱 **Enfoque actual:** Profundización en seguridad backend: rate limiting, control de acceso granular (RBAC/ABAC) y diseño de APIs resilientes con observabilidad.

- 💬 **Puedo ayudar con:** Revisión de arquitectura backend, diseño de APIs seguras, modelado de autorización (IAM) y contribuciones técnicas a proyectos open source.

---

## 2) Filosofía de Desarrollo & Principios

Mis decisiones arquitectónicas no son aleatorias. Se basan en un conjunto de reglas que garantizan la integridad y longevidad del software.

- Seguridad & Ética por Diseño

  - **Privilegio Mínimo:** Diseño sistemas donde cada componente tiene solo el acceso necesario. La seguridad no es un "feature" final, es el cimiento de la validación temprana.

  - **Auditoría Ética:** Desarrollo herramientas para la transparencia y la educación. Mis proyectos incluyen límites de uso y advertencias para prevenir el abuso y fomentar la responsabilidad.

  - **Privacidad Radical:** Recolección mínima de datos. Si un dato no es crítico para la función, no se procesa ni se almacena.

- Arquitectura & Mantenibilidad

  - **Dependencias Justificadas:** Evito incluir dependencias innecesarias. Prefiero asumir complejidad controlada en código propio antes que introducir dependencias opacas que comprometan la seguridad o la auditabilidad.

  - **Simplicidad Evolutiva:** Priorizo soluciones claras y legibles. Si la complejidad crece, la refactorización es obligatoria para mantener la deuda técnica bajo control.

  - **Contratos Explícitos:** Ya sea en APIs o en sistemas de diseño, creo en interfaces claras que reduzcan la ambigüedad.

- Observabilidad & Transparencia

  - **Trazabilidad:** Un sistema que no se puede medir, no se puede asegurar. Implemento telemetría y logs explicables para auditorías reproducibles.

  - **Open Source de Calidad:** Documentación rigurosa y pruebas exhaustivas. El código abierto es mi estándar para fomentar la colaboración y la revisión por pares.

---

## 3) Tecnologías y herramientas

No utilizo herramientas por tendencia, sino por control y adecuación al problema.

### Backend & Seguridad

- **Python:** desarrollo de herramientas de auditoría, análisis de superficie de ataque y procesamiento de datos.  

- **Java + Spring Boot:** construcción de APIs robustas con enfoque en control de acceso, validación y separación de responsabilidades.  

### Arquitectura & Sistemas

- **Diseño de APIs:** contratos explícitos, validación temprana y manejo de errores consistente.  

- **Control de acceso (IAM):** implementación de modelos RBAC/ABAC, separación entre autenticación y autorización, y evaluación de JWT vs sesiones según contexto.  

- **Rate limiting & resiliencia:** estrategias de limitación, control de abuso y diseño tolerante a fallos.  

- **Orquestación de LLMs:** routing, fallback entre proveedores y observabilidad de ejecución.

### Infraestructura & Entrega

- **Docker:** aislamiento de servicios y entornos reproducibles.  
- **GitHub Actions:** automatización de builds, testing y despliegues.

### Frontend (enfoque complementario)

- **Astro + Tailwind:** construcción de interfaces ligeras orientadas a rendimiento, con sistemas de estilos basados en tokens.
---

## 4) Proyectos destacados

- 🚀 **[ModelRouter](https://github.com/HC-ONLINE/ModelRouter)**: Orquestador de LLMs (Groq, OpenRouter, Ollama) con soporte para streaming y observabilidad.  

- 🛡️ **[CiberWebScan](https://github.com/HC-ONLINE/CiberWebScan)**: Herramienta de reconocimiento pasivo para análisis de superficie de ataque.  

- 🧠 **[LexGuard – PII Scanner](https://github.com/HC-ONLINE/LexGuard)**: Motor CLI-first para detección y correlación de PII, enfocado en riesgo real y alineado con cumplimiento normativo.

- 🔑 **IAM Suite ([AccessManager](https://github.com/HC-ONLINE/AccessManager) / [PermissionManager](https://github.com/HC-ONLINE/PermissionManager))**: Proyectos centrados en la lógica de autorización y autenticación segura.  

- 🎨 **[ORBIT-UI](https://github.com/HC-ONLINE/ORBIT-UI)**: Design system centrado en contratos explícitos y escalabilidad visual.

---

## 5) Contacto y Colaboración

- **¿Buscas colaborar?** Abre un issue o envía un PR en mis proyectos abiertos.  

- **Trabajo profesional:** Escríbeme detallando objetivos y alcance a mi email. ![Available for hire](https://img.shields.io/badge/Available%20for%20hire-yes-brightgreen)

📧 **Email:** [henriquezandres856@gmail.com](mailto:henriquezandres856@gmail.com)

---

## English — Quick

# 👋 Hi — I’m Andres Henriquez (HC-ONLINE)

Developer & researcher focused on web security and reliable software architecture. I build practical tools for reconnaissance, orchestration and design systems.

## Core Principles

- Security by design — minimize attack surface and apply least privilege.  
- Privacy & responsible use — collect/process only what’s necessary; tools for ethical auditing and education.
- Dependencies with explicit justification — I avoid libraries unless they provide a clear, auditable benefit, preferring controlled complexity over opaque dependencies.
- Observability & traceability — telemetry and logs to enable reproducible audits.  
- Simplicity & maintainability — prefer clear, auditable solutions and refactor when needed.  
- Transparency & collaboration — docs, tests and open contribution flow.  
- Ethics & responsibility — discourage misuse; include use limits and warnings for sensitive tools.

- **Contact:** [henriquezandres856@gmail.com](mailto:henriquezandres856@gmail.com)
