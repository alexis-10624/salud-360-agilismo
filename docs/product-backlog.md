Product Backlog - Salud 360
1. Visión del Producto
Salud 360 es un sistema integral de atención en salud enfocado en facilitar el agendamiento de citas, trámites administrativos, consulta de resultados clínicos, pagos digitales y soporte al paciente mediante una interfaz accesible y simplificada.

2. Definición de Escalas de Trabajo
Prioridades

Alta: Funcionalidades críticas y esenciales para el uso básico del sistema.
Media: Funcionalidades de apoyo que enriquecen la experiencia del usuario.
Baja: Funcionalidades complementarias o simulaciones secundarias.

Estimación (Puntos de Historia )
1 - 2 Puntos: Tareas muy sencillas, vistas estáticas o formularios básicos sin validación compleja.
3 - 5 Puntos: Formularios con componentes interactivos, modales, tablas dinámicas de datos o integración con descargas/archivos.
8+ Puntos: Lógica avanzada de negocio o integraciones complejas.

Estados
1-Por hacer (To Do)
2-En progreso (In Progress)
3-Hecho (Done)

3. Product Backlog Detallado

ÉPICA 1: Gestión Asistencial (Citas)
Responsable: Alexis Restrepo Sánchez
HU 1.1.1

Agendamiento Digital: Selección de especialidad y fecha.
Confirmación de Reserva: Mensaje con resumen de cita.Criterios de Aceptación:
HU 1.1.1: Incluir una lista desplegable (<select>) con opciones como "Medicina General" y "Especialistas". Selector de fecha interactivo y botón "Consultar/Agendar"

.
HU 1.1.2: 
Tras presionar "Agendar", desplegar tarjeta o modal con especialidad, fecha, hora y sede.
HU 1.2.1: 
Botón visual de "Cancelar" en cada cita. Cuadro de confirmación modal. Remoción de la entrada tras confirmar.
Cancelación de Citas: Lista de citas con opción de remover cupo.

ÉPICA 2: Acceso y Perfil (Gestión de Usuarios)
Responsable: Juan Pablo Ortiz Tabares

HU 2.1.1
Registro de Pacientes: Formulario de datos personales.
HU 2.2.1
Autenticación (Login): Ingreso con correo y contraseña.


Criterios de Aceptación:

HU 2.1.1: Campos de texto: Nombre, Documento, Correo y Teléfono. Botón de acción que dirija al inicio de sesión.
HU 2.2.1: Campos de correo y contraseña con validación de no vacíos. Redirección al Dashboard.

ÉPICA 3: Trámites Administrativos
Responsable: Cristian Seguro García

HU 3.1.1
Certificaciones: Descarga de certificado de afiliación PDF.
HU 3.2.1
Radicación de Órdenes: Carga de archivos para autorizaciones.

Criterios de Aceptación:

HU 3.1.1: Botón "Descargar Certificado". Apertura o descarga de archivo PDF estático de muestra.
HU 3.2.1: Input de tipo archivo compatible con PDF/Imagen. Indicador visual del nombre del archivo y botón de confirmación.

ÉPICA 4: Resultados e Historial Clínico
Responsable: Cristian Seguro García

HU 4.1.1
Consulta de Laboratorio: Lista de exámenes realizados.
HU 4.1.2
Visualización de Resultados: Apertura de reportes detallados.

Criterios de Aceptación:

HU 4.1.1: Tabla o lista de registros que muestre tipo de examen y fecha.
HU 4.1.2: Enlace "Ver resultado" por ítem. Visor sencillo o descarga directa del reporte.

ÉPICA 5: Pagos y Soporte
Responsables: Edison Arnessen Toro Aguirre / Juan Pablo Ortiz Tabares

HU 5.1.1
Recaudo Digital (Edison): Pago de cuota moderadora vía PSE.
HU 5.2.1
Calificación (Juan Pablo): Retroalimentación del servicio.

Criterios de Aceptación:

HU 5.1.1: Desglose del monto a pagar. Botón "Pagar con PSE" (Simulación). Modal de éxito tras transacción.
HU 5.2.1: Interfaz con sistema de 5 estrellas o iconos. Botón de envío con confirmación de recepción.

ÉPICA 6: Panel de Control (Dashboard)
Responsable: Edison Arnessen Toro Aguirre

HU 6.1.1
Visor del Afiliado: Nombre y estado de afiliación activo.
HU 6.2.1
Directorio de Atención: Sedes y teléfonos de urgencias.

Criterios de Aceptación:

HU 6.1.1: Saludo personalizado. Indicador gráfico de "Afiliado Activo". Accesos directos a funciones principales.
HU 6.2.1: Tarjetas informativas con direcciones y números de emergencia.

4. Resumen y Consolidado de Estimaciones
Estadísticas Generales
Total de Historias de Usuario: 13
Puntos de Historia Totales: 28 Puntos

Integrante
Historias Asignadas
Carga de Puntos
Juan Pablo Ortiz Tabares
3
5 Puntos
Alexis Restrepo Sánchez
3
8 Puntos
Cristian Seguro García
4
9 Puntos
Edison Arnessen Toro Aguirre
3
6 Puntos












