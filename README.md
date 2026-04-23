Proyecto Semestral: 777
Integrantes: Nicolas Ortega, Jairo Cid, Anita Olivares
#### Estado del Sistema (Hito 1)
| Microservicio | Puerto | DB Name | Funcionalidad |
| :--- | :--- | :--- | :--- |
| Módulo de Registro | 8080 | universidad_backend | CRUD de usuarios |
| Módulo de Catálogo | 8081 | universidad_backend | CRUD de Productos (Prendas) |
| Módulo de Carrito | 8084 | universidad_backend | CRUD de itemcarrito |

#### Despliegue Técnico
Instancia: AWS EC2 t3.large (Ubuntu 24.04)
Comando de inicio: docker compose up -d
