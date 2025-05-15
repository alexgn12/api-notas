# API de Notas Seguras

API RESTful construida con Node.js y Express. Permite registrar usuarios, iniciar sesión, y gestionar notas personales protegidas por JWT. Los datos se almacenan de forma persistente en archivos `.json`.

---

## Tecnologías utilizadas

- Node.js + Express
- JSON Web Tokens (JWT)
- Bcrypt (hash de contraseñas)
- express-validator (validación de datos)
- Persistencia en archivos (`fs`)
- Arquitectura modular

---

| Método | Ruta            | Descripción                |
| ------ | --------------- | -------------------------- |
| POST   | /usuarios       | Registro de usuario        |
| POST   | /usuarios/login | Login y obtención de token |
| GET    | /notas          | Obtener tus notas          |
| POST   | /notas          | Crear nueva nota           |
| PATCH  | /notas/\:id     | Editar tu nota             |
| DELETE | /notas/\:id     | Eliminar tu nota           |
