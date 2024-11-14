## README - Frontend

# Sistema de Turnos para Peluquería - Frontend

### Descripción del Proyecto

Este es el frontend del sistema de turnos para una peluquería. La interfaz permite a los usuarios navegar por la aplicación, registrarse, iniciar sesión y reservar turnos en los horarios disponibles. Incluye una experiencia de usuario (UX) intuitiva, con formularios amigables y navegación fluida para brindar la mejor experiencia posible.

---

### Funcionalidades de UX/UI

1. **Landing de Bienvenida**
   - Página introductoria que presenta la aplicación.

2. **Página Principal (Home)**
   - Información sobre el sistema de turnos y servicios.

3. **Barra de Navegación (Navbar) y Pie de Página (Footer)**
   - Componentes de navegación accesibles en todas las vistas de la aplicación.

4. **Formularios Amigables (Registro, Login, Reserva de Turno)**
   - **Validaciones**: 
      - Se muestran mensajes de error en tiempo real.
      - El botón de envío se habilita solo cuando el formulario está completo y es válido.
   - **Respuestas**:
      - No se reinicia el formulario al hacer clic.
      - Placeholder para guiar al usuario en los campos.
      - Filtrado de fechas inválidas.

5. **Restricciones de Reservas**
   - Desde el frontend, el botón de "Agendar Turno" queda deshabilitado si ya existe un turno reservado en el mismo horario.

---

### User Stories

#### Usuario Invitado
1. Ver información de la aplicación (Landing y Home).
2. Crear una cuenta (Registro): recibe un email de confirmación.

#### Usuario Registrado
1. Iniciar sesión / Cerrar sesión.
2. Reservar turno: recibe un email de confirmación.
3. Ver historial de turnos.
4. Cancelar turno (hasta un día antes de la cita).

---

### Configuración y Ejecución

1. Clonar el repositorio.
2. Instalar dependencias: 
   ```bash
   npm install
   ```
3. Ejecutar la aplicación en desarrollo: 
   ```bash
   npm run dev
   ```

---

### Tecnologías Utilizadas

- **React** para la interfaz de usuario.
- **CSS** y librerías de estilos para la personalización visual.
- **Axios** para las peticiones al backend.

---
