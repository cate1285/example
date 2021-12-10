---
sidebar_label: 'Api 1!'
sidebar_position: 3
---


# Servicios


Crea un nuevo usuario.

Request (API)  https://api-nki-staging.technoapes.io/auth/users/create/

| Metodo      |              Acción                 |
|-------------|:-----------------------------------:|
| HEAD        |   Obtener información de recursos   |
| GET         |          Obtener recursos           |
| POST        |           Crear recursos            |
| PUT         | Actualizar completamente un recurso |
| PATCH       | Actualizar parcialmente un recurso  |
| DELETE      |         Eliminar un recurso         |


| Clave           |  Tipo  | Longitud Max. | Valor Defecto | Requerido | Descripcion |
|-----------------|:------:|--------------:|---------------|-----------|-------------|
| id              |  Int   |             3 | -             | Si        |             |
| service_id      |  Int   |            -- | -             | Si        |             |
| type_id         | Float  |            -- | -             | Si        |             |
| customer_id     |  Int   |            -- | -             | Si        |             |
| dimensions      |  ----  |            -- | -             | Si        |             |
| unit_dimensions | String |             4 | -             | Si        |             |
| weight          |  Int   |             4 | -             | Si        |             |
| unit_weight     | String |             4 | -             | Si        |             |
| properties      |  ----  |            -- | -             | Si        |             |
