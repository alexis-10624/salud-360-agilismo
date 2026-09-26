# Sprint Backlog — Sprint 1

* **Capacidad del equipo:** ~45 horas
* **Objetivo del Sprint:** Construir la primera versión funcional (solo UI) de las pantallas principales de las 6 épicas priorizadas: Citas, Acceso y Perfil, Trámites Administrativos, Resultados e Historial, Pagos y Soporte, y Dashboard.
* **Nota:** Este archivo contiene solamente el trabajo de este Sprint. El backlog completo del producto sigue viviendo en un único archivo: `../../product-backlog.md`.

---

## 👤 Juan Pablo Ortiz Tabares — Registro, Acceso y Evaluaciones

### HU 2.1.1: Formulario de Registro Básico
* **Como** nuevo usuario del sistema de salud,
* **Quiero** un formulario de registro accesible e intuitivo,
* **Para** crear mi cuenta ingresando mis datos personales básicos y poder acceder a la plataforma digital.

#### Criterios de Aceptación:
1. El formulario debe solicitar campos obligatorios mínimos: Tipo de documento, Número de documento, Correo electrónico y Contraseña.
2. El sistema debe validar en tiempo real que el formato del correo electrónico sea válido y que la contraseña cumpla con los estándares de seguridad mínimos (ej. longitud y caracteres especiales).
3. Al enviar el formulario con datos correctos, el sistema debe registrar al usuario y mostrar un mensaje de éxito con la opción de iniciar sesión.
4. Si el documento o correo ya se encuentran registrados, el sistema debe mostrar un mensaje de error claro advirtiendo la situación.

---

### HU 2.2.1: Inicio de Sesión (Login)
* **Como** usuario registrado,
* **Quiero** ingresar mis credenciales en una pantalla de inicio de sesión,
* **Para** acceder de forma segura a mi perfil y a los servicios de salud disponibles.

#### Criterios de Aceptación:
1. La pantalla de login debe contener campos para Correo/Usuario y Contraseña, además de un botón de "Iniciar Sesión".
2. El sistema debe validar las credenciales ingresadas contra la base de datos de usuarios registrados.
3. Si las credenciales son incorrectas, se debe mostrar un mensaje de error genérico por seguridad (ej. "Usuario o contraseña inválidos").
4. Tras un inicio de sesión exitoso, el usuario debe ser redirigido automáticamente a su pantalla principal (Dashboard).

---

### HU 5.2.1: Formulario de Calificación del Servicio
* **Como** paciente que ha utilizado un servicio o atención,
* **Quiero** calificar mi experiencia a través de un formulario sencillo,
* **Para** aportar mi retroalimentación y ayudar a mejorar la calidad de la atención médica.

#### Criterios de Aceptación:
1. El formulario debe incluir una escala de calificación visual (ej. de 1 a 5 estrellas o emojis de satisfacción).
2. Debe opcionalmente incluir un campo de texto libre para comentarios o sugerencias detalladas sobre el servicio recibido.
3. Al pulsar el botón de "Enviar", el sistema debe almacenar la calificación asociada al usuario y mostrar un mensaje de agradecimiento.
4. El formulario no debe permitir el envío si no se ha seleccionado al menos una calificación cuantitativa (estrellas/escala).

---

## 👤 Alexis Restrepo Sánchez — Agendamiento de Citas

### HU 1.1.1: Selector de Especialidad y Fecha
* **Como** paciente que necesita atención médica,
* **Quiero** seleccionar la especialidad médica deseada y la fecha de disponibilidad mediante filtros interactivos,
* **Para** encontrar rápidamente los espacios de citas disponibles que se ajusten a mi tiempo.

#### Criterios de Aceptación:
1. La interfaz debe mostrar una lista desplegable o selector con las especialidades médicas disponibles.
2. Debe incluir un selector de fechas (calendario interactivo) que deshabilite los días pasados o sin agenda disponible.
3. Al seleccionar la especialidad y la fecha, el sistema debe actualizar y mostrar dinámicamente los horarios/médicos disponibles para ese día.
4. Si no existen horarios disponibles para los filtros seleccionados, el sistema debe mostrar un aviso indicando que no hay agenda abierta.

---

### HU 1.1.2: Confirmación y Mensaje de Cita Agendada
* **Como** paciente que ha seleccionado un horario,
* **Quiero** visualizar un resumen de la cita elegida y un mensaje de confirmación al finalizar el proceso,
* **Para** estar seguro de que mi cita médica quedó agendada correctamente.

#### Criterios de Aceptación:
1. Antes de confirmar, el sistema debe presentar una pantalla de resumen con los datos clave: Especialidad, Profesional, Fecha, Hora y Sede/Modalidad.
2. Al hacer clic en "Confirmar Cita", el sistema debe procesar el registro y mostrar un mensaje de éxito destacado ("¡Cita agendada con éxito!").
3. El mensaje de confirmación debe incluir los detalles esenciales de la cita y la opción de agregarla al calendario o regresar al inicio.
4. En caso de error de red o fallo en el sistema al guardar, debe mostrarse una alerta impidiendo la pérdida de la selección del usuario.

---

### HU 1.2.1: Botón para Cancelar Cita
* **Como** paciente que no podrá asistir a una cita programada,
* **Quiero** encontrar un botón visible para cancelar la cita,
* **Para** liberar el espacio y evitar penalizaciones o inasistencias en el sistema de salud.

#### Criterios de Aceptación:
1. En el detalle de cada cita programada en el historial del usuario, debe existir un botón claramente identificado como "Cancelar Cita".
2. Al hacer clic en el botón, el sistema debe desplegar una ventana de confirmación preguntando si está seguro de realizar la acción.
3. Tras confirmar la cancelación, el sistema debe actualizar el estado de la cita a "Cancelada" y mostrar un mensaje de éxito.
4. El horario liberado debe quedar disponible inmediatamente en el sistema para otros pacientes.

---

## 👤 Cristian Seguro García — Trámites, Certificados y Resultados

### HU 3.1.1: Botón de Descargar Certificado de Afiliación
* **Como** afiliado al sistema de salud,
* **Quiero** visualizar un botón de descarga para mi certificado de afiliación,
* **Para** obtener mi documento en formato digital y rápido sin necesidad de trámites presenciales.

#### Criterios de Aceptación:
1. El botón "Descargar Certificado de Afiliación" debe estar visible y accesible en la sección de perfil o trámites.
2. Al hacer clic, el sistema debe generar y descargar de forma automática el documento en formato PDF.
3. El documento descargado debe reflejar los datos actualizados del usuario (nombre, tipo de documento, estado de afiliación y fecha de expedición).
4. Si el servicio de generación falla o el usuario no posee una afiliación activa, se debe mostrar un mensaje de error claro y comprensible.

---

### HU 3.2.1: Vista para Cargar Orden Médica
* **Como** paciente,
* **Quiero** acceder a una interfaz intuitiva para cargar mi orden médica,
* **Para** solicitar la autorización o el agendamiento de mis servicios de salud de forma digital.

#### Criterios de Aceptación:
1. La vista debe contar con un botón o zona interactiva de arrastre (*drag and drop*) para adjuntar archivos desde el dispositivo en formatos permitidos (PDF, JPG, PNG).
2. Se debe mostrar una vista previa o el nombre del archivo seleccionado antes de confirmar el envío.
3. El sistema debe validar que el archivo seleccionado cumpla con el peso o tamaño máximo permitido.
4. Al presionar "Enviar", el sistema debe arrojar una notificación de éxito indicando que la orden médica fue recibida con éxito y se encuentra en revisión.

---

### HU 4.1.1 / 4.1.2: Lista de Resultados de Laboratorio
* **Como** paciente,
* **Quiero** visualizar una lista organizada con los resultados de mis exámenes de laboratorio,
* **Para** consultar el histórico y el estado actual de mis pruebas médicas de manera centralizada.

#### Criterios de Aceptación:
1. La interfaz debe presentar un listado ordenado cronológicamente de los exámenes de laboratorio realizados (del más reciente al más antiguo).
2. Cada elemento de la lista debe detallar: nombre del examen, fecha de realización y estado actual (ej. *Disponible*, *En proceso*).
3. Para los resultados con estado *Disponible*, debe existir un enlace o botón interactivo que permita ver el detalle o descargar el informe médico.
4. Si el usuario no cuenta con registros de laboratorio previos, la vista debe mostrar un mensaje amigable indicando la ausencia de resultados.

---

## 👤 Edisson Arnessen Toro Aguirre — Dashboard y Pagos Simples

### HU 6.1.1: Pantalla Principal (Dashboard de Afiliado)
* **Como** afiliado autenticado,
* **Quiero** visualizar una pantalla principal (Dashboard) con un resumen de mi información y accesos directos,
* **Para** navegar de forma rápida hacia mis citas pendientes, trámites y servicios más utilizados.

#### Criterios de Aceptación:
1. El Dashboard debe mostrar un saludo personalizado con el nombre del usuario y el estado actual de su afiliación.
2. Debe incluir accesos directos visuales (tarjetas o botones) hacia las secciones principales: Agendamiento de Citas, Resultados, Trámites y Pagos.
3. Se debe visualizar un resumen o tarjeta informativa con la próxima cita médica programada (si aplica).
4. La interfaz debe adaptarse correctamente a diferentes tamaños de pantalla (diseño responsivo).

---

### HU 6.2.1: Directorio de Sedes y Urgencias
* **Como** usuario que requiere asistencia presencial o de urgencia,
* **Quiero** consultar un directorio interactivo con las sedes de atención y puntos de urgencias disponibles,
* **Para** ubicar rápidamente la dirección, horarios y canales de contacto del centro médico más cercano.

#### Criterios de Aceptación:
1. La pantalla debe mostrar un listado o mapa con las diferentes sedes de la red de salud.
2. Cada sede debe detallar información clave: Nombre de la sede, dirección exacta, teléfonos de contacto y servicios específicos (ej. Urgencias 24 horas, laboratorio).
3. Debe incluir filtros o una barra de búsqueda por ubicación o tipo de servicio requerido.
4. Si una sede presenta cambios en sus horarios o estado de atención, la información mostrada debe reflejarlo claramente.

---

### HU 5.1.1: Pantalla Simulación de Pago (PSE)
* **Como** usuario que necesita realizar el pago de una cuota moderadora, copago o servicio complementario,
* **Quiero** acceder a una pantalla de simulación de pago mediante pasarela (PSE),
* **Para** completar transacciones financieras de manera simulada y segura dentro de la plataforma.

#### Criterios de Aceptación:
1. La interfaz debe mostrar el resumen del cobro a realizar (concepto, valor total y número de referencia).
2. Debe incluir una sección visual que simule los pasos típicos de una pasarela de pago PSE (selección de tipo de persona, banco y botón de continuar).
3. Al proceder con la simulación, el sistema debe procesar la transacción y mostrar una pantalla de comprobante de pago aprobado o rechazado según corresponda.
4. El comprobante generado debe incluir un número de transacción único y la opción de descargar el recibo en formato digital.

---

## 🔗 Referencias
* **Product Backlog completo:** `docs/product-backlog.md`
* **Historias de usuario detalladas:** `docs/user-stories.md`
