# SISTEMA DE INFORMACIÓN GESTIÓN DE RIESGO EN SALUD

Monitorear la Calidad y la gestión del riesgo en la prestación de servicios de salud en las IPS de mediana y  alta complejidad con las  6 patologías de la CAC.  ( ERC, VIH, CÁNCER, HEMOFILIA, ARTRITIS REUMATOIDE, ENFERMEDADES HUÉRFANAS).

## 1. MODELADO DEL SISTEMA DE INFORMACIÓN ALTO COSTO

### 1.1 ACTORES GESTIÓN CUENTA DE ALTO COSTO

![Con titulo](img/ActoresAltoCosto.jpg "Actores")

### 1.2 IDENTIFICACIÓN DE LOS CASOS DE USO GESTIÓN CUENTA DE ALTO COSTO



| Número | Procesos del Sistema de Información |
| ------ | ----------------------------------- |
| 1      | Solicitar Red                       |
| 2      | Entrega Red                         |
| 3      | Planear CAC                         |
| 4      | Organizar CAC                       |
| 5      | Ajustar CAC                         |
| 6      | Evaluar CAC                         |
| 7      | Controlar CAC                       |
| 8      | Interna y/o Externa                 |
| 9      | Auditoria HC                        |
| 10     | Analizar Casos Clínicos             |
| 11     | Evaluar eventos adversos            |
| 12     | Seguimiento PM                      |
| 13     | Realizar Auditoria                  |
| 14     | Solicitar Información               |
| 15     | Entrega Información                 |
| 16     | Recibir Información Prestador       |
| 17     | Consolida Información               |
| 18     | Llevar registro                     |
| 19     | Generar plano                       |
| 20     | Seguimiento nominal                 |
| 21     | Informe no enviado                  |
| 22     | Entrega información                 |
| 23     | Generar archivo por paciente        |
| 24     | Verificar usuarios                  |
| 25     | Consolida información               |
| 26     | Seguimiento nominal                 |
| 27     | Diligenciar novedad                 |
| 28     | Cargar plano                        |
| 29     | Verificación dato                   |
| 30     | Listado Usuarios                    |
| 31     | Omitidos                            |
| 32     | Compartidos                         |
| 33     | Duplicados                          |
| 34     | Cargar HC solicitadas               |
| 35     | Documentar                          |
| 36     | Eliminar usuario                    |
| 37     | Solicitar HC                        |
| 38     | Participar mesa                     |
| 39     | Organizar soportes                  |
| 40     | Entrega información                 |
| 41     | Soportar auditoria CAC              |
| 42     | Informe auditoria realizada         |
| 43     | Elabora informe trimestral          |

### 1.3 DESCRIPCIÓN DEL DIAGRAMA DE CASOS DE USO GESTIÓN CUENTA DE ALTO COSTO
| | |
| - | - |
| **1. Caso de Uso** | Gestión Cuenta de Alto Costo |
| **2. Descripción** | Monitorear la Calidad y la gestión del riesgo en la prestación de servicios de salud en las IPS de mediana y  alta complejidad con las  6 patologías de la CAC.  (ERC, VIH, CÁNCER, HEMOFILIA, ARTRITIS REUMATOIDE, ENFERMEDADES HUÉRFANAS) |
| **3. Actor(es)**   | **CoordinadorCAC** Coordinador de la Cuenta de Alto Costo, **P.U.CAC** Profesional Universitario de la Cuenta de Alto Costo, Auxiliar Salud Publica, **P.U.Referencia** Profesional Universitario de Referencia, Estadística, Contrataciones, Aseguramiento, **CAC** Cuenta de Alto Costo, Prestadores, Seguimiento Afiliados   |
| **4. Pre Condiciones** | Contar con red contratada  |
| **5. Pos Condiciones** | Archivo reportado, seguimiento nominal de los afiliados priorizados, indicadores y redistribución de recursos|
| **6. Flujo de Eventos** |
| *Actor(es)* | *Sistema* |
| 1. El Coordinador de la Cuenta de Alto Costo solicita la red prestadores actualizada y vigente|  |
| 2. Contrataciones, entrega la red de prestadores |  |
| 3. El Coordinador de la Cuenta de Alto Costo una vez recibida la red, planea, organiza, ajusta, evaluá y controla las actividades a desarrollar en la Coordinación de CAC  |  |
| 4. El Coordinador de la Cuenta de Alto Costo y el Profesional Universitario de AC, realizan auditoria de HC interna o externa a los prestadores |   |
| 5. El Coordinador de la Cuenta de Alto Costo analiza casos clínicos   |  |
| 6. El Coordinador de la Cuenta de Alto Costo analiza eventos adversos  |  |
| 7. El Coordinador de la Cuenta de Alto Costo Realiza seguimiento a los Planes de Mejoramiento |  |
| 8. El Coordinador de la Cuenta de Alto Costo y el Profesional Universitario de AC realizan auditorias adherencia y calidad del dato a la red de mediana y alta complejidad  | |
| 9. El Profesional Universitario de AC solicita información: a Prestadores, Estadística, Seguimiento afiliados |  | 
| 10. Prestadores, Estadística, Seguimiento afiliados, entregan la información |  | 
| 11. Los prestadores acceden al modulo   |12. Muestra pantalla inicial donde se hace la búsqueda por numero de cedula del afiliado (ver interfaz I001)|
|13. Muestra una ventana con los datos generales del afiliado (Ver interfaz I002)| |
|14. El prestador selecciona la opción Registrar ERC (Ver interfaz I002)|15. Muestra el formulario de captura (Ver interfaz I003)|
| 16. El prestador diligencia los datos que le aplican|17. Guarda los datos (Ver interfaz I004)|
| 18. El Auxiliar de Salud Publica consolida la información y lleva el registro de cada uno de los prestadores que suministro la información | |
| 19. El Auxiliar de Salud Publica identifica en el registro que prestadores no reportaron la información y envia oficio por segunda vez al prestador  |
| 20. El Auxiliar de Salud Publica entrega la información consolidada al Profesional Universitario de AC y al Coordinador de la Cuenta de Alto Costo para realizar el seguimiento de manera nominal de los afiliados|
| 21. El Auxiliar de Salud Publica genera y organiza los archivos enviados por los diferentes actores en carpeta por cada uno de los afiliados | |
| 22. El Profesional Universitario de AC realiza la consolidación teniendo en cuenta cada una de las patologías a reportar  | |
| 23. El Profesional Universitario de AC envia a la coordinación de afiliaciones y registro el consolidado para verificar el estado de afiliación de cada uno de los usuarios | |
| 24. La coordinación de afiliaciones y registro entrega las novedades presentadas en la BD | |
| 25. El Profesional Universitario de AC diligencia las novedades presentadas antes de hacer el envío a la CAC| |
| 26. El Profesional Universitario de AC genera el plano y lo carga a través del sitio web de la CAC, teniendo en cuenta el periodo establecido para reporte de cada una de las patologías. | |
| 27. La CAC retroalimenta los errores presentados en el cargue de la patología respectiva | |
| 28. El Profesional Universitario de AC accede al sitio de la CAC y descarga los posibles errores | |
| 29. El Profesional Universitario de AC corrige los errores y vuelve a cargar el archivo a través del sitio web de la CAC hasta obtener un cargue satisfactorio| |
| 30. El Profesional Universitario de AC verifica el listado de los usuarios que se encuentran compartidos, omitidos, duplicados el cual es suministrado por la CAC | |
| 31. El Profesional Universitario de AC solicita a la coordinación de afiliaciones y registro certificación de afiliación por cada unos de los registros compartidos | |
| 32. El Profesional Universitario de AC solicita a los prestadores y/o seguimiento afiliados copia de la HC | |
| 33. El Profesional Universitario de AC elabora oficio para la eliminación de los registros que no corresponden a la entidad y es enviado a la CAC | |
| 34. El coordinador de la CAC participa en la mesa de compartidos donde sustenta los soportes entregados por el Profesional Universitario de AC | |
| 35. El Profesional Universitario de AC solicita la HC a los prestadores | |
| 36. Los prestadores y seguimiento afiliados entregan la información solicitada| |
| 37. El Auxiliar de Salud Publica organiza la información de acuerdo a la patología y entrega al profesional universitario de AC| |
| 38. El Profesional Universitario de AC una vez consolidada la información realiza el cargue de las HC a través del correo electrónico designado por la CAC| |
| 39. El Coordinador de la CAC el Profesional Universitario de AC sustentan la auditoria a la CAC| |
| 40. El Coordinador de la CAC elabora informe del resultado de la visita | |
| 41. El coordinador de la CAC el Profesional Universitario de AC elaboran informes trimestral y anuales. | |
| **7. Requerimiento Asociado** | R001, R002, R003 |
| **8. Interfaz de Usuario Asociada** | I001, I002, I003 |
| **9. Formato de Usuario Asociado** | F001, F002, F003, F004, F005, F006, F007 |

### 1.4 MODELADO VISUAL DEL CASO DE USO GESTIÓN CUENTA DE ALTO COSTO

![Con titulo](img/FlujoAltoCosto.jpg "Caso de uso")

## 2. ESPECIFICACIÓN DEL SISTEMA DE INFORMACIÓN GESTIÓN CUENTA DE ALTO COSTO

| Término | Descripción                       |
| ------- | --------------------------------- |
| ERC     | Enfermedad Renal Crónica          |
| VIH     | Virus de Inmunodeficiencia Humana |
| CAC     | Cuenta de Alto Costo              |
| HC      | Historia Clínica                  |
| BD      | Base de Datos                     |


## 3. ESPECIFICACIÓN DE REQUERIMIENTOS

| | | |
| - | - | - |
| **N°** | **Tipo** | **Descripción** |
| R001 | Proceso | Red prestadora |
| R002 | Proceso | Normatividad vigente |
| R003 | Proceso | Instructivos entregados por la CAC |

## 4. ESPECIFICACIÓN DE LA INTERFACE DE USUARIO

| |
| - |
| **1. Número** |
| I001 |
| **2. Propósito de la Interfaz** |
| Busca afiliado para registrar y/o actualizar |
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/AltoCosto1.jpg "Búsqueda") |

| |
| - |
| **1. Número** |
| I002 |
| **2. Propósito de la Interfaz** |
| Muestra datos generales del afiliado e ingresa al formulario |
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/AltoCosto2.jpg "Registra datos") |


| |
| - |
| **1. Número** |
| I003 |
| **2. Propósito de la Interfaz** |
| Registrar información general relacionada con las variables clínicas y paraclínicas de las enfermedades precursoras |
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/AltoCosto3.jpg "Registro") |


### 4.1 IDENTIFICACIÓN DE PERFILES Y DIÁLOGOS

| |
| - |
| **1. Nombre del Perfil** |
| Auxiliar |
| **2. Opciones a las que tiene Acceso**|
| Registrar ERC|
| **3. Tipo de Acceso** |
| Registrar, modificar, reporte, consultar  |

### 4.2 ESPECIFICACIÓN DE FORMATOS DE USUARIO

| Número | Nombre del Formato                                                    |
| ------ | --------------------------------------------------------------------- |
| F001   | Formato Auditoria ERC                                                 |
| F002   | Formato Auditoria VIH                                                 |
| F003   | Formato Auditoria Artritis                                            |
| F004   | Formato Auditoria Cáncer                                              |
| F005   | Formato Auditoria Hemofilia                                           |
| F006   | Formato Gestión del Riesgo por prestador                              |
| F007   | Formato Matriz de Gestión de Riesgo de Pacientes con patologías de AC |