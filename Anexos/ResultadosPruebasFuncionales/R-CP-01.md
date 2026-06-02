# Resultado de Caso de Prueba: CP-01

## 📊 Información General
| Campo | Detalle |
| :--- | :--- |
| **Identificador** | CP-01 |
| **Historia de Usuario** | HU-01 |
| **Componente** | Interfaz Android (Kotlin) / Mapa |
| **Estado Final** | 🟢 CUMPLE (Exitoso) |

## 🎯 Objetivo y Escenario
Validar el ingreso automático de coordenadas y la colocación de marcadores visuales al interactuar con el mapa interactivo dentro del área de cobertura establecida (Quito).

* **Datos de Entrada:** Punto de destino: EPN (-0.2106, -78.4889)
* **Precondiciones:** Aplicación Android en ejecución, conexión activa a internet y servicios de localización habilitados.

## 📝 Evaluación de Resultados

### Resultado Esperado
Los campos de texto de la interfaz deben actualizarse de forma automática con las direcciones o coordenadas seleccionadas, desplegando los marcadores visuales correspondientes sobre el mapa.

### Resultado Obtenido
Los puntos se registraron en la interfaz de Kotlin de manera inmediata y sin retrasos. Los marcadores visuales se fijaron y renderizaron correctamente en las coordenadas geográficas especificadas.