### API TEMPERATURA ARGENTINA

- #### Endpoint: <a>http://40.119.47.179:8080/api_smn/?id_localidad=889</a>
- #### Metodo: GET
- #### Detalles Uso: Cambie el valor del parametro "id_localidad" que se encuentra en la URL por la localidad que usted prefiera, las localidades validas estan en el "JSON_Localidades_Disponibles"

### LOCALIDADES DISPONIBLES
- #### [Archivo_JSON_Localidades_Disponibles](https://github.com/DiegoCC14/Api_temperatura_argentina/blob/main/JSON_Localidades.json)
- #### Estructura JSON: 
		- { "Provincia" :
			- { "localidad" : 
				- {"id": id_localidad , 
				- "coordenadas": {"lat","long"} 
				- }
			- } 
		- }
### IMPLEMENTACIONES
#### - Python - Requests
	import requests , json
  	
	url = "http://40.119.47.179:8080/api_smn/?id_localidad=122"
	headers = { 'Content-Type': 'application/json' }
	response = requests.request("GET", url, headers=headers)
	print(response.text)
#### - cURL
	curl --location --request GET 'http://40.119.47.179:8080/api_smn/?id_localidad=122' \
	header 'Content-Type: application/json' \

### DETALLES API
- Detalles Implementacion: 
	- Tecnologias: Selenium , Python , Django , SQLite3 , SQLAlchemy
	- Repositorio Github: <a>https://github.com/DiegoCC14/API_SMN_Implementacion</a>
- #### Github: DiegoCC14
- #### Correo: diego.xmen123@gmail.com
