# SISTEMA DE INFORMACIÓN GESTIÓN DE RIESGO EN SALUD

Garantizar que los afiliados a EPS - I Mallamas reciban servicios de protección especifica y detección temprana, de acuerdo a la identificación del riesgo contemplados en la Normatividad vigente

## 1. MODELADO DEL SISTEMA DE INFORMACIÓN

### 1.1 ACTORES REPORTE DE NOVEDADES

![Con titulo](img/ActoresNovedades.jpg "Actores")

### 1.2 IDENTIFICACIÓN DE LOS CASOS DE USO REPORTE DE NOVEDADES

| Número | Procesos del Sistema de Información |
| ------ | ----------------------------------- |
| 1      | Solicitar novedades                 |
| 2      | Recibir información                 |
| 3      | Validar información                 |
| 4      | Generar plano                       |
| 5      | Colocar firma digital               |
| 6      | Reportar cargue o correcciones      |

### 1.3 DESCRIPCIÓN DEL DIAGRAMA DE CASOS DE USO REPORTE DE NOVEDADES
| | |
| - | - |
| **1. Caso de Uso** | Reporte de novedades |
| **2. Descripción** | Actualizar los datos de identificación de los afiliados |
| **3. Actor(es)**   | Auxiliar de Salud Publica, Aseguramiento, Estadística |
| **4. Pre Condiciones** | Contar con las novedades de aseguramiento |
| **5. Pos Condiciones** | Realizar reporte de novedades presentadas|
| **6. Flujo de Eventos** |
| *Actor(es)* | *Sistema* |
| 1. Auxiliar de Salud Publica, solicita novedades al área de aseguramiento teniendo en cuenta los registros del trimestre anterior|  |
| 2. Aseguramiento, entrega las novedades presentadas en los documentos de identidad de los afiliados |  |
| 3. Auxiliar de salud publica valida la información entregada |4. Incluir la información en archivo plano |
| 5. Auxiliar de salud publica guarda la información|  |
| 7. Auxiliar de salud publica remite el archivo al área de estadística  |  |
| **7. Requerimiento Asociado** | R001, R002 |
| **8. Interfaz de Usuario Asociada** | |
| **9. Formato de Usuario Asociado** | F001, F002 |

### 1.4 MODELADO VISUAL DEL CASO DE USO REPORTE DE NOVEDADES

![Con titulo](img/FlujoNovedades.jpg "Caso de uso")

## 2. ESPECIFICACIÓN DEL SISTEMA DE INFORMACIÓN REPORTE DE NOVEDADES

| Término | Descripción |
| ------- | ----------- |
|         |             |
|         |             |

## 3. ESPECIFICACIÓN DE REQUERIMIENTOS

| | | |
| - | - | - |
| **N°** | **Tipo** | **Descripción** |
| R001 | Proceso | Novedades presentadas |
| R002 | Proceso | Resolución 4505 de 2012 |


## 4. ESPECIFICACIÓN DE LA INTERFACE DE USUARIO

| |
| - |
| **1. Número** |
| I001 |
| **2. Propósito de la Interfaz** |
| |
| **3. Gráfica de la Interfaz**|
|  |

### 4.1 IDENTIFICACIÓN DE PERFILES Y DIÁLOGOS

| |
| - |
| **1. Nombre del Perfil** |
| |
| **2. Opciones a las que tiene Acceso**|
| |
| **3. Tipo de Acceso** |
|  |

### 4.2 ESPECIFICACIÓN DE FORMATOS DE USUARIO

| Número | Nombre del Formato           |
| ------ | ---------------------------- |
| F001   | Formato Archivo de novedades |
| F002   | Archivo plano de novedades   |
