# Clusterización
## Input
Se ha publicado un archivo ("data_ecu.txt") que contiene 305 ubicaciones del Ecuador. Cada ubicación es un dato de dos dimensiones que representa la latitud y la longitud del lugar. Por ejemplo "-80.43  -0,95" significa la longitud es de -80.43 y la latitud es de -0,95

## Output
Implementar el algoritmo de K-means para agrupar las 305 ubicaciones en tres clusters, de manera que las ubicaciones dentro del mismo cluster estén geográficamente cercanas entre sí.

1. Genere un archivo de salida llamado "clusters.txt". El archivo de salida debe contener exactamente 305 líneas, donde cada línea representa la etiqueta de cluster de cada ubicación. Cada línea debe tener el formato: location_id cluster_label.

A continuación se proporciona un ejemplo de un fragmento del archivo de salida "clusters.txt":
0 1
1 0
2 1
3 2

La primera ubicación pertenece al cluster "1".
La segunda ubicación pertenece al cluster "0".
