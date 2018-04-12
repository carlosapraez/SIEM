# SISTEMA DE INFORMACIÓN SEGUIMIENTO A LA GESTION DE RIESGO INDIVIDUAL

Garantizar que los afiliados a EPS - I Mallamas reciban servicios de protección especifica y detección temprana, de acuerdo a la identificación del riesgo contemplados en la normatividad vigente

## 1. MODELADO DEL SISTEMA DE INFORMACIÓN

### 1.1 ACTORES

![Con titulo](img/ActoresSeguimientoGRI.jpg "Actores")

### 1.2 IDENTIFICACIÓN DE LOS CASOS DE USO

| Número | Procesos del Sistema de Información                      |
| ------ | -------------------------------------------------------- |
| 1      | Entrega de red de prestadores           |
| 2      | Entrega de BD de afiliados              |
| 3      | Caracterización                         |
| 4      | Entrega reporte 4505                    |
| 5      | Recopilar información                   |
| 6      | Revisión y análisis de información      |
| 7      | Programar actividades                   |
| 8      | Envió plan de actividades               |
| 9      | Acepta o rechaza programación           |
| 10      | Programar reunión de concertación       |
| 11     | Hacer seguimiento a programación        |
| 12     | Consulta de actividades, procedimientos e intervenciones |
| 13     | Elaborar informe                         |
| 14     | Revisar y enviar informe                 |
| 15     | Aceptar o rechazar informe               |
| 16     | Programar reunión                        |
| 17     | Realizar ajustes                         |
| 18     | Realizar plan de mejora                  |
| 19     | Seguimiento y evaluación                 |
| 20     | Remitir informe para interventoria       |
| 21     | Envió informe final para liquidaciones   |


### 1.3 DESCRIPCIÓN DE LOS CASOS DE USO SEGUIMIENTO A LA GESTION DE RIESGO INDIVIDUAL

| | |
| - | - |
| **1. Caso de Uso** | Seguimiento Gestión del Riesgo Individual |
| **2. Descripción** | Garantizar que los afiliados a EPS - I Mallamas reciban servicios de protección especifica y detección temprana, de acuerdo a la identificación del riesgo contemplados en la normativas vigente |
| **3. Actor(es)**   | Contrataciones, Aseguramiento, P.U. Salud Publica, Auxiliar de salud Publica, Técnico en Sistemas, Coord. PyP y Gestión del Riesgo, P.U. de Sistemas y Prestadores |
| **4. Pre Condiciones** | Contar con BD de afiliados, Red de prestadores, Caracterización y reporte de 4505 |
| **5. Pos Condiciones** | Revisar si los prestadores cumplen con lo plasmado en los contratos para realizar su liquidación. |
| **6. Flujo de Eventos** |
| *Actor(es)* | *Sistema* |
| 1. El Téc. en sistemas recopila la información necesaria,Base de datos de Aseguramiento poblacional, caracterización, contratos de red prestadora y reporte 4505.   |  |
| 2. el Téc. en sistemas realiza revisión y análisis de la información  recopilada y de la normatividad vigente |  |
| 3. el Téc. en sistemas elabora programación de actividades. |  |
| 4. El téc. en sistemas envía la programación a la red prestadora de servicios de salud de baja complejidad |  |
| 5. Los prestadores notifican si aceptan o rechazan la programación enviada. |  |
| 6. Los prestadores rechazan la programación, se realiza una reunión para hacer concertación y programar nuevas fechas |  |
| 7. El coord. de PyP y gestión del riesgo individual realiza Seguimiento  a la ejecución de PE, DT  y atención de EISP  nominal por IPS de baja complejidad |  |
| 8.el P.U. de sistemas realiza consulta de actividades, procedimientos e intervenciones de protección específica, detección temprana  y atención de las EISP en las fuentes información utilizadas para el seguimiento |  |
| 9. El P.U. de sistemas elabora informe de ejecución de las actividades de PE,DT y atención de EISP por cada IPS de baja complejidad |  |
| 10. El P.U. genera reporte de acuerdo a resultados de indicadores de gestión de riesgo  |  |
| 11. El coord. de PyP y gestión del riesgo individual se encarga de revisar y enviar informe a la IPS de baja complejidad. |  |
| 12. Los prestadores notifican si aceptan o rechazan el informe  |  |
| 13. Los prestadores rechazan el informe, el coord. de PyP y gestión del riesgo individual genera reunión de concertación con los prestadores. |  |
| 14. El coord. de PyP y Gestión del Riesgo Individual ante las bajas coberturas solicita plan de mejora |  |
| 15. El coord. de PyP y gestión del riesgo individual realiza seguimiento y evaluación al plan de mejora. |  |
| El coord. de PyP y gestión del riesgo individual Remite al procedimiento de interventoria de contratos informe de prestadores que presentan bajas coberturas luego de seguimiento al plan de mejora y de aquellos que no han reportado la información |  |
| el coord. de PyP y gestión de riesgo individual Remite a coordinación de contrataciones el informe final de actividades programadas y ejecutadas por cada IPS para su correspondiente liquidación de contratos | |
| **7. Requerimiento Asociado** | R001, R002, R003, R004, R005, R006, R007, R008 |
| **8. Interfaz de Usuario Asociada** | <Colocar_Interfaz_Asociada> |

### 1.4 MODELADO VISUAL DE LOS CASOS DE USO

![Con titulo](img/SeguimientoGRI.jpg "Caso de uso")

## 2. ESPECIFICACIÓN DEL SISTEMA DE INFORMACIÓN

| Término            | Descripción             |
| ------------------ | ----------------------- |
| P.U  | Profesional Universitario |
| Téc. |Técnico |
| PYP  |Promoción y Prevención |
| EISP | Enfermedades de Interés de Salud Publica|
| PE   | Protección especifica |
| DT   | Detección temprana    |

## 3. ESPECIFICACIÓN DE REQUERIMIENTOS

| | | |
| - | - | - |
| **N°** | **Tipo** | **Descripción** |
| R001 | Físico | Base de Datos de población afiliada |
| R002 | Físico | Red Prestadora |
| R003 | Físico | Caracterización |
| R004 | Físico | Reporte 4505 |
| R005 | Físico | Programación de Actividades. |
| R006 | Físico | Plan de Mejora |
| R007 | Físico | Informe para interventoria |
| R008 | Físico | Informe final |

## 4. ESPECIFICACIÓN DE LA INTERFACE DE USUARIO

| |
| - |
| **1. Número** |
| <Colocar_Número> |
| **2. Propósito de la Interfaz** |
| <Colocar_Propósito> |
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Interfaz01.jpg "Interfaz de Usuario") |

### 4.1 IDENTIFICACIÓN DE PERFILES Y DIÁLOGOS

| |
| - |
| **1. Nombre del Perfil** |
| <Colocar_Nombre> |
| **2. Opciones a las que tiene Acceso**|
| <Describir_Las_Opciones_a_las_que_tiene_Acceso_el_perfil> |
| **3. Tipo de Acceso** |
| <Colocar_Tipo_Acceso> |