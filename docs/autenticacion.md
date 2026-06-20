# Autenticación

La API utiliza JWT.

## Login

```http
POST /api/auth/login
```

### Parámetros

| Campo | Tipo |
|--------|--------|
| email | string |
| password | string |

!!! note

    El token dura 24 horas.

Ir a [Endpoints](endpoints.md).