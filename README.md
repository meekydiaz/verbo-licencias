# Verbo · registro de licencias

Este repositorio lo consulta el plugin **Verbo** para DaVinci Resolve y comprueba si una clave de licencia es válida.

- `l/<sha256 de la clave>.json`: estado de cada licencia (`active` o `revoked`), plan y caducidad.
- Aquí no hay claves ni datos de clientes: solo el hash SHA-256 de cada clave, y a partir de él no se puede reconstruir la clave.
- Las licencias se crean y se revocan con el generador privado, nunca a mano.
