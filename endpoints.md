# Endpoints REST - UCA-CFC Connect

## Módulo de Autenticación

| Método | Endpoint | Descripción | Roles |
|--------|----------|-------------|-------|
| POST | /api/auth/login | Iniciar sesión | Todos |
| POST | /api/auth/logout | Cerrar sesión | Todos |
| POST | /api/auth/register | Registro de usuario | Público |
| POST | /api/auth/recover-password | Recuperar contraseña | Público |

## Módulo 1: Gestión Académica

| Método | Endpoint | Descripción | Roles |
|--------|----------|-------------|-------|
| GET | /api/cursos | Listar cursos | Todos |
| GET | /api/cursos/{id} | Obtener curso | Todos |
| POST | /api/cursos | Crear curso | ADMIN |
| PUT | /api/cursos/{id} | Actualizar curso | ADMIN |
| DELETE | /api/cursos/{id} | Eliminar curso | ADMIN |
| PATCH | /api/cursos/{id}/activate | Activar/Inactivar | ADMIN |

... y así con todos los módulos
