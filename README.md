
// insertar un ejemplo de como se puede usar el sistema en el readme
### Ejemplo de Uso del Sistema

El sistema puede ser utilizado de la siguiente manera:

1. **Iniciar Sesión**: El usuario inicia sesión en el sistema utilizando su nombre de usuario y contraseña.
2. **Crear Proyecto**: El usuario crea un nuevo proyecto, especificando el nombre del proyecto, la descripción y los objetivos.
3. **Agregar Tareas**: El usuario agrega tareas al proyecto, especificando la descripción, la fecha de inicio y la fecha de vencimiento.
4. **Asignar Tareas**: El usuario asigna tareas a los miembros del equipo, especificando el nombre del miembro y la fecha de entrega.
5. **Seguimiento**: El usuario puede seguir el progreso de las tareas y proyectos en tiempo real, utilizando gráficos y tablas de estadísticas.

### Código de Ejemplo

```markdown
# Iniciar Sesión
```bash
$ login -u usuario -p contraseña
```

# Crear Proyecto
```bash
$ crear-proyecto -n "Mi Proyecto" -d "Este es un ejemplo de proyecto"
```

# Agregar Tarea
```bash
$ agregar-tarea -p "Mi Proyecto" -d "Esta es una tarea de ejemplo" -i 2023-01-01 -v 2023-01-31
```

# Asignar Tarea
```bash
$ asignar-tarea -p "Mi Proyecto" -t "Esta es una tarea de ejemplo" -m "Juan Pérez" -e 2023-01-15
```

# Seguimiento
```bash
$ seguimiento -p "Mi Proyecto"
```
```