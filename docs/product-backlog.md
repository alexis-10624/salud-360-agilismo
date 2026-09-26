# Product Backlog - Salud 360

---

## 🎯 Visión del Producto
**Salud 360** es un sistema integral de atención en salud enfocado en facilitar el agendamiento de citas, trámites administrativos, consulta de resultados clínicos, pagos digitales y soporte al paciente mediante una interfaz accesible y simplificada.

---

## 📏 Definición de Escalas de Trabajo

### Prioridades
* **Alta:** Funcionalidades críticas y esenciales para el uso básico del sistema.
* **Media:** Funcionalidades de apoyo que enriquecen la experiencia del usuario.
* **Baja:** Funcionalidades complementarias o simulaciones secundarias.

### Estimación (Puntos de Historia)
* **1 - 2 Puntos:** Tareas muy sencillas, vistas estáticas o formularios básicos sin validación compleja.
* **3 - 5 Puntos:** Formularios con componentes interactivos, modales, tablas dinámicas de datos o integración con descargas/archivos.
* **8+ Puntos:** Lógica avanzada de negocio o integraciones complejas.

### Estados
1. **Por hacer** (*To Do*)
2. **En progreso** (*In Progress*)
3. **Hecho** (*Done*)

---

## 📋 Product Backlog Detallado

### ÉPICA 1: Gestión Asistencial (Citas)
* **Responsable:** Alexis Restrepo Sánchez

#### Historias de Usuario
* **HU 1.1.1: Agendamiento Digital**
  * **Descripción:** Selección de especialidad y fecha. Confirmación de reserva con mensaje y resumen de cita.
  * **Criterios de Aceptación:** 
    * Incluir una lista desplegable con opciones como *"Medicina General"* y *"Especialistas"*.
    * Selector de fecha interactivo y botón *"Consultar/Agendar"*.

* **HU 1.1.2:** 
  * **Descripción:** Visualización de la reserva agendada.
  * **Criterios de Aceptación:** 
    * Tras presionar *"Agendar"*, desplegar tarjeta o modal con especialidad, fecha, hora y sede.

* **HU 1.2.1: Cancelación de Citas**
  * **Descripción:** Lista de citas con opción de remover cupo.
  * **Criterios de Aceptación:** 
    * Botón visual de *"Cancelar"* en cada cita.
    * Cuadro de confirmación modal.
    * Remoción de la entrada tras confirmar.

---

### ÉPICA 2: Acceso y Perfil (Gestión de Usuarios)
* **Responsable:** Juan Pablo Ortiz Tabares

#### Historias de Usuario
* **HU 2.1.1: Registro de Pacientes**
  * **Descripción:** Formulario de datos personales.
  * **Criterios de Aceptación:** 
    * Campos de texto: Nombre, Documento, Correo y Teléfono.
    * Botón de acción que dirija al inicio de sesión.

* **HU 2.2.1: Autenticación (Login)**
  * **Descripción:** Ingreso con correo y contraseña.
  * **Criterios de Aceptación:** 
    * Campos de correo y contraseña con validación de no vacíos.
    * Redirección al Dashboard.

---

### ÉPICA 3: Trámites Administrativos
* **Responsable:** Cristian Seguro García

#### Historias de Usuario
* **HU 3.1.1: Certificaciones**
  * **Descripción:** Descarga de certificado de afiliación PDF.
  * **Criterios de Aceptación:** 
    * Botón *"Descargar Certificado"*.
    * Apertura o descarga de archivo PDF estático de muestra.

* **HU 3.2.1: Radicación de Órdenes**
  * **Descripción:** Carga de archivos para autorizaciones.
  * **Criterios de Aceptación:** 
    * Input de tipo archivo compatible con PDF/Imagen.
    * Indicador visual del nombre del archivo y botón de confirmación.

---

### ÉPICA 4: Resultados e Historial Clínico
* **Responsable:** Cristian Seguro García

#### Historias de Usuario
* **HU 4.1.1: Consulta de Laboratorio**
  * **Descripción:** Lista de exámenes realizados.
  * **Criterios de Aceptación:** 
    * Tabla o lista de registros que muestre tipo de examen y fecha.

* **HU 4.1.2: Visualización de Resultados**
  * **Descripción:** Apertura de reportes detallados.
  * **Criterios de Aceptación:** 
    * Enlace *"Ver resultado"* por ítem.
    * Visor sencillo o descarga directa del reporte.

---

### ÉPICA 5: Pagos y Soporte
* **Responsables:** Edison Arnessen Toro Aguirre / Juan Pablo Ortiz Tabares

#### Historias de Usuario
* **HU 5.1.1: Recaudo Digital** *(Responsable: Edison)*
  * **Descripción:** Pago de cuota moderadora vía PSE.
  * **Criterios de Aceptación:** 
    * Desglose del monto a pagar.
    * Botón *"Pagar con PSE"* (Simulación).
    * Modal de éxito tras transacción.

* **HU 5.2.1: Calificación** *(Responsable: Juan Pablo)*
  * **Descripción:** Retroalimentación del servicio.
  * **Criterios de Aceptación:** 
    * Interfaz con sistema de 5 estrellas o íconos.
    * Botón de envío con confirmación de recepción.

---

### ÉPICA 6: Panel de Control (Dashboard)
* **Responsable:** Edison Arnessen Toro Aguirre

#### Historias de Usuario
* **HU 6.1.1: Visor del Afiliado**
  * **Descripción:** Nombre y estado de afiliación activo.
  * **Criterios de Aceptación:** 
    * Saludo personalizado.
    * Indicador gráfico de *"Afiliado Activo"*.
    * Accesos directos a funciones principales.

* **HU 6.2.1: Directorio de Atención**
  * **Descripción:** Sedes y teléfonos de urgencias.
  * **Criterios de Aceptación:** 
    * Tarjetas informativas con direcciones y números de emergencia.

---

## 📊 Resumen y Consolidado de Estimaciones

### Estadísticas Generales
* **Total de Historias de Usuario:** 13
* **Puntos de Historia Totales:** 28 Puntos

### Carga de Historias Asignadas por Integrante

| Integrante | Historias Asignadas | Carga de Puntos |
| :--- | :---: | :---: |
| **Juan Pablo Ortiz Tabares** | 3 | 5 Puntos |
| **Alexis Restrepo Sánchez** | 3 | 8 Puntos |
| **Cristian Seguro García** | 4 | 9 Puntos |
| **Edison Arnessen Toro Aguirre** | 3 | 6 Puntos |



