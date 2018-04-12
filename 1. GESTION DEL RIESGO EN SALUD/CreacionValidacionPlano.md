# SISTEMA DE INFORMACIÓN GESTIÓN DE RIESGO EN SALUD

Garantizar que los afiliados a EPS - I Mallamas reciban servicios de protección especifica y detección temprana, de acuerdo a la identificación del riesgo contemplados en la Normatividad vigente

## 1. MODELADO DEL SISTEMA DE INFORMACIÓN

### 1.1 ACTORES VALIDACIÓN DE PLANOS Y CREACIÓN DE USUARIOS

![Con titulo](img/ActoresContraseña.jpg "Actores")

### 1.2 IDENTIFICACIÓN DE LOS CASOS DE USO VALIDACIÓN DE PLANOS Y CREACIÓN DE USUARIOS

| Número | Procesos del Sistema de Información |
| ------ | ----------------------------------- |
| 1      | Solicitar red                       |
| 2      | Entrega red                         |
| 3      | Verificar prestadores NC            |
| 4      | Verificar en REPS                   |
| 5      | Solicitar acceso al validador 4505  |
| 6      | Ingresar nuevo prestador            |
| 7      | Validar nuevo prestador             |
| 8      | Guardar nuevo prestador             |
| 9      | Enviar usuario a prestador          |
| 10     | Validar archivos planos             |
| 11     | Verificar calidad del dato          |
| 12     | Realizar informe de auditoria       |
| 13     | Realizar seguimiento                |
| 14     | Notificar prestador                 |

### 1.3 DESCRIPCIÓN DEL DIAGRAMA DE CASOS DE USO VALIDACIÓN DE PLANOS Y CREACIÓN DE USUARIOS
| | |
| - | - |
| **1. Caso de Uso** | Validación de planos y creación de usuarios |
| **2. Descripción** | Establecer las credenciales de acceso a los prestadores |
| **3. Actor(es)**   | Prestador, Auxiliar de Salud Publica, contrataciones, **CoordinadorPyPyGR** Coordinador de Promoción y Prevención y Gestión del Riesgo, **P.U.Sistemas** Profesional Universitario de Sistemas, Estadística|
| **4. Pre Condiciones** | Contar con red contratada, validador instalado en los prestadores de servicios de salud, armar archivos de acuerdo a la estructura del anexo técnico de la normatividad |
| **5. Pos Condiciones** | Reportar de manera nominal las atenciones de PE, DT y AEISP en un archivo consolidado al MSPS |
| **6. Flujo de Eventos** |
| *Actor(es)* | *Sistema* |
| 1. Auxiliar de SSP solicita red prestadora a contrataciones|  |
| 2. Contrataciones, entrega la red de prestadores |  |
| 3. Auxiliar de SSP verifica cuales son los prestadores nuevos contratados e ingresa al validador|4. Presenta el formulario de ingreso de prestadores  |
|5. El auxiliar ingresa los prestadores nuevos al sistema y da clic en guardar| 6. Envía los datos a la BD del sistema, validando que el prestador no se encuentre registrado |
| 7. El Auxiliar de SSP genera oficio y envía datos de acceso al validador a los prestadores |  |
| 8. Los prestadores generan los archivos planos teniendo en cuenta el anexo técnico de la normatividad vigente e ingresa al sistema con el usuario y contraseña asignado a la opción validar plano  |9. Presenta la pantalla para validar el plano  |
|10. El prestador carga los planos y da clic en validar archivo|11. Realiza las validaciones establecidas en la normatividad del anexo técnico y genera el reporte de inconsistencias |
|12. El prestador realiza las correcciones generadas por el sistema y carga nuevamente al validador| |
|13. Auxiliar de SSP brinda asistencia técnica cuando se presenta alguna dificultad a los prestadores de servicios de salud||
|14. El prestador realiza las correcciones generadas por el sistema y carga nuevamente al validador|15. El validador genera un mensaje que el archivo no tiene errores|
| 16. El prestador de servicios procede hacer firmar digitalmente el archivo validado|17. Recepciona el archivo firmado digitalmente|
| |18. Genera certificado de envío al prestador.|
|19. El P.U. de Sistemas verifica la calidad de la información reportada|20. definición periodo de consulta y descarga la información del validador|
| |21. Presentar resultado de verificación|
| |22. Seguimiento a reporte|
|23. El P.U de Sistemas Notifica a Prestador ||
| **7. Requerimiento Asociado** | R001, R002, R003 |
| **8. Interfaz de Usuario Asociada** |I001, I002, I003, I004  |
| **9. Formato de Usuario Asociado** | F001, F002 |

### 1.4 MODELADO VISUAL DE LOS CASOS DE USO

![Con titulo](img/flujoContraseña.jpg "Caso de uso")

## 2. ESPECIFICACIÓN DEL SISTEMA DE INFORMACIÓN

| Término | Descripción                                          |
| ------- | ---------------------------------------------------- |
| PE, DT  | Protección Especifica y Detección Temprana           |
| MSPS    | Ministerio de Salud y Protección Social              |
| SSP     | Subdirección de Salud Publica                        |
| AEISP   | Atención de Enfermedades de Interés de Salud Publica |
| GR      | Gestión del Riesgo                                   |
| NC      | Nuevos Contratados                                   |
| FCD     | Fortalecimiento Calidad del Dato                     |
| P.U     | Profesional Universitario                            |

## 3. ESPECIFICACIÓN DE REQUERIMIENTOS

| | | |
| - | - | - |
| **N°** | **Tipo** | **Descripción** |
| R001 | Proceso | Red prestadora |
| R002 | Proceso | Resolución 4505 de 2012 |
| R003 | Proceso | Validador |

## 4. ESPECIFICACIÓN DE LA INTERFACE DE USUARIO

| |
| - |
| **1. Número** |
| I001 |
| **2. Propósito de la Interfaz** |
| Acceder al validador|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Contraseña1.jpg "Inicio sesión") |

| |
| - |
| **1. Número** |
| I002 |
| **2. Propósito de la Interfaz** |
| Acceder a las opciones validaciones|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Contraseña2.jpg "Opciones de validación") |

| |
| - |
| **1. Número** |
| I003 |
| **2. Propósito de la Interfaz** |
| Validar archivos planos|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Contraseña3.jpg "Validaciones anexo") |

| |
| - |
| **1. Número** |
| I004 |
| **2. Propósito de la Interfaz** |
| Firmar digitalmente una vez se haya concluido la validación|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/Contraseña4.jpg "Verifica firma digital") |

### 4.1 IDENTIFICACIÓN DE PERFILES Y DIÁLOGOS

| |
| - |
| **1. Nombre del Perfil** |
| Auxiliar de Salud Publica y P.U de Sistemas|
| **2. Opciones a las que tiene Acceso**|
| Cargar plano, validar contenido, exportar errores, guardar plano, generar certificados de envío, archivos recibidos, parámetros del validador, administrar usuarios.|
| **3. Tipo de Acceso** |
| Ingresar, consultar, actualizar|

| |
| - |
| **1. Nombre del Perfil** |
|Prestador de servicios|
| **2. Opciones a las que tiene Acceso**|
| Cargar plano, validar contenido, exportar errores, guardar plano, generar certificados de envío, archivos recibidos|
| **3. Tipo de Acceso** |
| Ingresar, consultar|

### 4.2 ESPECIFICACIÓN DE FORMATOS OFIMATICOS

| Número | Nombre del Formato                 |
| ------ | ---------------------------------- |
| F001   | Análisis de reporte de información |
| F002   | Formato de control de reporte      |
|        |                                    |