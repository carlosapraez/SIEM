# SISTEMA DE INFORMACIÓN GESTIÓN DE RIESGO EN SALUD

Identificación y priorización de los problemas en salud, para todos ámbitos territoriales (departamentales, distritales, municipales), donde la EAPB esté habilitada dentro del marco de coordinación intersectorial y transectorial establecido por el plan decenal de salud publica (PDSP) que deben concurrir en la formulación de los planes territoriales de salud.

## 1. MODELADO DEL SISTEMA DE INFORMACIÓN

### 1.1 ACTORES CARACTERIZACIÓN DE LA POBLACIÓN AFILIADA

![Con titulo](img/ActoresCaracterizacion.jpg "Actores")

### 1.2 IDENTIFICACIÓN DE LOS CASOS DE USO CARACTERIZACIÓN DE LA POBLACIÓN AFILIADA

| Número | Procesos del Sistema de Información                                         |
| ------ | --------------------------------------------------------------------------- |
| 1      | Alistar información                                                         |
| 2      | Crear cronograma y tiempos de entrega                                       |
| 3      | Identificar fuentes de información                                          |
| 4      | Conformar grupo de trabajo                                                  |
| 5      | Descarga indicadores                                                        |
| 6      | Consolidación indicadores matriz priorización                               |
| 7      | Análisis, identificación y priorización                                     |
| 8      | Construcción plano                                                          |
| 9      | Envío plano                                                                 |
| 10     | Formular acciones de intervención e indicadores para los grupos priorizados |
| 11     | Concertar articulación con Entes                                            |
| 12     | Envío plantilla CEO                                                         |
| 13     | Recepción, análisis documento IFASORIS                                      |
| 14     | Elaboración documento final                                                 |
| 15     | Socialización documento                                                     |

### 1.3 DESCRIPCIÓN DEL DIAGRAMA DE CASOS DE USO CARACTERIZACIÓN DE LA POBLACIÓN AFILIADA
| | |
| - | - |
| **1. Caso de Uso** | Caracterización de la población afiliada |
| **2. Descripción** | Identificación y priorización de las necesidades en salud|
| **3. Actor(es)**   | **Subdirector SP:** Subdirector de Salud Publica, **P.U.Sistemas** Profesional Universitario de Sistemas, **CoordinadorGSPyABC:** Coordinador de Salud Publica y Auditoria de Baja Complejidad, SISPRO, Estadística, **AdecuaciónSC** Adecuación Socio Cultural |
| **4. Pre Condiciones** | Tener los lineamientos del Ministerio de Salud y Protección Social, contar con la normatividad vigente, equipo de trabajo, fuentes información.|
| **5. Pos Condiciones** | Generar documento de análisis de caracterización poblacional a nivel nacional, departamental, distrital|
| **6. Flujo de Eventos** |
| *Actor(es)* | *Sistema* |
| 1. Subdirector de Salud publica alistar la información|  |
| 2. Preparación de las condiciones y actuales necesidades para ejecución del proceso de caracterización |  |
|3. Sondeo de información y recursos||| 
|4. Profesional Universitario de Sistemas Elabora cronograma y tiempos de entrega a Subdirección de SSP y Coordinación de Gestión de Salud Publica  y auditoria de la baja complejidad |||
|5. Profesional Universitario de Sistemas identifica las fuentes de información como son: RIPS, RUAF, Sivigila, Suficiencia de UPC, Red Contratada, BDUA|||
| 6. Coordinación de Gestión de Salud Publica  y auditoria de la baja complejidad identificación de interesados, involucrados y afectados |  |
| 7. Conformación de grupos de trabajo. | |
| 8. Profesional Universitario de Sistemas descarga indicadores SISPRO desde el sitio web | |
| 9. Profesional Universitario de Sistemas consolida indicadores en la matriz de priorización  | |
|10. Subdirector de Salud Pública, Coordinador de Gestión de Salud Publica y Auditoria de Baja Complejidad, Profesional Universitario de Sistemas analizan, identifican y priorizan    | |
| |11. Profesional Universitario de sistemas construye el archivo plano en Excel y lo envía a estadística |
| 12. El funcionario de estadística, coloca la firma digital y envía el archivo por PISIS | |
| 13. Subdirector de Salud Pública y Coordinador de Gestión de salud pública y auditoria de baja complejidad, formulan acciones de intervención e indicadores para los grupos de riesgo priorizados | |
| |14. Profesional Universitario de Sistemas envía la plantilla de CEO al Ministerio de Salud y Protección Social mediante correo electrónico|
| 15. Subdirector de Salud Pública y coordinador de gestión de Salud publica y auditoria de baja complejidad realiza la concertación del CEO con los entes  departamentales y municipales según convocatoria| |
|16. Subdirector de Salud Pública solicita documento IFASORIS a la oficina de adecuación sociocultural|||
| |17. Subdirector de Salud Pública y Coordinador de Gestión de salud pública y auditoria de baja complejidad y el Profesional Universitario de Sistemas elaboran el documento final de caracterización |
|| 18. Subdirector de Salud Pública y coordinador de gestión de Salud publica y auditoria de baja complejidad socializan el documento de la caracterización|
| **7. Requerimiento Asociado** | R001, R002, R003, R004, R005, R006 |
| **8. Interfaz de Usuario Asociada** | |
| **9. Formato de Usuario Asociado** | F001, F002, F003 |

### 1.4 MODELADO VISUAL DEL CASO DE USO CARACTERIZACIÓN DE LA POBLACIÓN AFILIADA

![Con titulo](img/FlujoCaracterizacion.jpg "Flujo Caracterización")

## 2. ESPECIFICACIÓN DEL SISTEMA DE INFORMACIÓN CARACTERIZACIÓN DE LA POBLACIÓN AFILIADA

| Término  | Descripción                                                |
| -------- | ---------------------------------------------------------- |
| EAPB     | Empresa Administradora de Planes de Beneficio              |
| PDSP     | Plan Decenal de Salud Publica                              |
| BDUA     | Base de Datos Única de Afiliados                           |
| RIPS     | Registro Individual de Prestación de Servicios             |
| RUAF     | Registro Único de Afiliados                                |
| SIVIGILA | Sistema de Información de Vigilancia Epidemiológica        |
| UPC      | Unidad Pago por Capitación                                 |
| SISPRO   | Sistema Integrado de Información para la Protección Social |
| CEO      | Componente Estratégico y Operativo                         |
| MSPS     | Ministerio de Salud y Protección Social                    |

## 3. ESPECIFICACIÓN DE REQUERIMIENTOS

| | | |
| - | - | - |
| **N°** | **Tipo** | **Descripción** |
| R001 | Proceso | Normatividad vigente |
| R002 | Proceso |Guía metodológica  |
| R003 | Proceso | Lineamientos MSPS |
| R004 | Proceso | Fuentes de información |
| R005 | Proceso |Instrumentos definidos por el MSPS  |
| R006 | Proceso |Matriz de priorización definida por la entidad  |



## 4. ESPECIFICACIÓN DE FORMATOS DE USUARIO

| Número | Nombre del Formato                             |
| ------ | ---------------------------------------------- |
| F001   | Plantilla CEO                                  |
| F002   | Instrumentos definidos por el MSPS             |
| F003   | Matriz de priorización definida por la entidad |

