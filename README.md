# 👋 ¡Hola! Soy Julian Urueña Pineda

## 🚀 Senior Full Stack Developer | Data Engineer | DevOps

Desarrollador con **experiencia comprobada en arquitectura y deployment de sistemas críticos** que sirven a **180,000+ usuarios** en el sector de utilities colombiano. Especializado en **modernización de arquitecturas legacy**, logrando mejoras de rendimiento de hasta **200x** y reducción de costos operativos del **40%**.

### 💡 Perfil Híbrido
- **Full Stack Development**: React/NestJS/Oracle
- **Data Engineering**: Azure Databricks/PySpark/Delta Lake
- **DevOps**: Azure AKS/Docker/CI-CD
- **15+ sistemas empresariales** en producción con **99.7% uptime**

---

## 🎯 Sistemas en Producción

### Aplicaciones Empresariales Deployadas

Estos son sistemas reales que desarrollé y que están actualmente en producción, sirviendo a miles de usuarios:

#### 🏢 [Sistema de Registro de Visitas](https://registrovisitas.efigas.com.co/)
**Gestión empresarial en tiempo real con QR codes**

<details>
<summary><b>📋 Detalles Técnicos</b></summary>

**Stack**: React 18, Vite, TypeScript, Node.js, Express, Oracle, WebSockets

**Características**:
- Registro en tiempo real con generación de QR codes (sub-segundo)
- Dashboard para personal de seguridad con roles diferenciados
- Integración con directorio corporativo
- Notificaciones en tiempo real vía WebSockets

**Desafíos técnicos resueltos**:
- Generación de QR instantánea para escenarios de alto tráfico
- Arquitectura offline-first para áreas con conectividad limitada
- Sistema de notificaciones en tiempo real escalable

**Impacto**: 5,000+ visitas registradas mensualmente, reducción del 70% en tiempo de registro
</details>

---

#### 📄 [Portal de Certificados Tributarios](https://certificadosretencion.efigas.com.co/)
**Generación automatizada de certificados oficiales con firma digital**

<details>
<summary><b>📋 Detalles Técnicos</b></summary>

**Stack**: NestJS, Oracle, pdf-lib, Azure AD, React, SAP integration

**Características**:
- Generación de PDFs con firmas digitales y formato DIAN (autoridad tributaria colombiana)
- Autenticación Azure AD SSO para clientes corporativos
- Integración SOAP con sistemas legacy SAP para validación fiscal
- Audit trail completo para cumplimiento regulatorio

**Desafíos técnicos resueltos**:
- Generación dinámica de PDFs con layouts complejos (10K+ certificados/mes)
- Integración con SAP legacy vía SOAP con retry logic y circuit breaker
- Cumplimiento estricto con formatos oficiales de DIAN

**Impacto**: 10,000+ certificados generados mensualmente, reducción del 90% en tiempo de emisión
</details>

---

#### 🔄 [Portal de Actualización de Datos](https://actualizate.efigas.com.co/)
**Self-service portal con verificación SMS y procesamiento de documentos**

<details>
<summary><b>📋 Detalles Técnicos</b></summary>

**Stack**: React, TypeScript, NestJS, Oracle, Sharp, SMS gateway, SmartFlex CIS

**Características**:
- Formulario multi-paso con validación en tiempo real
- Verificación OTP vía SMS con múltiples proveedores (fallback)
- Upload y procesamiento de documentos con optimización de imágenes (Sharp)
- Sincronización en tiempo real con sistema CIS SmartFlex

**Desafíos técnicos resueltos**:
- Optimización de imágenes reduciendo tiempo de upload en 70%
- Gateway SMS con providers secundarios para 99.9% delivery
- Data sync con legacy CIS sin downtime usando event-driven architecture

**Impacto**: 15,000+ actualizaciones mensuales, reducción del 65% en llamadas de soporte
</details>

---

#### 🛠️ [Catálogo de Servicios](https://portafolioservicios.efigas.com.co/)
**Portal público optimizado para SEO con gestión de contenido**

<details>
<summary><b>📋 Detalles Técnicos</b></summary>

**Stack**: Next.js, React, Tailwind CSS, Oracle, CMS integration, Vercel/CDN

**Características**:
- Static site generation para performance óptimo (Lighthouse 95+)
- Catálogo dinámico con soporte multimedia (imágenes, videos, PDFs)
- SEO optimization para tráfico orgánico
- Responsive design mobile-first

**Desafíos técnicos resueltos**:
- SSG/ISR balanceado para contenido dinámico pero performante
- Lazy loading y code splitting reduciendo carga inicial en 60%
- CDN integration para assets multimedia con cache inteligente

**Impacto**: 25,000+ visitas mensuales orgánicas, 40% incremento en conversiones
</details>

---

### 📊 Impacto Agregado de Sistemas Públicos

| Métrica | Valor |
|---------|-------|
| 👥 Usuarios activos | 180,000+ |
| 📈 Sesiones mensuales | 50,000+ |
| ⚡ Uptime promedio | 99.7% |
| 📱 Transacciones/mes | 180,000+ |
| 🎯 Tasa de éxito | 99.2% |

---

## 💼 Experiencia Profesional Destacada

### 🏢 Efigas S.A. E.S.P. (2022 - Presente)
**Senior Full Stack Developer**

Empresa de servicios públicos de gas natural con cobertura en el Eje Cafetero colombiano, sirviendo a **180,000+ usuarios** en 3 departamentos.

#### 🔥 Proyectos Principales

<details>
<summary><b>🗺️ TEA - Territorial Energy Analysis (Sistema de Gestión Geográfica)</b></summary>

**Contexto**: Migración completa de arquitectura monolítica legacy que presentaba problemas críticos de escalabilidad.

**Stack**: Node.js, Express, Oracle, Sequelize ORM, React 18, Vite

**Lo que hice**:
- Lideré migración de Python/Flask/MongoDB a Node.js/Express/Oracle
- Rediseñé arquitectura consolidando 107 endpoints en 63 optimizados
- Unifiqué 3 bases de datos MongoDB en 1 Oracle centralizado
- Refactoricé frontend de 139 componentes a 31 componentes modulares

**Resultados**:
- ⚡ **Mejora de ~200x** en tiempo de builds (CRA→Vite: 12min → 3.5seg)
- 📉 **Reducción del 60%** en incidencias de producción (15/mes → 6/mes)
- 🚀 **Deployment time**: 2 horas → 15 minutos con CI/CD automatizado
- 💰 Habilitó nuevo módulo de análisis predictivo generando $45M COP adicionales en Q1

</details>

<details>
<summary><b>💼 Preventa-CRM (Sistema de Gestión Comercial)</b></summary>

**Contexto**: CRM completo para optimizar procesos de 50+ asesores comerciales.

**Stack**: NestJS, Oracle, React, Leaflet, Recharts

**Lo que hice**:
- Diseñé arquitectura con 144 endpoints REST en 24 módulos
- Implementé gestión geográfica con Leaflet para zonificación
- Desarrollé dashboards en tiempo real con Recharts
- Sistema de roles (Admin, Coordinador, Asesor) con permisos granulares

**Resultados**:
- 📈 **Conversión mejorada**: 23% → 38% en 8 meses
- ⏱️ **Reducción del 40%** en tiempo de onboarding de clientes (3 días → 18 horas)
- 👥 Gestión eficiente de 50+ asesores con tracking completo de pipeline

</details>

<details>
<summary><b>🔗 Middleware de Integración Empresarial (OSF Integrator)</b></summary>

**Contexto**: Integrador central conectando sistemas críticos de facturación, contratos, pagos, certificados.

**Stack**: Express, Oracle (3 pools simultáneos), PostgreSQL, SOAP/REST

**Lo que hice**:
- Desarrollé 42 módulos de recursos (1,236 archivos JS)
- Gestioné 3 pools Oracle + PostgreSQL simultáneamente
- Implementé circuit breaker y fallback para integraciones
- Sistema de logging centralizado con Winston

**Resultados**:
- 💯 **99.7% uptime** en 18 meses de operación
- 📦 **180,000+ transacciones** procesadas mensualmente
- 🎯 **99.2% tasa de éxito** en integraciones con circuit breaker

</details>

<details>
<summary><b>🏗️ Backend Empresarial NestJS (Multi-Instancia)</b></summary>

**Contexto**: Infraestructura backend robusta con conexión simultánea a múltiples instancias Oracle.

**Stack**: NestJS, Oracle (8 instancias), Redis, pdf-lib, Sharp, ExcelJS

**Lo que hice**:
- Arquitectura con 20+ módulos NestJS y 27 controladores
- Pool dedicado por cada instancia Oracle para aislamiento
- Generación automatizada de PDFs, procesamiento de imágenes, Excel
- Integración Microsoft Graph API y monitoreo APM

**Resultados**:
- ⚡ **Latencia promedio <200ms** bajo carga alta
- 🔄 **8 instancias Oracle** gestionadas simultáneamente sin contención
- 📧 Integración exitosa con Graph API para emails corporativos

</details>

<details>
<summary><b>🌐 Portal Web Multi-Tenant</b></summary>

**Contexto**: Plataforma unificada sirviendo a 3 empresas desde una sola base de código.

**Stack**: React, TypeScript, Bull, Redis, AWS (S3, SES, SNS), 4 pasarelas de pago

**Lo que hice**:
- Arquitectura multi-tenant con 807 archivos JS modulares
- Sistema de colas (77+ handlers) para emails, SMS, WhatsApp
- Integración 4 pasarelas (PayU, ePayco, Nuvei, ECCollect)
- OAuth 2.0 + Social Auth (Google/Apple/Facebook)

**Resultados**:
- 💰 **Reducción de 65%** en costos de mantenimiento
- 📧 **1.2M emails/mes** con 98.7% delivery rate (AWS SES)
- 👥 Soporte para **50K+ usuarios concurrentes**
- 📊 Retención mejorada: **67% → 84%** mediante programa de fidelización

</details>

<details>
<summary><b>🤖 Pipeline de Validación RNE (Cumplimiento Normativo)</b></summary>

**Contexto**: Pipeline automatizado para cumplimiento con Registro Nacional de Bases de Datos.

**Stack**: Azure Databricks, PySpark, Delta Lake, Unity Catalog, JWT

**Lo que hice**:
- Pipeline diario procesando 206K+ registros con deduplicación
- Integración JWT con API gubernamental
- Generación automática de reportes de cumplimiento
- Almacenamiento en Delta Lake con Unity Catalog

**Resultados**:
- ✅ **100% cumplimiento normativo** verificado
- ⏱️ **Reducción de 95%** en tiempo de procesamiento (8 horas → 24 minutos)
- 📊 **206K+ registros** procesados diariamente de forma automatizada

</details>

<details>
<summary><b>⚙️ Pipeline de Órdenes de Trabajo</b></summary>

**Contexto**: Automatización de creación de órdenes complementarias en OpenSmartFlex.

**Stack**: Azure Databricks, PySpark, Delta Lake, REST API, Unity Catalog

**Lo que hice**:
- Pipeline procesando +4,800 órdenes desde Delta Lake
- Validación de condiciones de negocio por tipo de orden
- Creación automática vía API REST OpenSmartFlex
- Auditoría completa en Unity Catalog

**Resultados**:
- 🔄 **4,800+ órdenes** automatizadas mensualmente
- ✅ **100% trazabilidad** con auditoría completa
- ⏱️ Reducción de 80% en tiempo de generación manual

</details>

---

## 🛠️ Stack Tecnológico

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

**Especialidades**: React 18/19, Angular, Vue.js, Material-UI, Leaflet Maps, Chart.js/Recharts, React Hook Form

### Backend
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Especialidades**: API-First Design, Microservices, SOLID Principles, Event-Driven Architecture, OAuth 2.0, JWT

### Bases de Datos
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**Especialidades**: Connection Pooling Avanzado (8 instancias simultáneas), PL/SQL, Migraciones Versionadas, Delta Lake

### Data Engineering
![Azure Databricks](https://img.shields.io/badge/Azure_Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**Especialidades**: ETL Pipelines, Delta Lake, Unity Catalog, Procesamiento Masivo (206K+ registros/día)

### DevOps & Cloud
![Azure](https://img.shields.io/badge/Azure-0078D7?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)

**Especialidades**: Azure DevOps (CI/CD), AKS, Azure AD, AWS (S3, SES, SNS), Sentry, APM

### Testing & Quality
![Jest](https://img.shields.io/badge/Jest-323330?style=for-the-badge&logo=Jest&logoColor=white)
![Supertest](https://img.shields.io/badge/Supertest-07BA82?style=for-the-badge)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)

**Cobertura**: 85%+ con Jest, Supertest, Vitest, Testing Library

---

## 📊 Métricas de Impacto

```
📈 Sistemas en Producción:        15+
👥 Usuarios Servidos:              180,000+
🔌 APIs Desarrolladas:             400+
🗄️ Tablas de BD Diseñadas:        100+
🔗 Integraciones Externas:         30+
📊 Registros Procesados/Día:      206,000+
💳 Transacciones/Mes:             180,000+
📧 Emails Enviados/Mes:           1,200,000+
⚡ Uptime Promedio:                99.7%
🧪 Cobertura de Testing:          85%+
🚀 Mejora de Rendimiento:         200x
📉 Reducción de Incidencias:      60%
💰 Reducción de Costos:           40-65%
```

---

## 🎯 Áreas de Expertise

### Architecture & Design
- ✅ Microservices Architecture
- ✅ Event-Driven Systems
- ✅ API-First Design
- ✅ Legacy System Modernization
- ✅ Multi-Tenant Platforms
- ✅ Scalable Infrastructure

### Integration & Middleware
- ✅ REST & SOAP Services
- ✅ Payment Gateway Integration
- ✅ SSO/OAuth 2.0/Social Auth
- ✅ Legacy System Integration
- ✅ Message Queues (Bull/Redis)
- ✅ Circuit Breaker Patterns

### Data Engineering
- ✅ ETL Pipeline Development
- ✅ PySpark/Big Data Processing
- ✅ Delta Lake & Unity Catalog
- ✅ Data Orchestration
- ✅ Real-time Data Processing

### DevOps & Operations
- ✅ CI/CD Pipeline Implementation
- ✅ Docker & Kubernetes (AKS)
- ✅ Monitoring & APM
- ✅ Infrastructure as Code
- ✅ Zero-Downtime Deployments

---

## 🏆 Logros Destacados

🥇 **Migración exitosa** de arquitectura monolítica legacy con **mejora de 200x** en rendimiento

🥇 **Reducción del 60%** en incidencias de producción mediante refactorización completa

🥇 **99.7% uptime** mantenido en **15+ sistemas** críticos durante 18 meses

🥇 **Retención de clientes mejorada** del 67% al 84% mediante sistema de fidelización

🥇 **Automatización completa** de pipeline normativo reduciendo 8 horas de trabajo manual a 24 minutos

🥇 **Plataforma multi-tenant** reduciendo costos de mantenimiento en 65%

---

## 🚀 Proyecto Personal: FUBIX SaaS

### 💼 Co-Fundador | LegalTech Startup (2024 - Presente)

Startup tecnológica enfocada en soluciones SaaS para el sector legal en Colombia.

**VERIDIC**: Plataforma de gestión de casos jurídicos con:
- Integración a portales gubernamentales colombianos
- Procesamiento inteligente de documentos legales
- Gestión de expedientes y seguimiento de procesos
- Dashboard analítico para estudios jurídicos

**Mi rol**:
- Arquitectura técnica completa del MVP
- Modelado financiero y proyecciones
- Planificación estratégica y roadmap de producto
- Desarrollo del stack tecnológico inicial

---

## 📚 Educación

🎓 **Ingeniería de Sistemas** (Décimo semestre - Graduación: Junio 2026)  
Corporación Unificada Nacional de Educación Superior (CUN) | Colombia  
*Especialización*: Telecomunicaciones, Redes Empresariales, Fibra Óptica, Gerencia de Proyectos TI

🎓 **Tecnólogo en Análisis y Desarrollo de Sistemas de Información**  
Servicio Nacional de Aprendizaje (SENA) | Colombia

---

## 🌐 Idiomas

🇪🇸 **Español**: Nativo  
🇺🇸 **Inglés**: Técnico avanzado (lectura/escritura), conversacional básico

---

## 📫 Contacto & Portfolio

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/julian-urueña-pineda-118b52166)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:julian15uru@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JulianUP)
[![Download CV](https://img.shields.io/badge/📄_Download_my_CV-PDF-red?style=for-the-badge)](https://github.com/JulianUP/JulianUP/blob/main/CV_Julian_Uruena.pdf)

</div>

### 🎯 Abierto a oportunidades como:
- Senior Full Stack Developer
- Backend Engineer (Node.js/NestJS)
- Data Engineer (Azure/PySpark)
- Tech Lead / Engineering Manager

---

## 💡 Filosofía de Trabajo

> "Código limpio, arquitectura sólida, resultados medibles. No solo construyo sistemas, resuelvo problemas de negocio con tecnología."

**Principios**:
- ✅ **Testing es no negociable**: 85%+ coverage en todos mis proyectos
- ✅ **Documentación como código**: APIs documentadas con Swagger/OpenAPI
- ✅ **Monitoreo proactivo**: APM, logging centralizado, alertas automáticas
- ✅ **Code reviews rigurosos**: Calidad antes que velocidad
- ✅ **Deployment continuo**: CI/CD automatizado, zero-downtime deployments

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=JulianUP&show_icons=true&theme=radical&hide_border=true&include_all_commits=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=JulianUP&layout=compact&theme=radical&hide_border=true)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=JulianUP&theme=radical&hide_border=true)

</div>

---

<div align="center">

### 💼 Construyendo el futuro, un commit a la vez

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=JulianUP.JulianUP)

**© 2026 Julian Urueña Pineda**

</div>
