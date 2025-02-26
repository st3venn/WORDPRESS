# WORDPRESS

## 1. Elección del Tema
Elegí el tema de mi página web basado en los mejores lugares turísticos de Ecuador.

## 2. Selección y Configuración del Tema
Seleccioné un tema sencillo y utilicé un editor clásico básico, ya que al probar otros temas, se borraban algunos elementos de la página.

## 3. Creación de Contenido
Investigé los lugares turísticos más populares de Ecuador, clasificándolos en sus cuatro regiones:
- Costa
- Sierra
- Oriente
- Islas Galápagos

## 4. Estructura de Páginas
Creé las siguientes páginas principales:
- **Lugares:** Presenta las cuatro regiones de Ecuador con botones que llevan a las ciudades correspondientes.
- **Ver Vuelos:** Lista agencias de viajes, con ofertas para viajar al pais y con enlaces directos a sus sitios web.
- **Sobre Nosotros:** Explica el propósito y enfoque de la página web.

## 5. Creación de Posts
En cada post, incluí:
- Cuatro lugares turísticos por ciudad (4 ciudades por region continental).
- Una imagen del sitio con un enlace que envia directamente a la ubicación.
- Descripción detallada de cada lugar y las actividades disponibles.
  
Cada post lo classifiqué en su categoría correspondiente.

Cada ciudad cuenta con botones en sus imágenes que llevan directamente a los posts de los lugares turísticos.

## 6. Implementación de Plugins
Instalé los siguientes plugins para mejorar la funcionalidad del sitio:
- **Contact Form 7:** Para crear dos formularios de contacto en diferentes páginas.
- **Polylang:** Para traducir la página a varios idiomas automáticamente.
- El plugin que utilice tambien para editar facilmente es el **Editor classico**.

## 7. Inserción de Anuncios
Agregué anuncios a la página. Pero, solo me dejaba 2 opciones de las tantas que hay, **After Paragraph** y **Before Paragraph**, entonces no me quedó otra opcion de dejarlos como quedaban.

## 8. Publicación en Hosting
Usé **InfinityFree** como hosting y seguí estos pasos:
1. Instalé WordPress dentro del hosting.
2. Configuré la base de datos actualizando el archivo **SALIDA.SQL**.
3. En **Visual Studio Code**, reemplacé todas las instancias de `https://localhost` por `http://stevensoriano20.infinityfreeapp.com/`.
4. Subí la base de datos a **PHPMyAdmin** del hosting.
5. En **FileZilla**, configuré los detalles de FTP y exporté la carpeta **wp-content** dentro de **htdocs**.
6. En la carpeta **htdocs**, edité el archivo **wp-config.php**, cambiando la línea:
   `$table_prefix = 'wprs';`  por:  `$table_prefix = 'wp_'; `

## 9. Conclusión
Con estos pasos, la página web quedó publicada correctamente. Si deseas viajar a Ecuador, puedes utilizar esta página guia turistica para explorar los mejores destinos turísticos.
