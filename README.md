

# TiendaApp

**TiendaApp** es una aplicación de comercio electrónico desarrollada en Android Studio, diseñada para facilitar las compras y ventas de productos directamente desde dispositivos Android. La aplicación incluye funciones de navegación, gestión de usuarios, catálogos de productos, chats de soporte y una interfaz intuitiva de usuario.

## Características Principales

- **Catálogo de Productos**: Listado de productos con detalles, descripciones, precios y disponibilidad.
- **Gestión de Usuarios**: Registro y autenticación de usuarios, con perfiles de comprador y vendedor.
- **Carrito de Compras**: Función para agregar, visualizar y eliminar productos del carrito.
- **Chat en Tiempo Real**: Comunicación entre compradores y vendedores para resolver dudas o consultas.
- **Navegación por Pestañas**: Barra de navegación inferior que facilita el cambio de secciones como Home, Ventas, y Notificaciones.
- **Sistema de Notificaciones**: Notificaciones automáticas para actualizaciones de compras, ventas y soporte.

## Tecnologías Utilizadas

- **Lenguaje**: Java
- **IDE**: Android Studio
- **Interfaz de Usuario**: XML para el diseño de pantallas y la disposición de elementos.
- **Base de Datos**: Firebase o SQLite para almacenar y gestionar los datos de usuarios, productos y chats.
- **Framework de Navegación**: BottomNavigationView para la navegación entre secciones.
- **Patrón de Arquitectura**: MVVM (Modelo-Vista-ViewModel) para una separación limpia de lógica de negocio y presentación.

## Requisitos del Sistema

- **Sistema Operativo**: Android 5.0 Lollipop o superior
- **Android Studio**: Version 4.0 o superior
- **Conexión a Internet**: Para la carga de datos en tiempo real y la funcionalidad de chat

## Instalación

Sigue estos pasos para clonar e instalar el proyecto en tu entorno de desarrollo:

1. **Clonar el repositorio**:
    ```bash
    git clone https://github.com/jmcasgar/Ejemplo_tienda.git
    cd TiendaApp
    ```

2. **Abrir el proyecto en Android Studio**:
   - Inicia Android Studio y selecciona "Open an Existing Project".
   - Navega hasta la carpeta del proyecto y selecciónala.

3. **Configurar Firebase** (opcional, si usas Firebase para la autenticación o la base de datos):
   - Accede a [Firebase Console](https://console.firebase.google.com/).
   - Agrega un nuevo proyecto y configura Firebase con tu aplicación.
   - Descarga el archivo `google-services.json` y colócalo en el directorio `/app`.

4. **Construir e Instalar la aplicación**:
   - Conecta un dispositivo Android o utiliza el emulador.
   - Haz clic en “Run” para instalar y ejecutar la aplicación.

## Uso de la Aplicación

1. **Registro e Inicio de Sesión**:
   - Los usuarios pueden registrarse e iniciar sesión para acceder a la aplicación.

2. **Explorar Productos**:
   - Navega por el catálogo, visualiza productos, añade artículos al carrito y consulta detalles de cada producto.

3. **Comprar y Vender**:
   - Los usuarios registrados como vendedores pueden agregar productos para su venta, mientras que los compradores pueden hacer pedidos.

4. **Chat en Vivo**:
   - Contacta con los vendedores o compradores para resolver preguntas sobre los productos.

5. **Gestión de Pedidos**:
   - Los usuarios pueden acceder a una vista de sus compras y ventas, con detalles de cada transacción.

## Estructura del Proyecto

- **src/** - Código fuente principal de la aplicación, con las siguientes carpetas clave:
    - `models/`: Clases de modelo para representar datos (usuarios, productos, pedidos).
    - `views/`: Actividades y fragmentos que conforman las interfaces de usuario.
    - `controllers/`: Controladores para la lógica de negocio.
    - `utils/`: Utilidades auxiliares, como adaptadores y servicios comunes.

- **res/** - Recursos de la aplicación:
    - `layout/`: Archivos XML para las interfaces de usuario.
    - `drawable/`: Recursos gráficos.
    - `values/`: Archivos de configuración, como strings y estilos.

## Contribución

Las contribuciones son bienvenidas. Para contribuir, sigue estos pasos:

1. Haz un fork del proyecto.
2. Crea una nueva rama (`git checkout -b feature/tu_feature`).
3. Realiza tus cambios y haz un commit (`git commit -m 'Añadir nuevo feature'`).
4. Haz push a la rama (`git push origin feature/tu_feature`).
5. Abre un Pull Request.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

---

Este README proporciona una visión general completa y útil para cualquier persona que quiera trabajar con el proyecto o entender sus funcionalidades.
