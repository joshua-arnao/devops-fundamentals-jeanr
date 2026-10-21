# DEPLOYMENT STRATEGIES
Lllevar una aplicación a producción minimizando riesgos e interrupciones.

## 1. BLUE/GREEN DEPLOYMENT
Mantiene dos ambientes:
- Blue: Versión Actual
- Green: Versión nueva

Consiste en redirecciona rel tráfico a la **nueva versión**

### VENTAJAS
- Rollback muy rápido.
- Casi cero downtime.
- Validación previa del entorno nuevo.

### DESVENTAJAS
- Más costo.
- Manejar dos ambientes completos.

## 2. CANARY DEPLOYMENT
La nueva versión se entrega primero a un grupo pequeño de usuarios.

### VENTAJAS
- Riesgo muy bajo.
- Detección temprana de errores.
- Excelente experiencia para el usuario.

### DESVENTAJAS
- Más complejidad.
- Requiere observabilidad.

## 3. ROLLING UPDATE
Se van remplazando instancias poco a poco hasta tener el 100% de las instacias con la nueva versión.

### VENTAJAS
- No necesitas duplicar infraestructura.
- Downtime mínimo.
- Muy simple.

### DESVENTAJAS
- Rollback más lento.
- Temporalmente conviven dos versiones.

## 4. INCREMENTAL
La nueva versión se van liberando por etapas las funcionaolidades o componentes.

### VENTAJAS
- Menos riesgo por cambio
- Lanzamientos graduales
