# SEMATIC VERSIONING - SemVer
Convención para asignar números de versión al software de forma que **el número de versión comunique qué tipo de cambio se realizó**.

## Estrucutra de la versión
```
MAJOR.MINOR.PATCH

  2  .  4  .  1
  ↑     ↑     ↑
MAJOR MINOR PATCH
```

### Major
El **MAJOR** cambia cuando realizas cambios **incompatibles** con versiones anteriores de la interfaz pública.

`1.5.2 → 2.0.0`

### Minor
**MINOR** aumenta cuando agregas nueva funcionalidad de manera **compatible con versiones anteriores**.


`1.2.0 → 1.3.0`

### Patch
**PATCH** aumenta cuando realizas una **corrección compatible**, como solucionar un bug.

`1.3.0 → 1.3.1`


## Resumen visual

```
        3.7.4
        │ │ │
        │ │ └── PATCH → Correcciones
        │ │
        │ └──── MINOR → Nueva funcionalidad compatible
        │
        └────── MAJOR → Cambio incompatible
```
