# SISTEMA DE INFORMACIÓN GESTIÓN DE RIESGO EN SALUD

Garantizar que los afiliados a EPS - I Mallamas reciban servicios de protección especifica y detección temprana, de acuerdo a la identificación del riesgo contemplados en la Normatividad vigente

## 1. MODELADO DEL SISTEMA DE INFORMACIÓN

### 1.1 ACTORES CONSOLIDACIÓN

![Con titulo](img/ActoresConsolidado.jpg "Actores Consolidado")

### 1.2 IDENTIFICACIÓN DE LOS CASOS DE USO DE CONSOLIDACIÓN


| Número | Procesos del Sistema de Información |
| ------ | ----------------------------------- |
| 1      | Entregar información consolidada    |
| 2      | Recibir información                 |
| 3      | Validar y corregir errores plano    |
| 4      | Revisa y aprueba                    |
| 5      | Generar Plano                       |
| 6      | Colocar firma digital               |
| 7      | Reportar cargue o correcciones      |


### 1.3 DESCRIPCIÓN DEL DIAGRAMA DE CASOS DE USO CONSOLIDACIÓN
| | |
| - | - |
| **1. Caso de Uso** | Consolidado |
| **2. Descripción** | Identifica las atenciones prestadas de manera nominal de la población afiliada |
| **3. Actor(es)**   | Proveedor software, Auxiliar de SSP, Coordinador de Promoción y Prevención y GR, Estadística|
| **4. Pre Condiciones** | Contar con la información radicada para poder obtener el consolidado |
| **5. Pos Condiciones** | Realizar reporte de las actividades de PE, DT y AEISP al MSPS |
| **6. Flujo de Eventos** |
| *Actor(es)* | *Sistema* |
| 1. Proveedor de Software entrega archivo consolidado|  |
| 2. Auxiliar de SSP recibe el archivo |3. Inicia la verificación y validación del archivo  |
| 4. El coordinador de PyP verifica, analiza y aprueba la información | |
| 5. El auxiliar de SSP genera el plano de acuerdo a las especificaciones de la normatividad| |
| 7. Auxiliar de SSP Notifica a Estadística  | 8. Estadística coloca la firma digital y envía el plano por PISIS a SISPRO|
| 9. Estadística informa si el archivo fue cargado o presento errores |  |
| 
| **7. Requerimiento Asociado** | R001, R002|
| **8. Interfaz de Usuario Asociada** |I001, I002, I003, I004|
| **9. Formato de Usuario Asociado** ||

### 1.4 MODELADO VISUAL DEL CASO DE USO CONSOLIDACIÓN

![Con titulo](img/FlujoConsolidacion.jpg "Flujo Consolidado")

## 2. ESPECIFICACIÓN DEL SISTEMA DE INFORMACIÓN CONSOLIDACIÓN

| Término | Descripción                                             |
| ------- | ------------------------------------------------------- |
| SSP     | Subdirección de Salud Publica                           |
| PISIS   | Plataforma Integrada de SISPRO                          |
| SISPRO  | Sistema Integral de Información de la Protección Social |

## 3. ESPECIFICACIÓN DE REQUERIMIENTOS

| | | |
| - | - | - |
| **N°** | **Tipo** | **Descripción** |
| R001 | Proceso | Fuentes de información |
| R002 | Proceso | Resolución 4505 de 2012 |


## 4. ESPECIFICACIÓN DE LA INTERFACE DE USUARIO

| |
| - |
| **1. Número** |
| I001|
| **2. Propósito de la Interfaz** |
| Iniciar sesión|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Contraseña1.jpg "Inicio sesión") |

| |
| - |
| **1. Número** |
| I002|
| **2. Propósito de la Interfaz** |
| Importar datos al validador|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Contraseña2.jpg "Importar datos") |

| |
| - |
| **1. Número** |
| I003|
| **2. Propósito de la Interfaz** |
| Validar datos|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Contraseña3.jpg "Valida") |

| |
| - |
| **1. Número** |
| I004|
| **2. Propósito de la Interfaz** |
| Indica y se exporta errores|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Contraseña5.jpg "Exporta errores") |

### 4.1 IDENTIFICACIÓN DE PERFILES Y DIÁLOGOS

| |
| - |
| **1. Nombre del Perfil** |
| Administrador|
| **2. Opciones a las que tiene Acceso**|
| validar contenido, exportar errores|
| **3. Tipo de Acceso** |
| Consultar |

### 4.2 ESPECIFICACIÓN DE FORMATOS DE USUARIO

| Número | Nombre del Formato |
| ------ | ------------------ |
|        |                    |
|        |                    |
|        |                    |