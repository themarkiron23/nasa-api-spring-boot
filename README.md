# nasa-api-spring-boot

Api Com springboot  java 8 , focada em consumir uma API da nasa , retornando se um asteroid esta ou nao a caminho da terra
informando uma data no formato 2018-12-01  - YYYY-MM-dd

# Para que os resultados sejam retornados com sucesso , a data tem que ser posterior no maximo 7 dias do dia atual .

exemplo  :  dia atual 2018-12-01  until  2018-12-07

Ainda temos uma camada de authenticacao mockada , apenas para teste , pois nao ha conexacao com banco de dados para tal service.


# Informacoes de authenticacao 

//GERAR TOKEN  METHOD POST
{
	
	
 "email" : "felipe.masterdeveloper@gmail.com",
 "senha" : "7218694275905162237644315182889232904370297308549308135143446232159002679111710949916253034019999587",
 "grand_type" : "client_credentials"

}

// RECUPERAR INFORMACOES DE ASTEROIDE NASA 

http://localhost:8080/asteroid-information/2018-12-01
Content-Type  =  application/json
Authorization  = ${TokenGerado}


# Fonte da API  para o desenvolvimento 

https://api.nasa.gov/api.html#NeoWS


Divirtam-se =)


versao google cloud 

https://persistence-mongodb-api.appspot.com






