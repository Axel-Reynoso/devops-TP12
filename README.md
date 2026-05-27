<div align="center">
# DevOps Portfolio — Path Operaciones1 [cite: 10]

[![Licencia MIT](https://img.shields.io/badge/licencia-MIT-green.svg)](LICENSE) [cite: 12]
[![Hecho con](https://img.shields.io/badge/hecho%20con-Killercoda%20%2B%20KodeKloud-blue.svg)](https://killercoda.com) [cite: 13]
</div>

---

## Sobre este portfolio
Aprendí DevOps desde cero en Operaciones1 usando únicamente herramientas gratuitas[cite: 17]. Cada TP tiene un entregable concreto en GitHub que demuestra lo aprendido en práctica[cite: 18].

---

## Stack tecnológico [cite: 20]
| Categoría | Herramientas | [cite: 21, 22]
|---|---| [cite: 23]
| **OS / Scripting** | Linux (Ubuntu), Bash | [cite: 24, 25]
| **Control de versiones** | Git, GitHub, Gitflow | [cite: 26]
| **Contenedores** | Docker, Docker Compose | [cite: 27, 28]
| **CI/CD** | GitHub Actions | [cite: 29, 30]
| **Monitoreo** | Prometheus, Grafana, cAdvisor | [cite: 31]
| **Orquestación** | Kubernetes (kubectl, Helm) | [cite: 32]
| **IaC** | Terraform (provider Docker) | [cite: 33, 34]
| **Backend** | Python, Flask, Gunicorn | [cite: 35, 36]
| **Base de datos** | PostgreSQL | [cite: 37, 38]
| **Proxy / Frontend** | Nginx | [cite: 39]
| **Config** | YAML, HCL, JSON | [cite: 40, 41]

---

## Proyectos por TP [cite: 43]

### Mes 1 — Fundamentos [cite: 159]
| TP | Proyecto | Tecnologías | Link | [cite: 45]
|---|---|---|---| [cite: 46]
| 1 | Script de automatización del sistema | Bash, cron | [→ ver repo](https://github.com/Axel-Reynoso/devops-TP01) | [cite: 47]
| 2 | Gestión de usuarios y permisos | Linux, chmod, useradd | [→ ver repo](https://github.com/Axel-Reynoso/devops-TP02) | [cite: 48]
| 3 | Flujo Gitflow completo | Git, GitHub, branching | [→ ver repo](https://github.com/Axel-Reynoso/devops-TP03) | [cite: 49]
| 4 | YAML multi-entorno + diagnóstico de red | YAML, bash, ping, dig, curl | [→ ver repo](https://github.com/Axel-Reynoso/devops-TP04) | [cite: 50]

### Mes 2 — Contenedores y CI/CD [cite: 160]
| TP | Proyecto | Tecnologías | Link | [cite: 52]
|---|---|---|---| [cite: 53]
| 5 | API Python en Docker | Docker, Flask, Gunicorn | [→ ver repo](https://github.com/Axel-Reynoso/devops-TP05) | [cite: 54]
| 6 | App multi-contenedor | Docker Compose, Postgres, Nginx | [→ ver repo](https://github.com/Axel-Reynoso/devops-TP06) | [cite: 55]
| 7 | Pipeline CI/CD completo | GitHub Actions, pytest, Docker Hub | [→ ver repo](https://github.com/Axel-Reynoso/devops-TP06) | [cite: 56]
| 8 | Stack de monitoreo | Prometheus, Grafana, Node Exporter | [→ ver repo](https://github.com/Axel-Reynoso/devops-TP08) | [cite: 57]

### Mes 3 — Kubernetes e IaC [cite: 161]
| TP | Proyecto | Tecnologías | Link | [cite: 59]
|---|---|---|---| [cite: 60]
| 9 | App en Kubernetes | kubectl, Pods, Deployments, Services | [→ ver repo](https://github.com/Axel-Reynoso/devops-TP09) | [cite: 61]
| 10 | Helm Chart + Ingress | Helm, Ingress NGINX, HPA | [→ ver repo](https://github.com/Axel-Reynoso/devops-TP10) | [cite: 62]
| 11 | Infraestructura como Código | Terraform, módulos, state | [→ ver repo](https://github.com/Axel-Reynoso/devops-TP11) | [cite: 63]
| 12 | Portfolio final | GitHub Actions, integración | [→ este repo](https://github.com/Axel-Reynoso/devops-portfolio) | [cite: 64]

---

## Proyecto integrador: Notes App [cite: 66]
La app que construí TP a TP terminó siendo una aplicación real de notas con todo el stack DevOps aplicado[cite: 67, 68]:

`Código → GitHub Actions (CI) → Docker Hub → Kubernetes (CD) ↓ Prometheus + Grafana (monitoreo en tiempo real)` [cite: 69]

**Repo principal:** [devops-TP06](https://github.com/Axel-Reynoso/devops-TP06) [cite: 70]

---

## Cómo ver cada proyecto [cite: 72]
Cada repo tiene: [cite: 73]
- `README.md` con explicación del proyecto y comandos para correrlo [cite: 74]
- `scripts/verificar.sh` para confirmar que todo funciona [cite: 75]
- Entregable funcional que podés levantar con un solo comando [cite: 76]

---

## Plataformas usadas (todas gratuitas) [cite: 78]
- **[Killercoda](https://killercoda.com)** — labs con terminal real en el navegador [cite: 79]
- **[KodeKloud](https://kodekloud.com)** — cursos estructurados con videos [cite: 80]
- **[roadmap.sh/devops](https://roadmap.sh/devops)** — guía de qué aprender [cite: 81]
- **[GitHub](https://github.com)** — CI/CD con Actions (minutos gratis) [cite: 82]
- **[Docker Hub](https://hub.docker.com)** — registry de imágenes (plan free) [cite: 83]
