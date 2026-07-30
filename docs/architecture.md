# Arquitectura

## Diagrama de componentes

```
[API Gateway] → [ms-payment-card] → [Database]
                       ↓
              [Queue: notifications]
```

## Dependencias

- **Database:** PostgreSQL
- **Queue:** SQS para notificaciones
- **Upstream:** API Gateway
- **Downstream:** ms-notifications
