# Proyecto para los Scripts y Programas para Plagios
# Carpeta `/scripts`

## Scripts y Archivos
- **Readme.md**
	- Este documento.
- **percentdup.sh**
	- Script Linux Shell para Analisis de Similitud Incremental de Ficheros de Texto Plano
	- Abrir un terminal y escribir el comando adecuado :
	- Uso : `./percetdup ext nro`
		- **ext** : Extensión de archivos a Analizar
		- **nro** : Porcentage mínimo de plagio para que considere dos archivos
		- Ejecutar en la carpeta que contiene todos los archivos a comparar.
		- Los archivo a comparar pueden estar contenidos en la `carpeta o subcarpetas`.
		- **Ejemplo** :
			- Situado en la carpeta donde residen los programas `.java` a analizar, entonces escribir :
				- **.....rutaHastaElScript/percentdup.sh java 15**
				- Mostraría un informe de aquellos ficheros de extensión `.java` con más del `15%` de `Similaridad Acumulada` dentro de la carpeta actual y sus subcarpetas.
