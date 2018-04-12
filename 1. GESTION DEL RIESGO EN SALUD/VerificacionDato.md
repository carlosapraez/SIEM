# SISTEMA DE INFORMACIÓN GESTIÓN DE RIESGO EN SALUD

Garantizar que los afiliados a EPS - I Mallamas reciban servicios de protección especifica y detección temprana, de acuerdo a la identificación del riesgo contemplados en la Normatividad vigente

## 1. MODELADO DEL SISTEMA DE INFORMACIÓN

### 1.1 ACTORES VERIFICACIÓN DE LA FUENTE DE INFORMACIÓN

![Con titulo](img/ActoresVerificacion.jpg "Actores")

### 1.2 IDENTIFICACIÓN DE LOS CASOS DE USO VERIFICACIÓN DE LA FUENTE DE INFORMACIÓN


| Número | Procesos del Sistema de Información |
| ------ | ----------------------------------- |
| 1      | Elaborar cronograma de salidas      |
| 2      | Seleccionar muestra                 |
| 3      | Crear programación                  |
| 4      | Editar programación                 |
| 5      | Registrar programación por área     |
| 6      | Notificar visita                    |
| 7      | Aceptar o rechazar visita           |
| 8      | Reprogramar visita                  |
| 9      | Crear acta de inicio                |
| 10     | Evaluar                             |
| 11     | Seleccionar programación            |
| 12     | Evaluar por área                    |
| 13     | Evaluar afiliado                    |
| 14     | Evaluar registro                    |
| 15     | Crear acta final                    |
| 16     | Crear Plan de mejoramiento          |

### 1.3 DESCRIPCIÓN DEL DIAGRAMA DE CASOS DE USO VERIFICACIÓN DE LA FUENTE DE INFORMACIÓN
| | |
| - | - |
| **1. Caso de Uso** | Verificación de la fuente de información |
| **2. Descripción** | Realizar auditoria a los prestadores para medir la veracidad en los datos reportados|
| **3. Actor(es)**   | Coordinador de Auditoria de baja complejidad, Auxiliar de SSP, P.U de sistemas, Prestadores |
| **4. Pre Condiciones** | Contar con los planos reportados oportunamente|
| **5. Pos Condiciones** | Informe de auditoria a prestador|
| **6. Flujo de Eventos** |
| *Actor(es)* | *Sistema* |
| 1. Coordinador de Auditoria de Baja complejidad realiza y entrega cronograma de salidas| 2. Generar Cronograma de Visitas Formato Excel |
| 3. El Profesional Universitario de sistemas recibe el cronograma|4. Presenta formulario con el periodo de consulta y prestador de servios para buscar los registros reportados |
| 5. El Profesional Universitario de sistemas ingresa los datos de fecha y nombre del prestador y presiona buscar|6. Lista todos los archivos reportados del prestador con las opciones de crear o editar|
| 7. El Profesional Universitario de sistemas selecciona el botón crear | 8. Despliega los datos del prestador |
| 9. El Profesional Universitario de sistemas presiona el botón guardar |10. Registra la programación y carga las áreas para su verificación|
| 11. El Profesional Universitario de sistemas selecciona los registros de cada área de acuerdo a su criterio y da clic en programar |12. Guarda los registros seleccionados y presenta la pantalla para seleccionar otra área con la cantidad de registros programados|
| 13. El Profesional Universitario de sistemas programa los registros en las áreas que aplique cada prestador | |
| 14. El Profesional Universitario de sistemas da clic en imprimir los registros programados para ser enviados al prestador| |
| 15. El prestador Responde en caso de aplazar visita| |
| 16. El Profesional Universitario de sistemas se desplaza al prestador e ingresa al modulo de crear acta de inicio |17. Presenta el formulario de búsqueda |
| 18. El Profesional Universitario de sistemas ingresa los datos de fecha y nombre del prestador y presiona buscar |19. Lista todos los archivos programados con las opciones de seleccionar (para crear nueva acta de inicio de uno varios registros) o Editar, imprimir, ver soportes (cuando ya esta creado)|
|20. Muestra el formulario de acta de inicio para ser diligenciado o modificado| |
|21. El Profesional Universitario de sistemas presiona en guardar | 22. guarda acta de inicio|
|23. El Profesional Universitario de sistemas ingresa los datos de fecha y nombre del prestador y presiona buscar|24. Lista todos los archivos programados del prestador con las opciones de evaluar calidad|
|25. El Profesional Universitario de sistemas selecciona el área a evaluar  |26. Indica los registro seleccionados para el área seleccionada con las opciones de evaluar datos del afiliado y registros| 
|27. El Profesional Universitario de sistemas verifica datos del afiliado coincidan con la Historia Clínica del prestador, registrando el resultado de la evaluación |28. Guarda el resultado de la evaluación para cada registro | 
|29. El Profesional Universitario de sistemas selecciona evaluación y verifica la exactitud del dato reportado, registrando el resultado de la evaluación  |30. Guarda el resultado de la evaluación para cada registro | 
|31. El Profesional Universitario de sistemas ingresa al modulo de crear acta final |32. Presenta el formulario de búsqueda |
|33. El Profesional Universitario de sistemas ingresa los datos de fecha y nombre del prestador y presiona buscar |34. Lista todos los archivos evaluados con las opciones de seleccionar (para crear nueva acta final de uno varios registros) o Editar, imprimir, ver soportes (cuando ya esta creado) |35. Muestra el formulario de acta final para ser diligenciado o modificado|
|36. El Profesional Universitario de sistemas presiona en guardar | 37. Guarda acta final|
| **7. Requerimiento Asociado** | R001, R002|
| **8. Interfaz de Usuario Asociada** | I001, I002, I003, I004, I005, I006, I007, I008, I009|
| **9. Formato de Usuario Asociado** |  |

### 1.4 MODELADO VISUAL DEL CASO DE USO VERIFICACIÓN DE LA FUENTE DE INFORMACIÓN

![Con titulo](img/FlujoVerificacionDato.jpg "Verificación del Dato")

## 2. ESPECIFICACIÓN DEL SISTEMA DE INFORMACIÓN VERIFICACIÓN DE LA FUENTE DE INFORMACIÓN

| Término | Descripción                   |
| ------- | ----------------------------- |
| SSP     | Subdirección de Salud Publica |
| P.U     | Profesional Universitario     |


## 3. ESPECIFICACIÓN DE REQUERIMIENTOS

| | | |
| - | - | - |
| **N°** | **Tipo** | **Descripción** |
| R001 | Proceso | Red prestadora |
| R002 | Proceso | Archivos Planos |


## 4. ESPECIFICACIÓN DE LA INTERFACE DE USUARIO

| |
| - |
| **1. Número** |
| I001 |
| **2. Propósito de la Interfaz** |
| Acceder al modulo de verificación de la fuente de información|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Verificacion1.jpg "Iniciar sesión") |

| |
| - |
| **1. Número** |
| I002 |
| **2. Propósito de la Interfaz** |
| Establecer periodo, prestador y archivos reportados|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Verificacion2.jpg "Seleccionar y buscar") |

| |
| - |
| **1. Número** |
| I003 |
| **2. Propósito de la Interfaz** |
| Seleccionar archivo para verificar|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Verificacion3.jpg "Ventana inicial") |

| |
| - |
| **1. Número** |
| I004 |
| **2. Propósito de la Interfaz** |
| Seleccionar áreas a verificar|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Verificacion4.jpg "Verificar áreas") |

| |
| - |
| **1. Número** |
| I005 |
| **2. Propósito de la Interfaz** |
| Elaborar acta de inicio|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Verificacion5.jpg "Acta de Inicio") |

| |
| - |
| **1. Número** |
| I006 |
| **2. Propósito de la Interfaz** |
| Diligenciar campos de formulario de acta de inicio|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Verificacion6.jpg "Diligenciar") |

| |
| - |
| **1. Número** |
| I007 |
| **2. Propósito de la Interfaz** |
| Evaluá la calidad del dato|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Verificacion7.jpg "Evaluar calidad") |

| |
| - |
| **1. Número** |
| I008 |
| **2. Propósito de la Interfaz** |
| Seleccionar área de verificación|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Verificacion8.jpg "Evaluar calidad") |

| |
| - |
| **1. Número** |
| I009 |
| **2. Propósito de la Interfaz** |
| Generar acta final|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Verificacion9.jpg "Acta final") |

### 4.1 IDENTIFICACIÓN DE PERFILES Y DIÁLOGOS

| |
| - |
| **1. Nombre del Perfil** |
| Auditor verificación del dato |
| **2. Opciones a las que tiene Acceso**|
|Programar, acta de inicio, evaluar, acta final |
| **3. Tipo de Acceso** |
| Crear, editar, consultar, imprimir |

