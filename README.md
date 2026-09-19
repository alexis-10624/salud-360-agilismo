# salud-360-agilismo
# Salud 360 🏥

**Salud 360** es una plataforma web orientada a simplificar y digitalizar el acceso a servicios asistenciales, trámites administrativos y gestión de pacientes dentro del sistema de salud.

---

## 📌 ¿Qué problema resuelve el proyecto?
En muchos sistemas de salud, la gestión de citas médicas, obtención de certificados, consulta de exámenes y pagos requiere desplazamientos físicos o el uso de plataformas fragmentadas e intuitivamente complejas. **Salud 360** unifica y centraliza estas funcionalidades en una interfaz accesible, clara y eficiente para el usuario.

---

## 🚀 Producto en Desarrollo
El proyecto consiste en una aplicación web interactiva que permite a los afiliados:
* Agendar y cancelar citas médicas presenciales o virtuales.
* Consultar y descargar resultados de exámenes de laboratorio en PDF.
* Descargar certificados de afiliación en línea[cite: 1].
* Radicar órdenes médicas mediante la subida de archivos[cite: 1].
* Realizar simulaciones de pago digital para cuotas moderadoras (PSE)[cite: 1].
* Visualizar un panel principal (Dashboard) con el estado de su cuenta y directorio de sedes/urgencias[cite: 1].
* Evaluar la calidad de la atención recibida mediante módulos de calificación[cite: 1].

---

## 👥 Equipo de Trabajo

| Integrante | Rol / Módulo Principal |
| :--- | :--- |
| **Juan Pablo Ortiz Tabares**[cite: 1] | Acceso y Perfil (Registro, Login) y Calificación del Servicio[cite: 1] |
| **Alexis Restrepo Sanchez**[cite: 1] | Gestión Asistencial (Agendamiento y Cancelación de Citas)[cite: 1] |
| **Cristian Seguro Garcia**[cite: 1] | Trámites Administrativos (Certificados, Órdenes) y Resultados Clínicos[cite: 1] |
| **Edison Arnesse Toro Aguirre**[cite: 1] | Panel de Control (Dashboard), Directorio y Recaudo Digital (PSE)[cite: 1] |

---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura semántica de las vistas y formularios web[cite: 1].
* **CSS3 / Bootstrap:** Estilizado, diseño responsivo y maquetación visual[cite: 1].
* **JavaScript (Vanilla):** Interactividad, simulación de estados y manejo de eventos DOM[cite: 1].
* **Git & GitHub:** Control de versiones, colaboración por ramas y despliegue continuo mediante GitHub Pages[cite: 1].

---

## 📁 Organización del Repositorio

La estructura de carpetas y archivos dentro del repositorio se organiza de la siguiente manera:

```text
salud-360/
├── index.html            # Pantalla de inicio de sesión o bienvenida principal[cite: 1]
├── css/                  # Hojas de estilo globales y por módulo
├── js/                   # Scripts de interactividad y validaciones
├── assets/               # Imágenes, íconos y documentos PDF de prueba
├── views/                # Vistas HTML secundarias del proyecto
│   ├── registro.html     # Módulo de registro de usuarios[cite: 1]
│   ├── citas.html        # Módulo de agendamiento y cancelación[cite: 1]
│   ├── tramites.html     # Certificados y radicación de órdenes[cite: 1]
│   ├── resultados.html   # Consulta de laboratorio[cite: 1]
│   ├── dashboard.html    # Panel principal del afiliado y directorio[cite: 1]
│   └── pagos.html        # Simulación de pagos PSE[cite: 1]
└── README.md             # Documentación principal del proyecto
