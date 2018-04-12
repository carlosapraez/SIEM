# SISTEMA DE INFORMACIÓN GESTIÓN DE RIESGO EN SALUD

Garantizar que los afiliados a EPS - I Mallamas reciban servicios de protección especifica y detección temprana, de acuerdo a la identificación del riesgo contemplados en la normativas vigente.

## 1. MODELADO DEL SISTEMA DE INFORMACIÓN

### 1.1 ACTORES

![Con titulo](img/Actores.jpg "Actores")

### 1.2 IDENTIFICACIÓN DE LOS CASOS DE USO

| Número | Procesos del Sistema de Información    |
| ------ | -------------------------------------- |
| 1      | Entrega Red de Prestadores             |
| 2      | Entrega BD de Afiliados                |
| 3      | Entrega reporte 4505                   |
| 4      | Recibir y Analizar la información      |
| 5      | Programar Actividades                  |
| 6      | Envió de la programación               |
| 7      | Aceptar o rechazar programación        |
| 8      | Hacer seguimiento de la programación   |
| 9      | Programar reunión concertación         |
| 10     | Solicitar Rips                         |
| 11     | Entregar Rips                          |
| 12     | Consultar y validar información        |
| 13     | Elaborar informe                       |
| 14     | Revisar y enviar informe               |
| 15     | Aceptar o rechazar informe             |
| 16     | Realizar plan de mejora                |
| 17     | Realizar ajustes                       |
| 18     | Programar Reunión                      |
| 19     | Recibir Plan de mejora                 |
| 20     | Realizar auditoria a Plan de mejora    |
| 21     | Recibir informe                        |
| 22     | Entregar informe de auditoria          |
| 23     | Notificar incumplimiento               |
| 24     | Remitir informe final para liquidación |


### 1.3 DESCRIPCIÓN DE LOS CASOS DE USO SEGUIMIENTO A LA GESTIÓN DEL RIESGO INDIVIDUAL

| | |
| - | - |
| **1. Caso de Uso** | SEGUIMIENTO A LA GESTIÓN DEL RIESGO INDIVIDUAL |
| **2. Descripción** | Garantizar que los afiliados a EPS - I Mallamas reciban servicios de protección especifica y detección temprana, de acuerdo a la identificación del riesgo  |
| **3. Actor(es)**   | Aseguramiento, Contrataciones, Auxiliares de Salud Publica, Coordinador Auditoria Baja Complejidad, Coordinador PyP, Prestadores,  Profesional Universitario de Salud Publica, Estadística |
| **4. Pre Condiciones** | Contar con la información requerida, red de prestadores, base de datos de afiliados  y reporte de 4505. |
| **5. Pos Condiciones** | Revisar si los prestadores cumplen con lo plasmado en los contratos para realizar su liquidación. |
| **6. Flujo de Eventos** |
| *Actor(es)* | *Sistema* |
| 1. El área de contrataciones enviá la red prestadora. |  |
| 2. El área de aseguramiento enviá BD de la población afiliada |  |
| 3. Auxiliar de salud publica enviá reporte de 4050 |  |
| 4. el auxiliar de Salud Publica Recibe y analiza la información enviada por las distintas áreas. | 5. El auxiliar de salud publica Programa actividades de pyp para prestadores en formato excel. |
| 6. El auxiliar de salud publica enviá la programación a los prestadores. |  |
| 7. El Prestador notifica si acepta o rechaza la programación enviada por el auxiliar de salud publica. |   |
| 8.el prestador notifica si acepta o rechaza la programación. | |
| 9. el prestador rechaza la programación, se hace nueva programación.  |  |
| 10. el coord. de PYP hace seguimiento a la programación  |  |
| 11. Coord. solicita rips al área de cuentas medicas | 12. El área de cuentas medicas enviá rips solicitados por el coord. PYP por correo electrónico. |
|  | 13. El profesional universitario de salud publica consulta y valida la información recibida a través de comparación de datos en Excel. |
| 14. El profesional universitario labora un informe según la validación de los datos |  |
| | 15. el profesional universitario enviá el informe al prestador a través de correo electrónico. |
| 16. El prestador notifica si acepta o rechaza el informe enviado por el profesional universitario |  |
| 17. el profesional universitario no acepta el informe se programa reunión |  |
|18. se realizan ajustes según sugerencias del prestador.   | 19. El coord. de PYP realiza plan de mejora en plantilla excel. |
| 20. Coord. auditoria BC recibe plan de mejora |    |
| 21. el coord. auditoria BC realiza auditoria al plan de mejora |    |
| 22. el coord. auditoria BC entrega informe según la auditoria realizada al plan de mejora |    |
| 23. el coord. PYP recibe informe sobre el plan de mejora | .  |
|24. el coordinador de pyp notifica si existe incumplimiento sobre el plan de mejora | 25. el coord. PYP remite informe al área de contrataciones para realizar la respectiva liquidación a través de oficio remitido por Orfeo.  |
| **7. Requerimiento Asociado** | R001, R002, R003, R004 |
| **8. Interfaz de Usuario Asociada** | <Colocar_Interfaz_Asociada> |

### 1.4 MODELADO VISUAL DE LOS CASOS DE USO

![Con titulo](img/gestion.jpg "Caso de uso")

## 2. ESPECIFICACIÓN DEL SISTEMA DE INFORMACIÓN

| Término | Descripción               |
| ------- | ------------------------- |
| BD      | Base de Datos             |
| PM      | Plan de mejora            |
| BC      | Baja Complejidad          |
| PU      | Profesional Universitario |

## 3. ESPECIFICACIÓN DE REQUERIMIENTOS

| | | |
| - | - | - |
| **N°** | **Tipo** | **Descripción** |
| R001 | Proceso | BD de afiliados |
| R002 | Proceso | Red prestadora |
| R003 | Proceso | Fuentes de información |
| R004 | Proceso | Rips |

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
