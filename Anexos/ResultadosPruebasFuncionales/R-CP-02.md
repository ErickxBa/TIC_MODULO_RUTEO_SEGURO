# Resultado de Caso de Prueba: CP-02

## 📊 Información General
| Campo | Detalle |
| :--- | :--- |
| **Identificador** | CP-02 |
| **Historia de Usuario** | HU-02 |
| **Componente** | Backend (Nest.js) / Azure SQL Server |
| **Estado Final** | 🟢 CUMPLE (Exitoso) |

## 🎯 Objetivo y Escenario
Comprobar el procesamiento en el servidor para calcular y devolver un trazado vial óptimo en formato GeoJSON, evadiendo proactivamente los nodos con reportes de riesgo asignados.

* **Datos de Entrada:** Coordenadas del punto de destino.
* **Precondiciones:** Backend local en Nest.js activo y Base de Datos en Azure accesible con la red vial y zonas de riesgo previamente cargadas.

## 📝 Evaluación de Resultados

### Resultado Esperado
El backend debe calcular y retornar un objeto estructurado en formato GeoJSON con la trayectoria segura de la ruta, discriminando los sectores peligrosos de la base de datos.

### Resultado Obtenido
El algoritmo implementado en Nest.js procesó exitosamente la solicitud de ruteo. Retornó el objeto GeoJSON con la ruta segura en un tiempo aproximado de 1 minuto, rango que incluye los tiempos de latencia con la base de datos Azure SQL.