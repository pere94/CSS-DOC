# Cómo empezar a mostrar productos en nombre de sus comerciantes

Si participa en el programa de CSS, podrá mostrar productos en nombre de los comerciantes tanto de forma orgánica como en anuncios en Google.

En este artículo se describen los pasos que debe seguir en las herramientas de Google para empezar a participar en esta oportunidad. [Más información sobre las distintas formas en que los comerciantes pueden trabajar con servicios de comparación de precios](https://support.google.com/merchants/answer/9133811)

**Secciones de esta página:**

* [Antes de empezar](https://support.google.com/css-center/answer/13995647#Beforebegin)
* [Cómo empezar](https://support.google.com/css-center/answer/13995647#Gettingstarted)
* [Requisito de rendimiento del inventario](https://support.google.com/css-center/answer/13995647#inventory-performance-requirement)
* [Enlaces a su sitio web](https://support.google.com/css-center/answer/13995647#WebsiteLinks)
* [Ampliación a otros países](https://support.google.com/css-center/answer/13995647#expansion)
* [Productos de comerciantes más allá de la búsqueda general de Google](https://support.google.com/css-center/answer/13995647#products-beyond-search)

***

### Antes de empezar

1. Compruebe que cumple los [requisitos mínimos para mostrar productos en nombre de sus comerciantes](https://support.google.com/css-center/answer/13748444#Show\_products).
2. Siga el [proceso de incorporación al programa de CSS](https://support.google.com/css-center/answer/14233609).

***

### Cómo empezar

Para empezar a mostrar productos en nombre de sus comerciantes en Google correctamente, le recomendamos que complete dos fases: integración técnica y escalado (para añadir más productos).

Eche un vistazo a este [vídeo introductorio sobre los servicios de comparación de precios](https://www.youtube.com/watch?time\_continue=3\&v=zVSLaO75icY). En él se abordan los aspectos básicos de Merchant Center, los rechazos de productos por incumplimiento de políticas y el mantenimiento de los feeds.

#### Integración técnica

Esta fase le permite implementar y probar su integración con los sistemas de Google para asegurarse de que la configuración funciona correctamente. Durante esta fase, puede probar que todo funciona según lo esperado con una parte de su inventario, que puede incluir hasta 1 millón de productos y hasta 100 subcuentas, o hasta 100 comerciantes.

**Paso 1: Crear una cuenta de Merchant Center para sus comerciantes**

1. Primero, deberá crear las cuentas de Merchant Center de sus comerciantes. Si ya lo ha hecho, vaya al siguiente paso.
2. [Pase esas cuentas](https://support.google.com/css-center/answer/11144098) a CSS Center.
3. Compruebe que tiene el acceso necesario a las [cuentas de Merchant Center](https://support.google.com/css-center/answer/9773473).
4. Suba los productos.

Para probar la integración, le recomendamos que cree entre 10 y 15 cuentas de Merchant Center como mínimo y que suba productos a ellas.

**Nota:** También puede crear subcuentas para los comerciantes en su cuenta multicliente de CSS.

### Crear cuentas de Merchant Center y subir productos

1. Mediante la [API Content](https://developers.google.com/shopping-content/guides/quickstart), cree cuentas de Merchant Center para cada comerciante al que quiera representar.
2. Envíe los datos de producto de cada comerciante al que represente a través de la API Content. Si representa a menos de 1000 comerciantes, también puede usar feeds. Le recomendamos que use la API Content si tiene previsto hacer varios cambios al día (por ejemplo, actualizar el precio y la disponibilidad de determinados productos). [Más información sobre cómo crear un feed](https://support.google.com/merchants/answer/7439058)
3. Cuando suba sus datos, tenga en cuenta las [políticas de anuncios de shopping](https://support.google.com/merchants/answer/6149970) y siga la [especificación de datos de producto](https://support.google.com/merchants/answer/7052112). A continuación, se indican algunos aspectos concretos que debe tener presentes:
   * Las URLs que se envíen mediante el [atributo de enlace](https://support.google.com/merchants/answer/6324416) deben dirigir directamente a un sitio del dominio de Merchant Center. Si quiere redirigir anuncios a través de otros dominios con fines de seguimiento, utilice el [atributo de redirección de anuncios](https://support.google.com/merchants/answer/6324450).
   * Las páginas de destino deben mostrar todos los elementos clave del producto anunciado, y esa información debe coincidir con la que haya enviado en los datos de producto. Estos elementos incluyen el título, la descripción, la imagen, el precio, la moneda, la disponibilidad y un botón de compra. No es necesario que el título, la descripción y las imágenes sean siempre idénticos al contenido de los datos de producto, pero deben hacer referencia al mismo producto. No se admiten las páginas que no permitan la compra directa del producto (por ejemplo, subastas).
   * En cada cuenta de Merchant Center, especifique el sitio web del comerciante en cuestión. El sitio web debe coincidir con el dominio vinculado en los datos de producto que se envíen a esa cuenta, y se mostrará automáticamente como reclamado por la cuenta. No defina un dominio para la MCA principal del CSS.

### Panel de control para comerciantes

* Los comerciantes que tienen su propia cuenta de Merchant Center pueden acceder a un panel de control donde se les muestra qué CSS suben productos de su tienda. Los productos que envía el CSS están activos de forma predeterminada, pero los comerciantes pueden inhabilitarlos de CSS concretos y de Google Shopping. Si lo hacen, esos productos se desactivan.
* Este panel de control permite a los comerciantes saber quién los representa para poder adaptar sus decisiones empresariales y sus estrategias de marketing, gestionar sus presupuestos y asegurarse de que sus sistemas están configurados para gestionar el tráfico procedente de los CSS.
* La información de contacto del servicio de atención al cliente que haya introducido para la MCA de su CSS se mostrará a los comerciantes a los que representa para que puedan ponerse en contacto con usted si es necesario. Recibirá una notificación por correo si un comerciante se da de baja de su CSS. También puede consultar un resumen de todos los comerciantes que hayan cambiado su estado de activación en el informe "Estado del comerciante" de la página "Comerciantes" de CSS Center.

**Paso 2: Crear campañas de anuncios de shopping**

1. Cree una cuenta de Google Ads y vincúlela exclusivamente a sus cuentas de Merchant Center. Le recomendamos que no reutilice cuentas de Google Ads ya creadas para campañas de CSS. Tener una cuenta de Google Ads exclusiva para el CSS nos permite tratar sus datos confidenciales como corresponde.
2. Si cambia una cuenta de un comerciante ya creada a su CSS, puede seguir usando las cuentas de Merchant Center y de Google Ads que tenga ese comerciante.

Consulte los siguientes artículos para empezar:

* [Crear una cuenta de Google Ads](https://support.google.com/google-ads/answer/6366720)
* [Vincular una cuenta de Google Ads a Merchant Center](https://support.google.com/merchants/answer/6159060)

[Más información sobre Google Ads y las campañas de shopping](https://support.google.com/merchants/answer/2660968)

#### Escalado

Una vez que haya creado las cuentas de Merchant Center para sus comerciantes, haya subido sus productos y haya vinculado al menos una cuenta de Google Ads a esos comerciantes, podrá solicitar que se inicie la fase de escalado.

En esta fase, podrá subir su inventario. Indíquenos cuántos productos tiene previsto subir para que podamos reservar la capacidad correspondiente. Si su intención es subir productos de más de 100.000 comerciantes, indíquenoslo para que podamos configurar su cuenta correctamente.

**Nota:** El proceso de incorporación tarda 60 días en completarse. También puede solicitar salir de la fase de escalado antes de que finalice ese periodo. Una vez que se haya completado la incorporación, su inventario estará sujeto a los requisitos de rendimiento (indicados a continuación) según los resultados que ofrezcan sus anuncios.

***

### Requisito de rendimiento del inventario <a href="#inventory-performance-requirement" id="inventory-performance-requirement"></a>

Una vez que se haya completado el proceso de incorporación, para optimizar los recursos y la experiencia de usuario, su inventario deberá presentar un rendimiento mínimo concreto para conservar su tamaño. Si los consumidores hacen clic en sus anuncios es porque han encontrado útiles los productos y comerciantes correspondientes. Cuantos más clics hagan los usuarios en sus anuncios, más productos podrá subir. Por tanto, el inventario que suba debe conseguir una proporción de clic por producto de al menos 1:40 durante un periodo de 28 días.

Esto significa que, en cada conjunto de 40 productos enviados a Google, debe producirse al menos un clic durante un periodo de 28 días. Si no se cumple esa proporción, no podrá subir más productos y tendrá que reducir el inventario para que vuelva a corresponderse con la proporción que se exige. Si esto ocurre, recibirá una notificación en CSS Center.

***

### Enlaces a su sitio web

Puede que se muestren enlaces a su sitio web de CSS junto con los productos de sus comerciantes de forma orgánica y en anuncios. Para mostrar a los usuarios productos que les interesen en su sitio web, Google transfiere la consulta de búsqueda de los usuarios a la función de búsqueda de su sitio. Si hay riesgo de que la consulta contenga información privada del usuario, el enlace llevará a este a su página principal sin transferir la consulta. Las consultas funcionan de la misma forma con todos los CSS. Los enlaces correspondientes al CSS cuyos productos de comerciante se muestran aparecen automáticamente sin coste.

Si su CSS está activo en varios países, debe asegurarse de que los usuarios encuentran los productos de su sitio web en el país y el idioma correctos cuando hagan clic en el enlace que se muestra junto con la ficha de su comerciante. En otras palabras: el país y el idioma de los productos de su sitio web deben coincidir con los que se muestran en Google.

Para configurar o actualizar la vinculación, utilice este [enlace de asistencia](https://support.google.com/css-center/answer/9514710).

***

### Ampliación a otros países <a href="#expansion" id="expansion"></a>

Para poder ampliar su CSS a otros países:

1. El CSS debe cumplir los requisitos mínimos para mostrarse en el país en cuestión. Uno de estos requisitos es mostrar productos de 50 dominios de comerciante distintos en cada país al que oriente los anuncios de shopping. Estos comerciantes deben enviar productos a sus respectivos países, es decir, los consumidores de cada país deben poder hacerles compras. Para registrarse como CSS en un país concreto, consulte los [requisitos mínimos correspondientes](https://support.google.com/merchants/answer/7524491).
2. Una vez que su CSS cumpla los requisitos para publicar anuncios de shopping en el país que le interese, podrá emplear un modelo de publicidad para varios países, lo que le permitirá usar un único feed por idioma y orientar los anuncios a varios países del EEE a la vez.

[Más información sobre cómo mostrar productos en varios países de venta](https://support.google.com/merchants/answer/7448571)

### Productos de comerciantes más allá de la búsqueda general de Google <a href="#products-beyond-search" id="products-beyond-search"></a>

De forma predeterminada, los CSS solo pueden publicar productos en las páginas de resultados de la búsqueda general de Google. Use este [formulario](https://support.google.com/css-center/answer/9514710) (concretamente, la sección de exención y activación del seguimiento en paralelo) para habilitar otras superficies de Google (como la pestaña Shopping, la búsqueda de imágenes y YouTube).

***

### Usar feeds automáticos a partir de rastreos de sitios web

Google ofrece a los comerciantes la posibilidad de [utilizar feeds automáticos a partir de rastreos de sitios web](https://support.google.com/merchants/answer/7538732). De forma predeterminada, todos los CSS permiten que los comerciantes usen esta función. Si quiere cambiar este ajuste, rellene este formulario para inhabilitarlo.

Importante:

* Desde sus cuentas de Merchant Center Next, los comerciantes pueden a su vez cambiar el ajuste que usted establezca.
* Si decide habilitar los feeds automáticos en sus cuentas, los productos solo se añadirán si el propietario del dominio ha concedido el acceso "Rastreo de sitio web" al CSS en el [panel de control de CSS](https://support.google.com/merchants/answer/7523057).
