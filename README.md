<!-- Hallmark · pre-emit critique: P5 H5 E5 S5 R5 V4 -->
<!-- Hallmark · genre: modern-minimal · macrostructure: Long Document · theme: Cobalt · enrichment: none -->

<div align="center">

# Tomás Ortellado

**Full-stack developer · React, TypeScript, Node.js y PostgreSQL**

Construyo productos web de punta a punta: modelo de datos, APIs, interfaces, procesos asíncronos y despliegue.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tom%C3%A1s-ortellado-799547255/)
[![Parcialitos](https://img.shields.io/badge/Parcialitos.com-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white)](https://parcialitos.com)
[![Repositorios](https://img.shields.io/badge/Repositorios-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NumberGuan?tab=repositories)

</div>

---

## En pocas palabras

Soy estudiante de 4.º año de Ingeniería en Sistemas de Información en la UTN FRTL y trabajo desarrollando software full-stack en producción. En los últimos meses concentré mi trabajo en dos productos: una plataforma académica propia y un sistema industrial para trabajo de campo.

Me interesa resolver el recorrido completo de un producto: entender el proceso real, diseñar la arquitectura, implementar frontend y backend, cuidar los datos y dejar una operación desplegable y mantenible. Tengo nivel de inglés B2/C1.

## Trabajo reciente

### [Parcialitos.com](https://parcialitos.com) · plataforma académica en producción

Parcialitos organiza parciales, finales, resúmenes y apuntes de las carreras de la UTN FRTL. Lo desarrollé como un producto full-stack: desde la experiencia de carga y descubrimiento de material hasta la validación, moderación y operación del sistema.

**Arquitectura.** Una SPA en React 19 y TypeScript consume una API REST en Express 5. PostgreSQL y Prisma concentran los datos, las sesiones y una cola de trabajos con pg-boss; Cloudinary almacena los archivos. El procesamiento asíncrono extrae texto, aplica OCR cuando hace falta y usa Gemini para sugerir metadatos y asistir la validación, con revisión humana para los casos dudosos.

**Ingeniería de producto.** Google OAuth, búsqueda y filtros, perfiles, reputación, ratings, moderación, previsualización y descarga de archivos, panel administrativo y publicación de novedades. El proyecto usa contratos tipados, migraciones, rate limiting, pruebas con Vitest, Testing Library y Supertest, además de contenedores y despliegue continuo.

`React 19 · TypeScript · Vite · TanStack Query · Express 5 · PostgreSQL · Prisma · pg-boss · Gemini · Cloudinary · Docker`

[Visitar Parcialitos →](https://parcialitos.com)

### Sistema de mediciones industriales · Hazelhoff Ingeniería

Desarrollo y mantengo un sistema interno para relevamientos eléctricos en planta. Reemplaza un flujo basado en papel y carga manual por una aplicación que acompaña el trabajo desde la medición en campo hasta la generación del informe técnico.

**Arquitectura.** La solución es una PWA offline-first en React y TypeScript. Guarda el trabajo localmente en IndexedDB cuando no hay conectividad, sincroniza con una API REST en Node.js y Express y persiste la información en PostgreSQL. El backend genera reportes Excel y Word con mediciones, evidencias fotográficas y documentación asociada.

**Operación.** Incluye captura de fotos y ubicación, validaciones específicas por tipo de medición, roles, trazabilidad de acciones, panel administrativo, monitoreo, backups automatizados y despliegue productivo. Trabajo sobre frontend, backend, base de datos, generación documental, CI/CD y soporte de los flujos reales de campo.

`React · TypeScript · Vite · PWA/Workbox · IndexedDB · Node.js · Express · PostgreSQL · GitHub Actions`

> El código, los datos y los detalles operativos de este sistema son privados. Esta descripción se limita a su alcance profesional y a la arquitectura de alto nivel.

## Cómo trabajo

- **Producto completo.** Puedo moverme entre interfaz, API, modelo de datos, procesamiento de archivos e infraestructura sin perder de vista el flujo del usuario.
- **Confiabilidad fuera del entorno ideal.** Trabajo con sincronización offline, tareas asíncronas, validaciones, recuperación de errores y procesos que deben funcionar con conectividad limitada.
- **Calidad verificable.** Uso TypeScript, esquemas de validación, pruebas automatizadas, migraciones revisables, controles de seguridad y CI/CD.
- **Decisiones con contexto.** Prefiero una arquitectura clara y operable antes que sumar servicios sin necesidad.

## Stack habitual

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-111111?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)

## Otros proyectos

- **[gemini-subagent](https://github.com/NumberGuan/gemini-subagent)** — skill open source que orquesta tareas de código con un subagente Gemini mediante Antigravity CLI, con revisión del resultado y manejo del flujo desde Claude Code.
- **[Extractor OCR](https://github.com/NumberGuan/extractor-ocr)** — aplicación de escritorio en Python para extraer texto de imágenes, PDFs, DOCX y archivos de texto, con procesamiento paralelo y salida a Markdown.
- **[InmoVision](https://github.com/NumberGuan/Inmobiliaria)** — sistema para gestión inmobiliaria y atención automatizada por WhatsApp con Google Gemini.
- **[Mercadito App](https://github.com/NumberGuan/mercadito-app)** — marketplace local construido con Next.js, TypeScript, Prisma y Tailwind CSS.

## Formación y contacto

- Ingeniería en Sistemas de Información · UTN Facultad Regional Trenque Lauquen · 4.º año
- Inglés B2/C1
- Argentina
