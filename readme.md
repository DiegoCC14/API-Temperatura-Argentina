### API TEMPERATURA ARGENTINA

- #### Endpoint: <a>http://40.119.47.179:8080/api_smn/</a>
- #### Metodo: GET
- #### Body: {"id_location":"num_localidad"}

### LOCALIDADES DISPONIBLES
- #### [Archivo_JSON_Localidades](https://github.com/DiegoCC14/Api_temperatura_argentina/blob/main/JSON_Localidades.json)
- #### Estructura JSON: 
		- { "Provincia" :
			- { "localidad" : 
				- {"id": num_localidad , 
				- "coordenadas": {"lat","long"} 
				- }
			- } 
		- }

### DETALLES API
- Detalles Implementacion: 
	- Tecnologias: Selenium , Python , Django , SQLite3 , SQLAlchemy
	- Repositorio Github: <a>https://github.com/DiegoCC14/API_SMN_Implementacion</a>
- #### Github: DiegoCC14
- #### Correo: diego.xmen123@gmail.com
