# Monitorizacion de conversiones

Tiempo más Online = 1 Hora

*   Nota

    Se Puede demorar hasta 3 horas en salir en Google

Sistema de para saber cuáles se enviaron y cuáles no.

* Crear tabla aparte para gestionar transacciones enviadas:
  *   Nombre de tabla: monitor\_css\_transactions\_manager

      ```sql
      // table: monitor_css_transactions_manager

      id - int
      google_customer_id - varchar
      google_conversion_id - varchar
      google_ads_job_id - varchar
      state - ENUM 1=waiting, 2=failure, 3=success 
      retries - int
      created_at - timestamp
      updated_at - timestamp
      ```

      monitor\_css\_transactions\_sent

      ```sql
      // table: monitor_css_transactions_sent

      id | int
      monitor_css_transactions_manager_id | int
      transaction_id | int  
      created_at | timestamp
      updated_at | timestamp
      ```

Sistema para saber cuando hay un error y volver a intentar enviar cada X tiempo 3 retries → Notificar la transacción con el error al 3er intento



***

***

#### Posibles condiciones en la subida de conversiones a Google Ads:

* Bien - &#x20;
  * jobSummaries\[job\_id] no tiene la propiedad failedCount o es == '0'
  * AND jobSummaries\[job\_id].successfulCount == cantidad transacciones enviada para este manager
* Falló -
  * jobSummaries\[job\_id].failedCount != '0'&#x20;
  * AND jobSummaries\[job\_id].successfulCount != cantidad transacciones enviada para este manager
* Waiting
  * jobSummaries\[job\_id] no existe
  * OR ( jobSummaries\[job\_id].failedCount no existe o == 0\
    &#x20;   AND jobSummaries\[job\_id].successfulCount != cantidad transacciones enviada\
    &#x20;   AND jobSummaries\[job\_id].pendingCount no existe o es != 0 )
  * OR ???? ((hay que hacer una prueba))

***

***



