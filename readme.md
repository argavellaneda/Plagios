#Script para calculo del Indice de Similitud Incremental de trabajos.

- Uso :
	- ./percentdup.sh tipo numero
		- **tipo** : extensión de los archivos a comparar.
		- **numero** : mínimo valor para que aparezca en la comparativa.
		- Ejecutar en la carpeta que contiene todos los archivos a comparar.
		- Los archivo pueden estar contenidos en la carpeta o subcarpetas.
		- Ejemplo `./percentdup.sh java 15`
			- Mostraría aquellos ficheros de extensión `.java` con más  del `15%` de similaridad.
