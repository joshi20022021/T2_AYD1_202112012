### **Nombre: Edgar Josías** ### **Cán Ajquejay** ### **Carnet: 202112012** ### TAREA 2

Dado un sitio web de ventas online como ebay, amazon o walmart, realizar una lista de todos los requerimientos funcionales y no funcionales que se deben implementar para que esa pagina funciona correctamente. Identifique los actores y realice el diagrama de casos de usos.

---

### **Actores del Sistema**

* **Cliente / comprador**: Usuario que navega, busca y compra producto.
* **Vendedor**: Usuario que publica y vende productos en la plataforma.
* **Administrador del sistema**: Gestionar la plataforma y supervisa las operaciones.
* **Administrador**: Gestiona categorías, productos destacados y contenido editorial.

---

### **Requerimientos Funcionales**

#### **1.1 Gestión de Usuarios**
* **RF001**: Registro de nuevos usuarios (compradores y vendedores)
* **RF002**: Autenticación y autorización de usuarios
* **RF003**: Gestión de perfiles de usuario
* **RF004**: Recuperación de contraseñas
* **RF005**: Verificación de identidad para vendedores
* **RF006**: Sistema de roles y permisos
* **RF007**: Historial de actividad del usuario

#### **1.2 Gestión de Productos**
* **RF008**: Publicación de productos por vendedores
* **RF009**: Categorización de productos
* **RF010**: Búsqueda y filtrado de productos
* **RF011**: Visualización detallada de productos
* **RF012**: Gestión de inventario
* **RF013**: Sistema de variantes de productos 
* **RF014**: Productos relacionados y recomendaciones
* **RF015**: Gestión de imágenes y multimedia

#### **1.3 Sistema de Compras**
* **RF016**: Carrito de compras 
* **RF017**: Lista de deseos/favoritos 
* **RF018**: Proceso de checkout 
* **RF019**: Selección de métodos de pago 
* **RF020**: Cálculo de impuestos y envío 
* **RF021**: Confirmación de pedidos 
* **RF022**: Tracking de pedidos

#### **1.4 Sistema de Pagos**
* **RF023**: Procesamiento de pagos con tarjetas
* **RF024**: Integración con métodos de pago externos
* **RF025**: Gestión de reembolsos
* **RF026**: Facturación electrónica
* **RF027**: Historial de transacciones
* **RF028**: Validación de métodos de pago

#### **1.5 Sistema de Valoraciones y Reseñas**
* **RF029**: Calificación de productos
* **RF030**: Reseñas escritas de productos
* **RF031**: Calificación de vendedores
* **RF032**: Sistema de reputación
* **RF033**: Moderación de reseñas
* **RF034**: Respuestas de vendedores a reseñas

#### **1.6 Comunicación**
* **RF035**: Sistema de mensajería entre usuarios
* **RF036**: Notificaciones por email
* **RF037**: Notificaciones push
* **RF038**: Chat en vivo con soporte
* **RF039**: FAQ y centro de ayuda
* **RF040**: Sistema de tickets de soporte

#### **1.7 Gestión de Vendedores**
* **RF041**: Panel dashboard de vendedor 
* **RF042**: Gestión de órdenes por vendedor
* **RF043**: Reportes de ventas
* **RF044**: Gestión de políticas de devolución
* **RF045**: Herramientas promocionales
* **RF046**: Gestión de comisiones

#### **1.8 Administración**
* **RF047**: Panel de administración
* **RF048**: Gestión de usuarios y vendedores
* **RF049**: Moderación de contenido
* **RF050**: Gestión de categorías
* **RF051**: Reportes y análisis de datos
* **RF052**: Gestión de promociones y descuentos
* **RF053**: Configuración del sistema

---

### **REQUERIMIENTOS NO FUNCIONALES**

#### **2.1 Rendimiento**
* **RNF001**: Tiempo de respuesta eficiente para páginas principales
* **RNF002**: Tiempo de carga de imágenes corta
* **RNF003**: Soporte para una gran cantidad de usuarios
* **RNF004**: Disponibilidad 24/7
* **RNF005**: Capacidad de escalar horizontalmente

#### **2.2 Seguridad**
* **RNF006**: Encriptación HTTPS para todas las comunicaciones
* **RNF007**: Cumplimiento de requerimientos de seguridad para datos de tarjetas
* **RNF008**: Autenticación de dos factores opcional
* **RNF009**: Protección contra ataques 
* **RNF010**: Validación y sanitización de datos de entrada
* **RNF011**: Auditoría de accesos y cambios
* **RNF012**: Protección de datos personales

#### **2.3 Usabilidad**
* **RNF013**: Diseño responsive para móviles y tablets
* **RNF014**: Interfaz intuitiva y fácil de usar
* **RNF015**: Soporte multi-idioma
* **RNF016**: Navegación clara y consistente
* **RNF017**: Búsqueda con autocompletado

#### **2.4 Compatibilidad**
* **RNF018**: Soporte para navegadores principales 
* **RNF019**: Compatibilidad con dispositivos iOS y Android
* **RNF020**: APIs RESTful para integraciones
* **RNF021**: Soporte para diferentes métodos de pago regionales

#### **2.5 Mantenibilidad**
* **RNF022**: Código bien documentado
* **RNF023**: Logs para debugging de funcionalidades
* **RNF024**: Backup automático diario de datos 
* **RNF025**: Monitoreo de sistema 24/7

