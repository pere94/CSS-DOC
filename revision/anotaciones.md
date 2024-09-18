# Anotaciones

#### 1 - Mejorar intención comparativa en cards

Estamos mostrando en card de producto una marca y ofertas, esto puede dar intención de que es una card de una marca y no hay comparativa alguna y las ofertas son de Fnac.

<figure><img src="../.gitbook/assets/imagen.png" alt="" width="208"><figcaption></figcaption></figure>

Por otra parte encontramos en [https://bigshopper.es/search/?q=iphone+15](https://bigshopper.es/search/?q=iphone+15) que son mas literales&#x20;

<figure><img src="../.gitbook/assets/imagen (1).png" alt="" width="197"><figcaption></figcaption></figure>

Están mostrando:

* En enlace a página de detalles como "Comparar {número de ofertas} tiendas"
* Segundo enlace con clara intención de ir a la tienda directamente.
* Click en imagen: lleva a detalle de producto.
* Click en Apple lleva a una url donde solo hay productos de Apple ([https://bigshopper.es/brand/apple/](https://bigshopper.es/brand/apple/)). Esto lo hacemos, pero a nivel de search params, (es mejor en urls diferentes para la indexación de más productos, tal como lo hacen los ecommerce)
* Click en boton de comparar: lleva a pagina de detalle de producto.
* Click en "Directamente a la tienda": lleva al enlace del producto de menor precio.

#### 2 - Páginas diferentes para todas las categorías

* Ej: [https://bigshopper.es/category/](https://bigshopper.es/category/)
* Ej: [https://bigshopper.es/category/bricolaje/?page=5](https://bigshopper.es/category/bricolaje/?page=5)
* Veo bien que tienen páginas diferentes para cada categoría.
* Luego esto permite enriquecer cada pagina con contenido con IA y "generar una especie de valor extra" (esto es mas que todo es para indexar en google esas urls y no sean Thin content)
* Luego esto ayuda a los crawler de google a indexar mas urls de la web
* El punto negativo es que no puedes hacer filtros con varias categorías al mismo tiempo, pero tampoco le veo mucho sentido la verdad.

3 - Páginas diferentes para todos las marcas

* Ej: [https://bigshopper.es/brand/](https://bigshopper.es/brand/)
* Ej: [https://bigshopper.es/brand/abnet/](https://bigshopper.es/brand/abnet/)
* Esto deriva luego en páginas específicas por marca para sus productos
* Esto mejora la estructura web.

4- Paginas diferentes para todos los merchants

* Ej: [https://bigshopper.es/merchant/](https://bigshopper.es/merchant/)
* Ej: [https://bigshopper.es/merchant/100-hardcore/](https://bigshopper.es/merchant/100-hardcore/)
* Lo mismo de marcas aplica a merchants

5 - Pagina de promociones (productos con grandes descuentos, digamos mas de 20%)

* Ej: [https://bigshopper.es/promocion/](https://bigshopper.es/promocion/)
