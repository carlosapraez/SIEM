# SISTEMA DE INFORMACIÓN GESTIÓN DE RIESGO EN SALUD

Llevar en forma sistemática y oportuna la información de los eventos de notificación obligatoria que afectan a la población afiliada a MALLAMAS EPS- INDÍGENA, realizar la gestión del riesgo individual, análisis de la información y levantamiento de indicadores que permita establecer acciones de control y prevención de los Eventos de Interés en Salud Pública EISP según retroalimentación del INS - SIVIGILA

## 1. MODELADO DEL SISTEMA DE INFORMACIÓN

### 1.1 ACTORES VIGILANCIA EPIDEMIOLÓGICA

![Con titulo](img/ActoresVigilanciaEpidemiologica.jpg "Actores")

### 1.2 IDENTIFICACIÓN DE LOS CASOS DE USO VIGILANCIA EPIDEMIOLÓGICA


| Número | Procesos del Sistema de Información          |
| ------ | -------------------------------------------- |
| 1      | Solicitud retroalimentación                  |
| 2      | Notificación actualizaciones                 |
| 3      | Configurar SIVIGILA                          |
| 4      | Validar Usuario                              |
| 5      | Migrar Información                           |
| 6      | Notificación por correo electrónico          |
| 7      | Descarga retroalimentación                   |
| 8      | Consolidación información planos             |
| 9      | Exportar información a Excel                 |
| 10     | Cruce Datos BDUA vs SIVIGILA                 |
| 11     | Reporte inconsistencias                      |
| 12     | Ajuste información                           |
| 13     | Exportar información inconsistencias a plano |
| 14     | Envío Inconsistencias al INS                 |
| 15     | Organizar información                        |
| 16     | Análisis información seguimiento             |
| 17     | Elaborar Oficio Regionales y líderes         |
| 18     | Prioriza eventos a criterios de caso         |
| 19     | Seguimiento evento                           |
| 20     | Unidad análisis                              |
| 21     | Verificar ajuste SIVIGILA                    |
| 22     | Seguimiento al Plan de mejora                |
| 23     | Entrega Plan de mejora                       |
| 24     | Elabora informe trimestral                   |
| 25     | Oficiar Prestador                            |

### 1.3 DESCRIPCIÓN DEL DIAGRAMA DE CASOS DE USO VIGILANCIA EPIDEMIOLÓGICA
| | |
| - | - |
| **1. Caso de Uso** | Vigilancia Epidemiológica |
| **2. Descripción** | Es la recolección y análisis de los datos registrados en forma sistemática, periódica y oportuna, convertidos en información integrada para su divulgación, intervención, control y prevención de los EISP|
| **3. Actor(es)**   | Profesional Universitario de Sistemas, Líder Vigilancia, líderes de las dimensiones, INS, Prestadores |
| **4. Pre Condiciones** | Contar con el aplicativo y planos suministrados por el Instituto Nacional de Salud (INS) |
| **5. Pos Condiciones** | Tomar acciones de mejora para prevenir los EISP|
| **6. Flujo de Eventos** |
| *Actor(es)* | *Sistema* |
| 1. Profesional Universitario de Sistemas elabora oficio para ser remitido al Instituto Nacional de Salud solicitando la retroalimentación de las semanas epidemiológicas.| |
| 2. El Instituto Nacional de Salud en el caso de presentarse una actualización en el software, remitirá a la EAPB los instaladores respectivos a través del correo electrónico.|  |
| 3. El Profesional universitario de Sistemas una vez recibida la actualización, procede hacer la instalación respectiva en el equipo |4. Actualización SIVIGILA. ||
| 5. El Profesional Universitario de Sistemas ingresa a SIVIGILA | 6. Muestra la pantalla de inicio de sesión  |
|7. El Profesional Universitario de Sistemas accede a SIVIGILA con su usuario y contraseña y migra la información de acuerdo a las indicaciones suministradas por el INS  | | |
| 8. El Instituto Nacional de Salud Notifica a través del correo electrónico la llegada de las semanas epidemiológicas |9. Descarga los archivos del correo electrónico de la SSP|
| 10. El Profesional Universitario de Sistemas realiza la consolidación de información de los planos, la cual se realiza a través del menú Procesos, recepción y transferencias de archivos planos, recepción validación consolidación. (Ver interfaz 1)|  11. Muestra la ventana de seleccionar los planos. (Ver interfaz 2|
| 12. El Profesional Universitario de Sistemas, busca la ubicación de los archivos y selecciona el archivo de control. (Ver interfaz 3) | 13. Carga al sistema. (Ver interfaz 4) |
|14.  El Profesional Universitario de Sistemas exporta la información a través del menú Procesos, recepción y transferencias de archivos planos, retroalimentación IPS para análisis de datos.XLS (Ver interfaz 5)  | 15. Muestra la ventana de exportar información en excel. (Ver interfaz 6)|
|16. El Profesional Universitario de Sistemas diligencia los datos solicitados y da clic en generar. (Ver interfaz 6)  | 17. Genera archivo Excel|
| 18. El Profesional Universitario de Sistemas realiza el cruce de datos de BDUA Vs SIVIGILA identificando quien pertenece a la EAPB-I Mallamas,  |19. A través de Excel|
| 20. El Profesional Universitario de Sistemas ingresa a SIVIGILA el reporte de inconsistencias identificando a que EAPB corresponde los usuarios que no se encontraron en BDUA, a través de la ficha individual (Ver interfaz 7) |21. Abre la ficha individual de cada usuario. (Ver interfaz 8) |
| 22. El Profesional Universitario de Sistemas, da clic en ajustar, acepta la advertencia de modificar, ingresa la semana y el código de la EAPB a la cual pertenece (Ver interfaz 9)|23. Guarda los datos|
|24. El Profesional Universitario de Sistemas, exporta la información de inconsistencias a plano a través del menú (Ver interfaz 10) |25. Genera plano |
|26. El Profesional Universitario de Sistemas envia los planos al INS a través del correo electrónico de SSP |27. Muestra la ventana de envío|
|28. El Profesional Universitario de Sistemas organiza la información desagregando cada evento.  |29. Muestra las hojas de Excel|
|30. El Profesional Universitario de vigilancia en salud pública elabora oficio a regionales y las lideres de cada dimensión para el respectivo seguimiento ||
|31. El Profesional universitario de vigilancia en salud pública realiza el análisis de la información y prioriza los eventos sujetos a seguimiento e intervención  ||
|32. El Profesional universitario de vigilancia en salud pública revisa los eventos priorizados en el software SIVIGILA para determinar calidad del dato cumplimiento de la definición operativa de caso presentado en la semana de notificación||
|33. El Profesional universitario de vigilancia en salud pública si el evento cumple con los criterios de definición operativa de cada caso se realiza el  seguimiento del evento o realiza la unidad de análisis||
|34. El Profesional universitario de vigilancia en salud pública si el evento no cumple con los criterios de definición operativa de cada caso se oficializa al prestador de servicios para que realice el ajuste del evento||
|35. El Profesional universitario de vigilancia en salud pública verifica en sivigila la notificación de ajuste del evento||
|36. El Profesional universitario de vigilancia en salud pública realiza el seguimiento o unidad de análisis del evento del cual se efectúo el ajuste en el software SIVIGILA||
|37. El Profesional universitario de vigilancia en salud pública realiza la presentación de los eventos que requieren ser analizados en COVE institucional | |
| 38. El Profesional universitario de vigilancia en salud pública realiza la convocatoria de los integrantes del COVE institucional , prestadores involucrados, entes municipales y otros actores si el caso lo requiere | |
|39. El Profesional universitario de vigilancia en salud pública organiza la ejecución del análisis del evento en el COVE, levanta acta de reunión y diseño de plan de mejora concertado con los asistentes | |
|40. El Profesional universitario de vigilancia en salud pública hace entrega oficial del plan de mejoramiento a los asistentes  | |
|41. El Profesional universitario de vigilancia en salud pública realiza seguimiento al plan de mejoramiento | |
|42. El Profesional universitario de vigilancia en salud pública realiza el informe trimestral| 43. Diligencia formato en Excel| 
| **7. Requerimiento Asociado** | R001, R002, R003 |
| **8. Interfaz de Usuario Asociada** | I001, I002, I03, I004, I005, I006, I007, I008, I009, I010,|
| **9. Formato de Usuario Asociado** | F001 |

### 1.4 MODELADO VISUAL DEL CASO DE USO VIGILANCIA EPIDEMIOLÓGICA

![Con titulo](img/Flujovigilancia.jpg "Caso de uso")

## 2. ESPECIFICACIÓN DEL SISTEMA DE INFORMACIÓN VIGILANCIA EPIDEMIOLÓGICA

| Término | Descripción                              |
| ------- | ---------------------------------------- |
| BD      | Base de Datos                            |
| SSP     | Subdirección de Salud Publica            |
| INS     | Instituto Nacional de Salud              |
| EISP    | Enfermedades de Interés en Salud Publica |
| COVE    | Comité de vigilancia Epidemiológica      |
| BDUA    | Base de Datos Única de Afiliados         |
| EPS     | Empresa Promotora de Salud               |

## 3. ESPECIFICACIÓN DE REQUERIMIENTOS

| | | |
| - | - | - |
| **N°** | **Tipo** | **Descripción** |
| R001 | Proceso | Red prestadora |
| R002 | Proceso | Archivos Planos |
| R003 | Proceso | Software SIVIGILA |
| R003 | Proceso | Normatividad vigente |

## 4. ESPECIFICACIÓN DE LA INTERFACE DE USUARIO

| |
| - |
| **1. Número** |
| I001 |
| **2. Propósito de la Interfaz** |
| Cargar archivos planos a SIVIGILA |
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Vigilancia1.jpg "Cargar datos") |

| |
| - |
| **1. Número** |
| I002 |
| **2. Propósito de la Interfaz** |
| Seleccionar archivos planos a SIVIGILA |
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Vigilancia2.jpg "Seleccionar datos") |

| |
| - |
| **1. Número** |
| I003 |
| **2. Propósito de la Interfaz** |
| Seleccionar archivo de control |
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Vigilancia3.jpg "Archivo de control") |

| |
| - |
| **1. Número** |
| I004 |
| **2. Propósito de la Interfaz** |
| Importar, enviar datos a la BD de SIVIGILA |
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Vigilancia4.jpg "Envío archivos a BD") |

| |
| - |
| **1. Número** |
| I005 |
| **2. Propósito de la Interfaz** |
| Exportar datos a Excel |
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Vigilancia5.jpg "Envío archivos a BD") |

| |
| - |
| **1. Número** |
| I006 |
| **2. Propósito de la Interfaz** |
| Exporta datos a Excel con los datos registrados en BD|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Vigilancia6.jpg "Genera Archivo Excel ") |

| |
| - |
| **1. Número** |
| I007 |
| **2. Propósito de la Interfaz** |
| Ingresa a la ficha individual|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Vigilancia7.jpg "Ingreso ficha") |

| |
| - |
| **1. Número** |
| I008 |
| **2. Propósito de la Interfaz** |
| Contenido de la ficha individual|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Vigilancia8.jpg "Contenido ficha") |

| |
| - |
| **1. Número** |
| I009 |
| **2. Propósito de la Interfaz** |
| Ingresa semana y EAPB a la cual pertenece el usuario|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Vigilancia9.jpg "Diligenciar ficha") |

| |
| - |
| **1. Número** |
| I010 |
| **2. Propósito de la Interfaz** |
| Genera plano con el ajuste respectivo|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Vigilancia10.jpg "Genera plano") |


### 4.1 IDENTIFICACIÓN DE PERFILES Y DIÁLOGOS

| |
| - |
| **1. Nombre del Perfil** |
| Administrador |
| **2. Opciones a las que tiene Acceso**|
| Notificación Datos Básicos|
| **3. Tipo de Acceso** |
| Modificar, generar e imprimir |

### 4.2 ESPECIFICACIÓN DE FORMATOS DE USUARIO

| Número | Nombre del Formato     |
| ------ | ---------------------- |
| F001   | Evaluación Prestadores |
|        |                        |