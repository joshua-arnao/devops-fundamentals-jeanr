# CI | CD 
## CONTINUOS INTEGRATION - CI
consiste en revisar automáticamente cada cambio que se sube a Git. El sistema compila el código, ejecuta pruebas, analiza su calidad y avisa rápido si algo falla

```
Developer
    ↓
Git Push
    ↓
CI Pipeline
    ├── Compilar
    ├── Ejecutar pruebas
    ├── Revisar calidad
    └── Validar código
```

## CONTINUOS DELIVERY | CONTINUOS DEPLOY - CD
- CD — Entrega Continua deja el software siempre listo para publicarse, aunque todavía necesita una aprobación manual antes de llegar a producción
- CD — Despliegue Continuo va un paso más allá: si todas las pruebas pasan, el código se publica automáticamente sin intervención humana.

```
Código
   ↓
Build
   ↓
Tests
   ↓
Deploy
```



```
DIAGRAMA COMPLETO CI/CD


                                  ┌─────────────────┐           ┌─────────────────┐
                                  │       CI        │           │       CD        │
                                  ├─────────────────┤           ├─────────────────┤
                                  │ Build           │           │ Package         │
  Developer   →   Git Push   →    │ Unit Tests      │      →    │ Deploy          │    →    Producción
                                  │ Quality Checks  │           │ Verification    │
                                  │ Security Scans  │           └─────────────────┘
                                  └─────────────────┘


```
