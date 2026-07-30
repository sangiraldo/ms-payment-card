# ms-payment-card

Microservicio para administrar pagos de tarjeta.

## Overview

Este servicio gestiona el procesamiento de pagos con tarjeta de crédito y débito.

## Endpoints

| Método | Path | Descripción |
|--------|------|-------------|
| GET | /health | Health check |
| POST | /payments | Crear un pago |
| GET | /payments/:id | Consultar un pago |

## Stack

- NestJS 10
- TypeScript
- Node.js 20
