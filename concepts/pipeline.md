# PIPELINE
Un pipeline es una secuencia automatizada de pasos que se ejecutan para llevar código desde el desarrollo hasta el despliegue.


```
Código
  ↓
Build
  ↓
 Test
  ↓
Security Scan
  ↓
Package
  ↓
Deploy
  ↓
Producción
```


## PARA QUE SIRVE UN PIPELINE?
- Menos errores humanos
- Entregas más rápidas
- Mayor calidad
- Más automatización
- Retroalimentación rápida

## HERRAMIENTAS PARA CREAR PIPELINES
- Jenkins
- GitHub Actions
- GitLab
- Azure DevOps Pipelines
- Bitbucket Pipelines


## QUÉ ES UN WORKFLOW
Un workflow es el flujo completo de trabajo que define cuándo y cómo se ejecutan las tareas.

```
Workflow
│
├── Trigger: push a main
│
└── Jobs
    ├── Build
    ├── Test
    └── Deploy


Pipeline
│   
└── Build → Test → Deploy
```

Es decir un Workflow define:
- Cuándo se ejecuta
- Bajo que condiciones
- Qué pipeline ejecutar

Y un Pipeline define:
- Etapas que procesan el software

> En Jenkins se habla exclusivamente de pipeline pero en GitHub Actions se habal de workflos
