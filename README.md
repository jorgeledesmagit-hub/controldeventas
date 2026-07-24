# 📈 Sistema Control de Ventas

[![Licencia: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-7952B3.svg?style=flat&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![JS ES6](https://img.shields.io/badge/JavaScript-ES6-F7DF1E.svg?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![Portable](https://img.shields.io/badge/Version-Portable%20%28Serverless%29-blue)](https://github.com/)

Un sistema ligero, rápido y portable diseñado para registrar y controlar ventas de forma diaria, calcular comisiones por método de pago (tarjetas de crédito, débito, billeteras virtuales) y llevar un registro ordenado de pagos a proveedores. 

Dado que corre íntegramente en el navegador y utiliza `localStorage`, **no requiere conexión a internet, servidor web ni instalación de bases de datos**.

---

## 🚀 Características Principales

*   💼 **Registro de Ventas**: Carga rápida del monto, fecha y método de pago. El sistema calcula en tiempo real la comisión y el neto a recibir.
*   💳 **Gestión de Tarjetas y Métodos de Pago**: Administra diferentes tarjetas y comisiones asociadas (ej. Visa, Mastercard, Mercado Pago, Efectivo).
*   📊 **Visualización y Filtros**: Tabla interactiva con sumatorias totales de Bruto, Comisiones y Neto, con filtro por mes/año.
*   🚚 **Control de Proveedores**: Registra diferentes tipos de proveedores y lleva un historial detallado de los pagos realizados (monto, fecha y concepto).
*   🔒 **Acceso Administrador**: Panel de seguridad sencillo para restringir la modificación de métodos de pago y proveedores (contraseña almacenable en el navegador).
*   📥 **Exportar a CSV**: Descarga el reporte completo de tus ventas registradas en un archivo de Excel/CSV con un solo clic.
*   📦 **Totalmente Portable**: Dos archivos autónomos (`index.html` y `sistema_portable.html`) que puedes llevar en un pendrive y usar en cualquier computadora.

---

## 🛠️ Tecnologías Utilizadas

*   **Estructura y UI**: HTML5 & CSS3 con [Bootstrap 5.3](https://getbootstrap.com/) (Diseño responsivo para móviles y ordenadores).
*   **Interactividad**: JavaScript ES6 puro (Vanilla JS).
*   **Persistencia**: `localStorage` (los datos se guardan de forma persistente en tu navegador web y no se borran al cerrar la pestaña).

---

## 📋 Requisitos del Sistema

*   Cualquier navegador web moderno (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).
*   No requiere servidor Apache (XAMPP/Laragon) ni base de datos externa.

---

## ⚙️ Cómo Utilizar el Sistema

1.  **Descargar el Repositorio**
    Descarga o clona los archivos a tu computadora o pendrive.
2.  **Iniciar el Sistema**
    Haz doble clic en [index.html](file:///Applications/XAMPP/xamppfiles/htdocs/controldeventas/index.html) para abrir la aplicación de manera instantánea.
3.  **Configurar Métodos de Pago**
    *   Haz clic en **"Acceso Administrador"** en la esquina superior derecha.
    *   Usa la contraseña por defecto: `admin123`.
    *   Una vez dentro, podrás dar de alta tus tarjetas y comisiones personalizadas, así como también los tipos de proveedores.
4.  **Registrar Operaciones**
    Empieza a cargar tus ventas diarias y tus pagos a proveedores.

---

## 🔑 Credenciales por Defecto

*   **Contraseña de Administrador**: `admin123` *(se puede cambiar una vez iniciada la sesión de administrador)*.

---

## 💾 Backups y Resguardo de Información

> [!IMPORTANT]
> Al almacenar los datos localmente en el navegador (`localStorage`), si borras el historial o la caché del navegador de forma completa, los datos podrían perderse.
> 
> **Recomendaciones**:
> *   Utiliza regularmente el botón **"Exportar CSV"** para mantener copias de seguridad de tus registros.
> *   No utilices el modo incógnito del navegador, ya que este limpia el almacenamiento al cerrar la sesión.

---

## 🛡️ Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

