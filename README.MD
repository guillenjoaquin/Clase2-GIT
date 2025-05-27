# ACTIVIDAD INTERMEDIA  
## Git y herramientas para implementar el control de versiones en aplicaciones para desarrolladores/as  
**Joaquín Guillén**

---

### Diferencias entre Git y Subversion (SVN)

Estuve comparando Git con Subversion (SVN), que es otro sistema de control de versiones más viejo y centralizado. Algunas diferencias clave:

| Característica                  | Git                                       | Subversion (SVN)                         |
|--------------------------------|-------------------------------------------|------------------------------------------|
| Modelo                         | Distribuido: cada copia del repo es completa | Centralizado: dependés del servidor     |
| Trabajar sin conexión          | Podés hacer commits offline               | Necesitás conexión al servidor           |
| Velocidad                      | Mucho más rápido, todo corre localmente   | Más lento, depende del servidor          |
| Ramas                          | Crear ramas es rápido y liviano           | Crear ramas puede ser más costoso        |
| Curva de aprendizaje           | Más empinada, pero muy poderoso           | Más fácil de arrancar, pero limitado     |

Git es el que más se usa hoy en día, sobre todo por cómo maneja las ramas y por lo bien que se adapta a equipos distribuidos.

---

### GitHub vs GitLab

Después miré un poco las plataformas más comunes para trabajar con Git: GitHub y GitLab. Aunque parecen parecidas, tienen algunas diferencias importantes:

| Característica                  | GitHub                                  | GitLab                                    |
|--------------------------------|------------------------------------------|-------------------------------------------|
| Propiedad                      | De Microsoft                            | Open source, se puede auto-hostear       |
| CI/CD                          | Tiene GitHub Actions, pero hay que configurarlo | GitLab trae CI/CD muy integrado de fábrica |
| Gestión de tareas              | Tiene Projects, tipo Kanban              | Más completo para trabajo colaborativo     |
| Uso gratuito                   | Repos privados sin costo                 | También, y con más herramientas integradas |
| Enfoque                        | Mucho foco en comunidad open source      | Más orientado a empresas y DevOps         |

En mi caso, si tuviera que elegir, me inclinaría por GitLab para proyectos donde CI/CD y control más fino de permisos sean clave. Para open source o cosas más simples, GitHub sigue siendo excelente.

---
