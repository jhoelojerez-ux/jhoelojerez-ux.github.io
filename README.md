# jhoelojerez-ux.github.io
# Full Pollo Bacano — Pedidos & Rutas (v5.2)

Sistema de gestión local para la administración de pedidos, control de despacho y optimización de rutas de entrega para **Full Pollo Bacano**.

---

## 🚀 Acceso a la Aplicación

Puedes acceder a la versión desplegada en vivo a través de GitHub Pages en el siguiente enlace:
👉 **[Ver Aplicación en Vivo](https://<TU-USUARIO>.github.io/<NOMBRE-DEL-REPOSITORIO>/)**

*(Asegúrate de reemplazar `<TU-USUARIO>` y `<NOMBRE-DEL-REPOSITORIO>` con tus datos reales).*

---

## 🛠️ Características Principales

- **Gestión de Roles**: Panel con accesos y vistas adaptadas según el tipo de usuario (Administrador, Supervisor, Vendedor, Despacho).
- **Toma de Pedidos**: Interfaz para selección de productos, cantidades e información del cliente.
- **Control de Rutas**: Agrupación y asignación visual de pedidos por rutas optimizadas.
- **Exportación de Informes**: Integración con librerías para generación de reportes en PDF (`jsPDF`) y hojas de cálculo en Excel (`SheetJS/xlsx`).

---

## 💻 Tecnologías Utilizadas

- **HTML5 & CSS3**: Diseño responsivo con variables CSS y estilos personalizados.
- **JavaScript (Vanilla)**: Lógica del cliente, gestión de estados y manipulación del DOM.
- **Librerías Externas**:
  - [jsPDF](https://github.com/parallax/jsPDF) & AutoTable (Generación de archivos PDF).
  - [SheetJS (xlsx)](https://github.com/SheetJS/sheetjs) (Lectura y exportación a Excel).
  - Google Fonts (`Bebas Neue`, `DM Sans`, `JetBrains Mono`).

---

## ⚙️ Configuración en GitHub Pages

Para visualizar la página correctamente desde GitHub Pages:

1. Ve a la pestaña **Settings** (Configuración) de tu repositorio.
2. En el menú izquierdo, selecciona **Pages**.
3. En la sección **Build and deployment** -> **Source**, selecciona `Deploy from a branch`.
4. Elige la rama principal (`main` o `master`) y la carpeta `/ (root)`.
5. Haz clic en **Save**.

> **Nota importante:** GitHub Pages busca por defecto un archivo llamado `index.html`. Para que tu aplicación cargue automáticamente, se recomienda renombrar el archivo `FPB_PedidosRutas_v5.2.html` a `index.html`.
