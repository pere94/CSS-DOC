# Subida

REF: [https://support.google.com/google-ads/answer/7014069#prepare\_data](https://support.google.com/google-ads/answer/7014069#prepare\_data)

### Notas Importantes:

*

#### Prepara tus datos para la importación

* Si el clic que generó alguna de las conversiones importadas ocurrió hace menos de un día, es posible que Google Ads aún no pueda registrar esa conversión.&#x20;
* Te recomendamos que subas los datos correspondientes a un día adicional en cada importación.&#x20;
* Google Ads no registrará las conversiones duplicadas, y recibirás un mensaje de error que te permitirá saber cuáles son estas conversiones.&#x20;
* Ten en cuenta que, anteriormente, las conversiones duplicadas se ignoraban, pero no se mostraba un error. Por lo tanto, si subes conversiones duplicadas con frecuencia, es posible que notes más errores que antes.&#x20;
* Para determinar si una conversión es única, Google Ads utiliza el nombre de la acción de conversión, el momento de la conversión y el identificador único relevante asociados con una conversión.
* Si importas conversiones generadas a partir de clics con el ID de clic de Google (GCLID), no quites el campo del ID de clic de Google. De lo contrario, se producirá un error durante la importación.
* Asegúrate de que tus datos no incluyan columnas adicionales ni ningún tipo de información personal, como números de teléfono y correos electrónicos.
* Si deseas que Google Ads importe tus conversiones automáticamente de manera periódica (consulta el [paso 2: Importa tus conversiones](https://support.google.com/google-ads/answer/7014069#import\_file)), deberás utilizar las Hojas de cálculo de Google o vincular un archivo a través de HTTPS o SFTP.
* Utiliza uno de los siguientes formatos para ingresar la zona horaria (no encierres la zona horaria con comillas ni con otros caracteres especiales):
  * Ingresa tu [ID de zona horaria](https://developers.google.com/google-ads/api/data/codes-formats#timezone\_ids). Se recomienda usar este método para evitar errores durante las transiciones de horarios de verano. Ejemplo: Parameters:TimeZone=America/Chicago
  * Ingresa la diferencia horaria respecto de GMT. Para ello, utiliza los signos + o − y una cifra de 4 dígitos que indique la diferencia (por ejemplo, la diferencia de Nueva York es de -0500 y la de Berlín, de +0100). Si tu zona horaria corresponde a la hora del meridiano de Greenwich, simplemente ingresa +0000. Ejemplo: Parameters:TimeZone=-0500
