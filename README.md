# 🎬 Proyecto DevSecOps Completo — Clon de Netflix

Un proyecto **completo de DevSecOps de punta a punta** que muestra cómo automatizar, asegurar y monitorear infraestructura y aplicaciones usando herramientas modernas — desde **Terraform hasta Kubernetes**, **Jenkins hasta Trivy**, y todo lo que hay en el medio.

Construido para demostrar **flujos de trabajo DevSecOps del mundo real** para CI/CD, automatización en la nube, integración de seguridad y observabilidad — todo en una aplicación temática de Netflix. 🍿

---

## 🚀 Descripción del Proyecto

Este proyecto simula una configuración real de nivel empresarial donde un **Clon de Netflix basado en React** es desplegado y gestionado a través de un **pipeline DevOps seguro y automatizado**.

### 🌐 Características Principales
- **Infraestructura como Código** con Terraform (aprovisionamiento en AWS)
- **Gestión de estado** usando Terraform Cloud
- **Automatización CI/CD** con GitHub Actions y Jenkins
- **Escaneo de Seguridad** con Trivy y OWASP Dependency Check
- **Contenerización** con Docker
- **Despliegue en Kubernetes** (configuración de cluster no administrado)
- **Stack de Monitoreo** para Jenkins, Kubernetes y la propia aplicación

---

## 🧩 Estructura de Directorios
```bash
.
├── Application-Code        # App frontend Clon de Netflix construida con React + Vite
│   ├── Dockerfile           # Instrucciones de construcción de imagen Docker
│   ├── package.json         # Dependencias y scripts
│   ├── src/                 # Código fuente principal
│   └── public/              # Archivos estáticos
│
├── Jenkins
│   └── Jenkinsfile          # Configuración del pipeline CI/CD (build → test → deploy)
│
├── Kubernetes
│   ├── deployment.yml       # Manifiesto de despliegue de la app
│   └── service.yml          # Exposición del servicio K8s
│
└── Terraform
    ├── main.tf              # Definiciones de recursos AWS
    ├── backend.tf           # Configuración del backend en Terraform Cloud
    ├── iam.tf               # Roles y políticas IAM
    ├── vpc.tf               # Configuración de red
    ├── variables.tf         # Variables de entrada
    ├── dev.auto.tfvars      # Variables de entorno
    └── gather.tf            # Fuentes de datos y dependencias
```

---

## 🛠️ Stack Tecnológico

| Categoría | Herramientas / Tecnologías |
|-----------|----------------------------|
| **Infraestructura** | Terraform, AWS EC2, Terraform Cloud |
| **CI/CD** | Jenkins, GitHub Actions |
| **Seguridad** | Trivy, SonarQube, OWASP Dependency Check |
| **Contenerización** | Docker |
| **Orquestación** | Kubernetes (Cluster No Administrado) |
| **Monitoreo** | Node Exporter, Prometheus, Kube State Metrics |
| **Frontend** | React, Vite, TMDB API |

---

## 🎯 Objetivos

1. Automatizar todo el ciclo de vida de despliegue de infraestructura y aplicación
2. Integrar controles de seguridad y calidad temprano en el pipeline
3. Establecer un sistema completamente observable y monitoreado para garantizar confiabilidad
4. Mostrar un flujo de trabajo DevSecOps de punta a punta — ideal para portafolio y entrevistas

---

## 📽️ ¿Cómo realizar este Proyecto?

> Este proyecto está documentado a través de una **Serie de 5 Partes en YouTube**, cada una construyendo sobre la anterior.

|-------|--------|-------------|
| 🧩 **Parte 1** | *Terraform + GitHub Actions + Configuración AWS* | Configuración y automatización de infraestructura |
| ⚙️ **Parte 2** | *Jenkins, Docker, SonarQube, Trivy - Configuración* | Bases del pipeline CI/CD principal |
| 🧠 **Parte 3** | *SonarQube + Trivy + TMDB + Ejecución del Pipeline* | Ejecución de pipelines seguros |
| ☸️ **Parte 4** | *Configuración del Cluster Kubernetes + Despliegue* | Despliegue completo de la app en K8s |
| 📊 **Parte 5** | *Configuración del Monitoreo* | Observabilidad de punta a punta |

## 🔔 Tip Extra

Si estás siguiendo el proyecto, no olvides:
- 🎥 **Ver la versión en video** para una guía paso a paso
- 💼 **Etiquetar a [@Aman Pathak](https://www.linkedin.com/in/aman-devops/)** en LinkedIn cuando publiques tu progreso — ¡mostrar tus logros en DevOps te ayuda a crecer profesionalmente!

---

## Contribuciones

¡Las contribuciones son bienvenidas! Si tienes ideas para mejoras o encuentras algún problema, por favor abre un pull request o crea un issue.

## Licencia

Este proyecto está licenciado bajo la [Licencia MIT](LICENSE).
