---
description: >-
  En este artículo se explica qué son las páginas de producto de CSS, así como
  los requisitos y las prácticas recomendadas para mostrarlas.
---

# Requerimientos: Acerca de los requisitos de las páginas de producto de CSS

Ref: [https://support.google.com/css-center/answer/13709336?sjid=4171573421641804439-EU](https://support.google.com/css-center/answer/13709336?sjid=4171573421641804439-EU)

```
Importante

El éxito de las páginas de producto y de nuestros partners de CSS se basa en
ofrecer una experiencia de alta calidad que permita a los clientes buscar
productos con confianza.

Los clientes confían en que, si acceden a un CSS a través de un enlace, se les
dirigirá a una página de producto con ofertas de distintos comerciantes.
El precio que se muestra en Google debe coincidir con el que ofrece uno de esos
comerciantes.
```



* :red\_circle: :warning: Su página de producto de CSS tiene que coincidir con los datos de producto que envíe a Google.&#x20;
* :warning: Debe proporcionar contenido de alta calidad.
* :white\_check\_mark: Debe proporcionar opciones de comparación de precios para interactuar mejor con sus clientes.

### Cómo enviar una página de producto de CSS

Las URLs de sus páginas de producto de CSS se pueden enviar mediante los siguientes atributos:

* El enlace de CPP [`[cpp_link]`](https://support.google.com/css-center/answer/13583449) dirige a los clientes a la página de producto de CSS.
* El enlace móvil de CPP [`[cpp_mobile_link]`](https://support.google.com/css-center/answer/13583245) envía a los clientes a una versión optimizada para móviles de su página de producto de CSS. Esta versión se mostrará a los clientes que utilicen dispositivos móviles, como teléfonos o tablets.

### Requisitos mínimos

Para mostrar páginas de producto de CSS en Google, debe cumplir los requisitos que se indican a continuación.

#### Muestre su producto y sus ofertas de forma clara

* Envíe una página de producto que:
  * :white\_check\_mark: **Esté en el dominio asociado a su cuenta de CSS Center.** No puede redirigir automáticamente a los clientes a otros dominios.
  * :white\_check\_mark: **Muestre un solo producto** y su descripción.
  * :warning: **Contenga los precios y las condiciones de venta del producto** ofrecidos por al menos dos comerciantes independientes que tengan el producto disponible para su venta online inmediata.
* Asegúrese de lo siguiente:
  * :white\_check\_mark: :red\_circle: :information\_source: **El producto que se muestra en su página de producto de CSS y en las páginas de producto del comerciante es similar al que ha enviado** en sus datos de producto. No es necesario que el título, la descripción y las imágenes sean idénticos a los que figuran en los datos de producto.
  * :white\_check\_mark: **El precio y las condiciones de venta de su página de producto de CSS coinciden** con los de las páginas de producto de los comerciantes.
    * :warning: :green\_book: **Nota:** Si en el país donde muestra el producto es obligatorio incluir los impuestos en el precio, muestre todos los precios con impuestos incluidos en la página de producto de CSS y envíe este mismo precio en los datos de producto.
  * :white\_check\_mark: **Los clientes pueden comprar el producto a un comerciante por el precio que se muestra** en su página de producto de CSS. Esto implica que puedan añadir productos al carrito y recibirlos sin problemas.
* :white\_check\_mark: :red\_circle: :information\_source: **Los enlaces de las páginas de producto de CSS deben llevar directamente a las páginas de producto del comerciante,** donde los clientes podrán comprar el producto.

<figure><img src="../.gitbook/assets/Graphics #1_Comparison Shopping Services (CSS)- CSS product page requirements Draft file-01 (1).svg" alt="" width="563"><figcaption></figcaption></figure>

* :warning: **Compruebe que la página muestra información sobre el nivel de eficiencia energética** de los productos si corresponde.
* :white\_check\_mark: **No use diseños en los que se oculten los elementos importantes de la página.** Por ejemplo, una ventana emergente o un banner no deben tapar información que sea importante para los clientes.
  * :warning: (importante para bebidas y contenidos sexuales) **Nota:** En el caso de ciertos productos, la legislación local puede exigir que los clientes accedan a una página diferente antes de entrar en su página de producto. Por ejemplo, es posible que deba verificar la edad de los usuarios antes de que puedan acceder a su sitio. Es necesario que, cuando los usuarios pasen por dicha página, accedan a una página de producto que cumpla con las directrices indicadas anteriormente.

<figure><img src="../.gitbook/assets/working_productpagerequirements_ES_Pop-ups regarding product elements.svg" alt="" width="563"><figcaption></figcaption></figure>

#### Resalte su oferta destacada

La **oferta destacada** es aquella que aparece resaltada o que se muestra entre las tres ofertas principales junto con los precios y las condiciones de venta de diferentes comerciantes en la página del producto.

* :white\_check\_mark: :warning:(revisar campo headline\_offer\_price para el feed) **Envíe una página de producto en la que aparezca resaltado el precio de la oferta destacada.** Debe destacar o mostrar de forma predominante uno de los comerciantes de su página de producto cuyo precio coincida con el de la oferta destacada. Consulte más información sobre el atributo de [precio de la oferta destacada `[headline_offer_price]`](https://support.google.com/css-center/answer/13583347).
* :white\_check\_mark: :warning:(importante para cuando hagamos campaña) **Asegúrese de que los clientes puedan comprar online el producto del comerciante destacado,** lo que implica que puedan añadirlo al carrito y recibirlo sin problemas. Si el producto correspondiente a la oferta destacada está agotado, cambie la oferta destacada.
* :blue\_book:(revisar) **Compruebe que el estado del producto de la oferta destacada coincida con el que figura en sus datos de producto.** Consulte más información sobre el atributo de [estado de la oferta destacada `[headline_offer_condition]`](https://support.google.com/css-center/answer/13582738).

#### Muestre contenido coherente en todas las ubicaciones

```
Ejemplo

Imagine que es un CSS de Alemania. En ese caso, tiene que indicar en sus
datos de producto que muestra productos en Alemania, enviar los precios
en euros y utilizar el alemán.

Pongamos que quiere enviar una página de producto de CSS para un sofá. Si su
página de producto de CSS se visita desde Polonia, la página debe mostrar el
mismo sofá, incluidos todos los elementos clave del producto y las ofertas del
comerciante.

En concreto, la página de producto de CSS debe:

    Mostrar una imagen del sofá
    Incluir una lista de los comercios que lo venden en Alemania
    Indicar los mismos precios
    Estar escrita en alemán
    Indicar los precios en euros
```

* :warning: :timer: **El contenido de su página de producto de CSS debe ser coherente en todas las ubicaciones.** Puede personalizar ligeramente el contenido (por ejemplo, cambiar el orden de las ofertas). Quizás le interese cambiar el contenido de su sitio web según la ubicación de la IP de los usuarios o de otros factores.&#x20;
* :blue\_book:(revisar para campañas) **Utilice el mismo idioma que en los datos de producto.** Incluso en el caso de los países con varios idiomas oficiales, muestre el producto en su sitio web en el idioma que haya usado en los datos de producto. Por ejemplo, si muestra productos en Polonia, no puede enviar los datos de producto en inglés y mostrar su página de producto de CSS en polaco.
* :white\_check\_mark: **Muestre todos los precios en la misma moneda que haya usado en los datos de producto.**
* :white\_check\_mark: **Muestre los mismos precios en todas las regiones de un mismo país.**
* :warning: (revisar políticas de eficiencia para determinadpos productos) **Cumpla las normativas locales** que se aplican a todos los precios y al resto de la información que envíe y muestre.

#### Compruebe que las páginas funcionen correctamente

* :white\_check\_mark: **Compruebe que su página de producto de CSS esté publicada** y que no esté en construcción ni muestre errores (por ejemplo, un error 404).
* :white\_check\_mark: **Use una página de destino, no un archivo ni un correo electrónico.** No enlace una imagen, un archivo de audio, un vídeo, un documento o un PDF.
* :white\_check\_mark: **Use una página de destino móvil para dispositivos móviles y tablets.** No incluya elementos de diseño que quizás no funcionen correctamente en todos los dispositivos móviles, como Flash, Silverlight o ActiveX.
* :white\_check\_mark: **Permita que los usuarios utilicen el botón para volver.** Asegúrese de que pueden hacer clic en ese botón del navegador para volver a la página anterior después de visitar su página de producto de CSS.
* :white\_check\_mark: :warning:(incluiría las páginas legales en la misma web) **Incluya solo enlaces al dominio que figure en su cuenta de CSS Center.** No redirija automáticamente a los usuarios a un sitio web que no pertenezca al dominio que haya indicado en CSS Center.

### Prácticas recomendadas

* :red\_circle: :blue\_book: :warning: (revisar cuando hagamos campañas) **Seleccione previamente la variante de producto correcta en la URL de su página de producto de CSS.** Si un producto tiene variantes que difieran en color, talla, diseño, material u otros elementos personalizables, asegúrese de que la variante coincida con lo que se muestra en los datos de producto de su página de CSS.

<figure><img src="../.gitbook/assets/working_productpagerequirements_ES_The variant must be selected.svg" alt="" width="563"><figcaption></figcaption></figure>

* :white\_check\_mark: (no es necesario, tenemos una web responsive) **Envíe el atributo de** [enlace móvil de CPP `[cpp_mobile_link]`](https://support.google.com/css-center/answer/13583245) **además del de** [enlace de CPP `[cpp_link]`](https://support.google.com/css-center/answer/13583449) para usar páginas de destino independientes para dispositivos móviles.
* :warning: :red\_circle: (revisar en nuestro metodo de medicion con redirecciones) **Emplee la menor cantidad de redirecciones posible,** ya que aumentan el tiempo que transcurre desde que una persona hace clic en su ficha hasta que se carga su página de producto de CSS. Se desaconseja utilizar métodos de redirección distintos de HTTP 302, como JavaScript o etiquetas meta.

### Directrices adicionales

Para los tipos de producto que se mencionan más abajo, revise cada sección y siga las directrices pertinentes para que sus páginas de producto ofrezcan a los clientes la mejor experiencia posible. Verá alertas sobre cualquier problema o rechazo en su cuenta de CSS Center.

* :red\_circle: :blue\_book: (creo que no venderemos productos en lote) **Si muestra productos que se venden en lote:** En la página de producto, indique el precio total para la cantidad mínima de artículos vendidos o el precio por unidad y la cantidad mínima. El precio que haya enviado en los datos de producto debe coincidir con la cantidad mínima multiplicada por el precio unitario.
* :red\_circle: :warning: (filtros para la unificación de variantes de productos) **Si muestra teléfonos móviles o tablets:** Seleccione previamente variantes de teléfono con los parámetros de URL. Si es posible elegir diferentes variantes de teléfono en la misma página de producto, puede configurar sus URLs para que muestren la correcta a los clientes. Por ejemplo, las variantes podrían incluir opciones de color, almacenamiento y modelos de precios. Tenga en cuenta que los parámetros de URL no son obligatorios, pero son muy útiles para llevar a los usuarios a la página adecuada.
