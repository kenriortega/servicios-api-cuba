# Servicios Cuba API

Este repositorio recoge diferentes endpoints relacionados con los servicios informaticos alojados en nuestro país, con la finalidad de fomentar y promover el desarrollo de los servicios informáticos en *CUBA*


## Listado de Servicios API

>  *RedCuba* ofrece servicio REST-API para conocer el clima en el país.

- Endpoint [https://www.redcuba.cu/api/weather_get_summary/{nombre de provincia Habana}](https://www.redcuba.cu/api/weather_get_summary/Habana)


> *APKLIS* ofrece servicio REST-API para conocer el estado de las aplicaciones móviles en cuba

- Endpoint [https://api.apklis.cu/v2/application/](https://api.apklis.cu/v2/application/) ofrece un listado de las aplicaciones registradas en la plataforma

- Endpoint [https://api.apklis.cu/v2/review/?application={nombre-de-paquete com.cubanopensource.todo}](https://api.apklis.cu/v2/review/?application=com.cubanopensource.todo) ofrece la descripcion dado el nombre de una aplicación

> *Covid19 cuba*

- Endpoint [https://covid19cuba.github.io/covid19cubadata.github.io/api/v2/full.json](https://covid19cuba.github.io/covid19cubadata.github.io/api/v2/full.json) resumen covid en cuba

> *Tv digital*

- Endpoint [http://eprog2.tvcdigital.cu/canales](http://eprog2.tvcdigital.cu/canales) Descripcion de cada canal que se transmite por la television digital terrestre en Cuba

- Endpoint [http://eprog2.tvcdigital.cu/programacion/{channel-id}/{date}](http://eprog2.tvcdigital.cu/programacion/$%7Bchannel.id%7D/$date) Detalle de la programacion de un canal y fecha determinados por parametros en el querystring

> *cubava*

- Endpoint https://www.{nombre-del-sitio}.cubava.cu/wp-json/wp/v2/pages representa un listado de formato json con todas las paginas del sitio y sus datos asociados

- Endpoint https://www.{nombre-del-sitio}.cubava.cu/wp-json/wp/v2/posts representa un listado de formato json con todas las entradas o publicaciones del sitio y sus datos asociados

- Endpoint https://www.{nombre-del-sitio}.cubava.cu/wp-json/wp/v2/comments representa un listado de formato json con todos los comentarios del sitio y sus datos asociados
