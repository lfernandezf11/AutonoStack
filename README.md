# AutonoStack
Repositorio destinado a la generación de documentación y seguimiento del desarrollo de la asignatura Proyecto Intermodular de DAW.

## 📅 Cronograma de la asignatura

| Fecha | Hito / Actividad |
| :--- | :--- |
| **12 de septiembre** | Presentación de Asignatura y Proyecto |
| **19 de septiembre** | Creación de Imagen Corporativa de la Empresa |
| **26 de septiembre** | Elaboración de Contrato de Prestación de Servicios y Recogida de Necesidades |
| **03 de octubre** | Definición de Requisitos Funcionales y No Funcionales, y Presentación |
| **10 de octubre** | Desarrollo de las Interfaces Gráficas |
| **17 de octubre** | Desarrollo de la Estructura de la Base de Datos |
| **24 de octubre** | Definición de Modelo Relacional de la Base de Datos |
| **31 de octubre** | Presentación de Interfaces y Base de Datos a la Empresa |
| **07 de noviembre** | Elección de Tecnologías a Utilizar |
| **14 de noviembre** | Estructuración Inicial de Documentación |
| **21 de noviembre** | Definición de Puntos de los Manuales de Usuario y Técnico |
| **05 de diciembre** | Desarrollo Inicial de Manuales de Usuario y Técnico |
| **12 de diciembre** | Opciones de Despliegue de Aplicativos |
| **19 de diciembre** | Pruebas de Despliegue en Entorno Local (TomCat) |
| **09 de enero** | Pruebas de Despliegue en Vercel |

# AutonoStack - Sistema de Gestión Financiera y Dashboard Analítico 
## 📝 Resumen del Proyecto
AutonoStack es una plataforma web diseñada para centralizar la gestión de ingresos, gastos y previsiones económicas. Su objetivo es transformar el registro contable tradicional en una herramienta de análisis estratégico, permitiendo a los usuarios visualizar su salud financiera en tiempo real a través de un dashboard interactivo.

## 👥 ¿A quién se dirige?
La aplicación está dirigida específicamente a **profesionales autónomos e independientes** que requieren una soberanía total sobre su información financiera. Es ideal para aquellos que buscan una interfaz ágil y moderna para gestionar su facturación y analizar la rentabilidad de sus proyectos de forma individualizada.

## 💡 Justificación
La gestión financiera para autónomos suele ser fragmentada o excesivamente compleja. AutonoStack nace para resolver la falta de herramientas que combinen la simplicidad del registro diario con la potencia del análisis de datos. Se justifica en la necesidad de ofrecer:
* Un control exhaustivo de gastos desgravables.
* Trazabilidad completa por proyectos.
* Previsiones fiscales (IVA) automatizadas para evitar sorpresas en el cierre trimestral.
---

## 🔐 Matriz de Roles y Permisos

| Acción / Funcionalidad | Administrador | Autónomo | Invitado (Demo) |
| :--- | :---: | :---: | :---: |
| Registro e inicio de sesión | | ✓ | |
| Gestión de usuarios | ✓ | | |
| Supervisión técnica y auditoría | ✓ | | |
| Gestión de facturas y gastos (CRUD) | | ✓ | |
| Creación y gestión de proyectos | | ✓ | |
| Visualización del dashboard financiero | | ✓ | ✓ (Lectura) |
| Acceso a datos de ejemplo (Mock data) | | | ✓ |
| Generación de informes en PDF | | ✓ | |

---

## 🛠️ Stack Tecnológico (Medios Utilizados)

* **Lenguajes:** TypeScript (ES6+), SQL (PostgreSQL), HTML5, CSS3 y JSON.
* **Frameworks y Librerías:**
    * **Frontend:** React (SPA).
    * **Estilos:** Tailwind CSS.
    * **Backend as a Service:** Supabase (Auth, DB, Storage).
    * **Visualización:** Tremor / Recharts.
    * **Informes:** jsPDF.
* **Entorno de Desarrollo:**
    * IDE: Visual Studio Code.
    * Bundler: Vite.
    * Control de versiones: Git y GitHub
    
* **Despliegue:** Vercel.

---
**Participante:** Lucía Fernández Florencio
**Centro:** IES Albarregas, Mérida
