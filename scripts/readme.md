# Proyecto para los Scripts y Programas para Plagios
# Carpeta /script

## Scripts
- **percentdup.sh**
	- Script Linux Shell para analisis de ficheros de texto
	- Uso : percetdup ext nro
		- **ext** : Extensión de archivos a Analizar
		- **nro** : Porcentage mínimo de plagio para que considere dos archivos
		- Ejecutar en la carpeta que contiene todos los archivos a comparar.
		- Los archivo pueden estar contenidos en la carpeta o subcarpetas.
		- Ejemplo **./percentdup.sh java 15**
			- Mostraría aquellos ficheros de extensión `.java` con más  del `15%` de `similaridad acumulada` dentro de la carpeta actual y sus subcarpetas.
