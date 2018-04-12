# SISTEMA DE INFORMACIÓN GESTIÓN DE RIESGO EN SALUD

Verificar la adherencia en guías, protocolos, programas y calidad de la información reportada en la red contratada de baja complejidad de acuerdo al modelo de atención integral e intercultural con enfoque de riesgo basado en individuo, familia y comunidad definido por la EPS-I Mallamas.

## 1. MODELADO DEL SISTEMA DE INFORMACIÓN AUDITORIA EN SALUD PUBLICA

### 1.1 ACTORES AUDITORIA EN SALUD PUBLICA

![Con titulo](img/ActoresAuditoriaSP.jpg "Equipo Auditores")

### 1.2 IDENTIFICACIÓN DE LOS CASOS DE USO AUDITORIA EN SALUD PUBLICA


| Número | Procesos del Sistema de Información  |
| ------ | ------------------------------------ |
| 1      | Solicitar red                        |
| 2      | Entrega red                          |
| 3      | Evaluación                           |
| 4      | Protocolos                           |
| 5      | Programas, calidad dato              |
| 6      | Guiás                                |
| 7      | Informe final de PE, DT              |
| 8      | Plan Auditorias y Cronograma salidas |
| 9      | Aprobación                           |
| 10     | Socializar cronograma                |
| 11     | Ajustar cronograma                   |
| 12     | Notificar prestador                  |
| 13     | Realizar visita                      |
| 14     | Crear acta de inicio                 |
| 15     | Aplicar listas de chequeo            |
| 16     | Consolida hallazgos y crea PM        |
| 17     | Crea acta final                      |
| 18     | Consolida informes y PM              |
| 19     | Verificación de la Fuente del Dato   |
| 20     | Cumple PM                            |
| 21     | Seguimiento PM                       |
| 22     | Cierra PM                            |
| 23     | Interventoría                        |

### 1.3 DESCRIPCIÓN DEL DIAGRAMA DE CASOS DE USO AUDITORIA EN SALUD PUBLICA
| | |
| - | - |
| **1. Caso de Uso** | Auditoria en Salud Publica |
| **2. Descripción** | Verificar la adherencia en guías, protocolos, programas y calidad de la información reportada en la red contratada de baja complejidad |
| **3. Actor(es)**   | Director Salud, **Director AF** Director Administrativo y Financiero, **CoordinadorGSPyAPN** Coordinador de Gestión de Salud Publica y Auditoria de Primer Nivel, Prestadores, Contrataciones, **Equipo Auditores Gestión del Riesgo** Equipo Auditores GR |
| **4. Pre Condiciones** | Contar con red contratada, Protocolos normatividad vigente, Listas de chequeo,Presupuesto, equipo Auditor GR. |
| **5. Pos Condiciones** | Informe de auditoria al prestador|
| **6. Flujo de Eventos** |
| *Actor(es)* | *Sistema* |
| 1. El Coordinador de Gestión Publica y Auditoria de Primer Nivel solicita red prestadora a contrataciones|  |
| 2. Contrataciones, entrega la red de prestadores |  |
| 3. El Coordinador de Gestión Publica y Auditoria de Primer Nivel realiza una autoevaluación en cuanto corresponde a protocolos, programas, calidad del dato y los informes finales de cumplimiento de PE, DT y realiza la priorización que amerite |  |
| 4. El Coordinador de Gestión Publica y Auditoria de Primer Nivel analiza los informes y elabora cronograma de los prestadores priorizados| 5. Generar Cronograma de Visitas Formato Excel  |
| 6. El Coordinador de Gestión Publica y Auditoria de Primer Nivel una vez elaborado el cronograma lo envia al director de salud y director administrativo y financiero de la EAPB-I Mallamas para su revisión y aprobación |  |
| 7. El Director de Salud y el director administrativo y financiero revisan el cronograma de no presentar ninguna novedad por parte de las direcciones, estas aprueban e informan al CoordinadorGSPyAPN |  |
| 8. El Director de Salud y el director administrativo y financiero de tener alguna novedad por parte de las direcciones estas no aprueban  e informan al CoordinadorGSPyAPN para que sea ajustado y remitido nuevamente el cronograma a las direcciones|  |
| 9. El CoordinadorGSPyAPN socializa el cronograma aprobado al equipo Auditores GR|  |
| 10. El CoordinadorGSPyAPN Revisa cronograma y Notifica a Prestador  |  |
| 11. El Prestador emite respuesta a notificación y se confirma visita |  |
| 12. Si el prestador emite respuesta negativa el CoordinadorGSPyAPN realiza el ajuste a la fecha de salida |  |
| 13. El CoordinadorGSPyAPN prepara documentación para la visita y asigna el equipo auditores GR|  |
| 14. Ver caso de uso [Verificación Fuente de Información](VerificacionDato.md) para la realización de la verificación de la fuente de información en sistema |  |
| 15. El Equipo de Auditores GR crean acta de inicio |16. El Equipo de Auditores GR Ejecuta la auditoria con listas de chequeo  |
| 17. El equipo de Auditores GR presenta los hallazgos encontrados en la auditoria y elabora plan de mejoramiento entre las partes |  |
| 18. El equipo de Auditores GR socializa los hallazgos encontrados al representante legal y al equipo que acompaño la auditoria, se crea una acta final  | |
| 19. El equipo de Auditores GR hace entrega de los hallazgos y del plan de mejora al CoordinadorGSPyAPN| |
| 20. El CoordinadorGSPyAPN consolida los informes y PM | |
| 21. El CoordinadorGSPyAPN Realiza seguimiento a plan de mejora | |
| 22. Si el prestador cumple con el plan de mejoramiento, se cierra el plan de mejoramiento  | |
| 23. Si el prestador no cumple, remite a la coordinación de contrataciones IPS para la respectiva interventoría de contratos  | |
| **7. Requerimiento Asociado** | R001, R002, R003, R004, R005 |
| **8. Interfaz de Usuario Asociada** | |
| **9. Formato de Usuario Asociado** | F001, F002, F003 |

### 1.4 MODELADO VISUAL DEL CASO DE USO AUDITORIA EN SALUD PUBLICA

![Con titulo](img/FlujoAuditoriaSP.jpg "Auditoria en Salud Publica")

## 2. ESPECIFICACIÓN DEL SISTEMA DE INFORMACIÓN AUDITORIA EN SALUD PUBLICA

| Término | Descripción                               |
| ------- | ----------------------------------------- |
| PM      | Plan Mejoramiento                         |
| GR      | Gestión Riesgo                            |
| PE, DT  | Protección Especifica, Detección Temprana |

## 3. ESPECIFICACIÓN DE REQUERIMIENTOS

| | | |
| - | - | - |
| **N°** | **Tipo** | **Descripción** |
| R001 | Proceso | Red prestadora |
| R002 | Proceso | Reporte actividades |
| R003 | Proceso | Plan de Mejoramiento |
| R004 | Proceso | Normatividad vigente |
| R005 | Proceso | Asignación de presupuesto |

## 4. ESPECIFICACIÓN DE LA INTERFACE DE USUARIO

| |
| - |
| **1. Número** |
|  |
| **2. Propósito de la Interfaz** |
|  |
| **3. Gráfica de la Interfaz**|
|  |

### 4.1 IDENTIFICACIÓN DE PERFILES Y DIÁLOGOS

| |
| - |
| **1. Nombre del Perfil** |
|  |
| **2. Opciones a las que tiene Acceso**|
|  |
| **3. Tipo de Acceso** |
|  |

### 4.2 ESPECIFICACIÓN DE FORMATOS DE USUARIO

| Número | Nombre del Formato                          |
| ------ | ------------------------------------------- |
| F001   | Formatos de auditoria seguridad alimentaria |
| F002   | Formatos de auditoria en salud              |
| F003   | Formatos de auditora ene salud mental       |