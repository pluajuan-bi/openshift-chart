# Helm Chart Full Stack para OpenShift

Este chart despliega:
- Backend
- Frontend
- Base de datos PostgreSQL

## Instalación
```bash
helm install mi-app ./openshift-full-stack-chart
```

## Personalización
Edita `values.yaml` para configurar imágenes, rutas, credenciales y recursos.

## Ejemplo de credenciales PostgreSQL
```yaml
database:
  credentials:
    user: "admin"
    password: "superseguro"
    name: "openshift-db"
```
