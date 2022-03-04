# Gastos en asesorías externas de la Cámara de Diputadas y Diputados de Chile (2018-2022)

## Los datos

Los datos fueron extraídos del [sitio web de la Cámara de Diputadas y Diputados](https://www.camara.cl/transparencia/asesoriasexternasgral.aspx) usando los paquetes de R {[RSelenium](https://docs.ropensci.org/RSelenium/articles/basics.html)} y {[rvest](https://rvest.tidyverse.org/)}. 
La base de datos tiene 1980 observaciones para 9 variables:

| variable | descripción |
|----------|-------------|
| anio | año de la asesoría |
| mes | mes de la asesoría |
| folio | folio de la asesoría |
| asesor | nombre de la persona o institución que realizó la asesoría |
| monto | monto pagado por el serivicio |
| diputado | nombre del diputado o diputada solicitante |
| tipo de informe | si es informe final o parcial |
| doc | enlace al pdf del informe |
| formulario | enlace al formulario de actividades desarrolladas |
