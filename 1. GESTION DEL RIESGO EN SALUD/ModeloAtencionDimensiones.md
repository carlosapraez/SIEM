# SISTEMA DE INFORMACIÓN GESTIÓN INTEGRAL DEL MODELO DE ATENCIÓN SEGÚN LAS DIMENSIONES DE SALUD PUBLICA

Garantizar que los afiliados a EPS - I Mallamas reciban servicios de atención en los diferentes programas de salud pública, de acuerdo a las dimensiones establecidas en el modelo de atención en el marco del plan decenal de salud pública.

## 1. MODELADO DEL SISTEMA DE INFORMACIÓN

### 1.1 ACTORES GESTIÓN INTEGRAL DEL MODELO DE ATENCIÓN SEGÚN LAS DIMENSIONES DE SALUD PUBLICA

![Con titulo](img/ActoresModeloAtencionSP.jpg "Actores")

### 1.2 IDENTIFICACIÓN DE LOS CASOS DE USO GESTIÓN INTEGRAL DEL MODELO DE ATENCIÓN SEGÚN LAS DIMENSIONES DE SALUD PUBLICA



| Número | Procesos del Sistema de Información |
| ------ | ----------------------------------- |
| 1      | Elaborar POA                        |
| 2      | Estrategias                         |
| 3      | Actividades                         |
| 4      | Responsable                         |
| 5      | Linea de base                       |
| 6      | Meta                                |
| 7      | Acciones                            |
| 8      | Solicita información                |
| 9      | Recolectar información              |
| 10     | Consolidad información              |
| 11     | Seguimiento Trimestral              |
| 12     | Envío informe                       |
| 13     | Aceptación informe                  |
| 14     | Generar reunión                     |
| 15     | Levantar PM                         |
| 16     | Ajuste de informe                   |
| 17     | Seguimiento PM                      |
| 18     | Remisión                            |
| 19     | Remisión Informe final              |
| 20     | Interventoría                       |

### 1.3 DESCRIPCIÓN DEL DIAGRAMA DE CASOS DE USO GESTIÓN INTEGRAL DEL MODELO DE ATENCIÓN SEGÚN LAS DIMENSIONES DE SALUD PUBLICA

| **1. Caso de Uso** | Gestión Integral Del Modelo De Atención Según Las Dimensiones De Salud Publica |
| - | - |
| **2. Descripción** | Realizar auditoria a la red para medir la calidad en la prestación de los servicios de salud |
| **3. Actor(es)**   | **CoordinadorPyPyGR** Coordinador de Promoción y Prevención y Gestión del Riesgo, Contrataciones, **CoordinadorGSPyAPN** Coordinador de Gestión en Salud Publica y Auditoria de Primer Nivel, Gestión Riesgo Salud y Auxiliar de Salud Publica |
| **4. Pre Condiciones** | Contar con red contratada |
| **5. Pos Condiciones** | Mejorar las condiciones de salud de los afiliados|
| **6. Flujo de Eventos** |
| *Actor(es)* | *Sistema* |
| 1. El Grupo de gestión Riesgo Salud elabora el POA estableciendo estrategias, actividades, responsable, linea de base y meta|  |
| 2. El Grupo de gestión Riesgo Salud ejecuta las acciones planteadas en el POA de cada una de las dimensiones |  |
| 3. El Grupo de gestión Riesgo Salud solicita información a los prestadores de acuerdo a cada una de las dimensiones|  |
| 4. Los prestadores suministran la información mediante los formatos establecidos por cada una de las dimensiones |  |
| 5. Los prestadores ingresan la información en el modulo de sexualidad con sentido maternidad responsable  | 6. Muestra pantalla inicial donde se hace la búsqueda por numero de identificación del afiliado (ver interfaz I001) |
| 7. El prestador ingresa los datos que aplican a la dimensión  | 8. Muestra los formularios de preconcepción, maternidad o Anticoncepción PRE y POST (ver interfaz I002) |
| 9. El prestador selecciona el programa que le aplica e ingresa la información y da clic en botón guardar| 10. Registra los datos en BD |
| 11. Los prestadores acceden al modulo de ECNT|  12. Muestra pantalla inicial donde se hace la búsqueda por numero de cedula del afiliado (ver interfaz I003)|
| 13. Muestra una ventana con los datos generales del afiliado (Ver interfaz I004)  |  |
| 14. El prestador selecciona la opción Crónicos (Ver interfaz I005)  | 15. Muestra el formulario de captura (Ver interfaz I006)|
| 16. El prestador diligencia los datos que le aplican y da clic en registrar información  | 17. Registra los datos en la BD (Ver interfaz I006)|
| 18. El Grupo de gestión Riesgo Salud consolida la información enviada por los prestadores ya sea por el aplicativo o con las plantillas establecidas para cada dimensión | |
| 19. El Grupo de gestión Riesgo Salud Hace el seguimiento trimestral a cada unos de los prestadores que apliquen | |
| 20. El Grupo de gestión Riesgo Salud y el auxiliar de salud publica hacen el envío del informe trimestral a los prestadores | |
| 21. El Prestador si no esta de acuerdo con el informe, se programa una reunión entre las partes y se ajusta el informe trimestral  | |
| 22. El Prestador elabora un plan de mejoramiento | |
| 23. El Grupo de gestión Riesgo Salud realiza el seguimiento al plan de mejoramiento y lo remite al coordinador de gestión en salud publica y auditoria de primer nivel para su respectivo seguimiento | |
| 24. El coordinador de Promoción y prevención y gestión del riesgo remite el informe final a la coordinación de contrataciones  | |
| 25. El Coordinador de Gestión en Salud Publica y Auditoria de Primer Nivel de no cumplir con la meta propuesta se remite a la coordinación de contrataciones a interventoría de contrato | |
| **7. Requerimiento Asociado** | R001, R002, R003, R004 |
| **8. Interfaz de Usuario Asociada** | I001, I002, I003, I004, I005, I006 |
| **9. Formato de Usuario Asociado** | F001, F002, F003, F004, F005, F006, F007, F008, F009, F010, F011, F012, F013, F014 |

### 1.4 MODELADO VISUAL DEL CASO DE USO GESTIÓN INTEGRAL DEL MODELO DE ATENCIÓN SEGÚN LAS DIMENSIONES DE SALUD PUBLICA

![Con titulo](img/FlujoModeloAtencionSP.jpg "Modelo de Atención")

## 2. ESPECIFICACIÓN DEL SISTEMA DE INFORMACIÓN GESTIÓN INTEGRAL DEL MODELO DE ATENCIÓN SEGÚN LAS DIMENSIONES DE SALUD PUBLICA

| Término | Descripción                                    |
| ------- | ---------------------------------------------- |
| BD      | Base de Datos                                  |
| POA     | Plan Operativo Anual                           |
| RIPS    | Registro Individual de Prestación de Servicios |
| ECNT    | Enfermedades Crónicas no Transmisibles         |
| PAI     | Programa Ampliado de Inmunizaciones            |
| ITS     | Infecciones de transmisión sexual         |
| VIH     | Virus de Inmunodeficiencia Humana         |
| IVE     | Interrupción Voluntaria del Embarazo         |

## 3. ESPECIFICACIÓN DE REQUERIMIENTOS

| **N°** | **Tipo** | **Descripción** |
| - | - | - |
| R001 | Proceso | Red prestadora |
| R002 | Proceso | RIPS |
| R003 | Proceso | Plan de Mejora |
| R004 | Proceso | Reportes prestadores aplicativos |

## 4. ESPECIFICACIÓN DE LA INTERFACE DE USUARIO

| **1. Número** |
| - |
| I001 |
| **2. Propósito de la Interfaz** |
| Busca afiliado para registrar y/o actualizar |
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/ModeloAtencion1.jpg "Registrar Gestante") |

| **1. Número** |
| - |
| I002 |
| **2. Propósito de la Interfaz** |
| Seleccionar formulario |
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/ModeloAtencion2.jpg "Registrar Programa") |

| **1. Número** |
| - |
| I003 |
| **2. Propósito de la Interfaz** |
| Registrar información general relacionada con las variables clínicas y paraclínicas de las enfermedades precursoras |
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/ModeloAtencion3.jpg "Registrar ERCN") |

| **1. Número** |
| - |
| I004 |
| **2. Propósito de la Interfaz** |
| Busca afiliado para registrar y/o actualizar |
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/ModeloAtencion4.jpg "Registrar Gestante") |

| **1. Número** |
| - |
| I005 |
| **2. Propósito de la Interfaz** |
| Registrar información general relacionada con las variables clínicas y paraclínicas de las enfermedades precursoras |
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/ModeloAtencion5.jpg "Registrar ERCN") |

| **1. Número** |
| - |
| I006 |
| **2. Propósito de la Interfaz** |
| Registrar ERC |
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/ModeloAtencion6.jpg "Registrar ERCN") |

### 4.1 IDENTIFICACIÓN DE PERFILES Y DIÁLOGOS

| **1. Nombre del Perfil** |
| - |
| Auxiliar |
| **2. Opciones a las que tiene Acceso**|
| Registrar ERC |
| **3. Tipo de Acceso** |
| Registrar, modificar, reporte, consultar |

### 4.2 ESPECIFICACIÓN DE FORMATOS DE USUARIO

| Número | Nombre del Formato                                 |
| ------ | -------------------------------------------------- |
| F001   | Estrategia conoce tu riesgo, peso saludable (ECNT) |
| F002   | Sobrepeso  (ECNT)                                  |
| F003   | Corte Nacido Vivo                                  |
| F004   | Inasistentes PAI                                   |
| F005   | Coberturas PAI                                     |
| F006   | Bajo Peso                                          |
| F007   | Malnutrición en la Gestante                        |
| F008   | Seguimiento sobrepeso y obesidad                   |
| F009   | Seguimiento de Citologías anormales                |
| F010   | Seguimiento de gestantes con ITS y VIH             |
| F011   | Interrupción Voluntaria del Embarazo IVE           |
| F012   | Matriz seguimiento salud mental                    |
| F013   | BD conflicto armado                                |
| F014   | BD discapacidad                                    |