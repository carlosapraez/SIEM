#  GESTIÓN DE TUTELAS E INCIDENTES DE DASACATO .

Garantizar la respuesta oportuna a las acciones de Tutelas e incidentes de desacato

## 1. MODELADO DEL SISTEMA DE GESTIÓN DE TUTELAS E INCIDENTES DE DASACATO

### 1.1 ACTORES 

![Con titulo](img/ActorTutelas.jpg "Actores")

### 1.2 IDENTIFICACIÓN DE LOS CASOS DE USO

| N° | Procesos del Sistema de Información |
| ------ | ----------------------------------- |
| 1 |Recibir notificación de admisión de tutela o incidente de desacato.|
| 2 |Informar al jefe juridico|
| 3 |Repartir procesos de desacato a los profesionales de la oficina|
| 4 |Solicitar información de las diferentes coordinaciones|
| 5 |Solicitar interventoria al area de control interno al no tener respuesta |
| 6 |Iniciar con repuesta a acción de tutela|
| 7 |Radicar respuesta ante la autoridad judicial competente|
| 8 |Informar toda respuesta a siris |
| 9 |Notificar fallo y hacer revisión|
| 10|Comunicar el fallo a atención usuario |
| 11 |Revisar fallo si es favorable o no|
| 12 |Impuganar en contra de la sentencia radicar dentro del tiempo legal|
| 13 |Recibir notificación del juzgado|
| 14 |Admitir tramite de impugnación |
| 15 |Llegar fallo segunda estancia|
| 16 |Comunicar atención usuario si hubieron cambios|
| 17 |Recibir notificación de selección de  revisión por parte de la Corte Constitucional cuando se presente |
| 18 |Sustanciar informe para la Corte Constitucional|
| 19 |Recibir la decisión de la corte |
| 20 |El fallo tiene respuesta? |
| 21 |Seguir proceso |
| 22 |Notificar requerimiento de cumplimiento |
| 23 |Informar la decisión al proceso |
### 1.3 DESCRIPCIÓN DE LOS CASOS DE USO  GESTIÓN DE TUTELAS E INCIDENTES DE DASACATO

| | |
| - | - |
| **1. Caso de Uso** | GESTIÓN DE TUTELAS E INCIDENTES DE DASACATO|
| **2. Descripción** | Aplica para todas las tutelas e incidentes notificados a la Entidad. |
| **3. Actor(es)**   | Asistente Jurídico, Funcionarios Regionales, Jefe Jurídico, Auxiliar Jurídico, P. U. Jurídico.  |
| **4. Pre Condiciones** | Contar con la normatividad vigente, contar con la información requerida de los diferente procesos|
| **5. Pos Condiciones** |Obtener una decisión favorable para la entidad |
| **6. Flujo de Eventos** ||
| *Actor(es)* | *Sistema* |
|| 1. EL Auxiliar Jurídico recibe información en sistema, orfeo, correo electronico y correspondencia, |
| 2. EL Auxiliar Jurídico informa al jefe jurídico y el hace el reparto entre los profesionales de la oficina.||
|| 3. EL Asistente Jurídico solicita información a las coordinaciónes de aseguramiento, atención al usuario de diferentes regionales  |
|4. EL Asistente Jurídico al no tener respuesta a correo electronico, u orfeo solicita interventoria a el area de control interno.||
|5. EL Asistente Jurídico inicia con respuesta a acción de tutela||
|| 6. EL Asistente Jurídico radica la repuesta ante la autoridad competente mediante correo electronico o fisico|
| |7. EL Asistente Jurídico envía toda respesta de procesos a siris.| 
| 8. EL Asistente Jurídico notifica el fallo y hace revisión||
| |9. EL Asistente Jurídico comunica el fallo y atención al usuario realiza seguimiento.|
| 10. EL Asistente Jurídico revisa fallo si es favorable o no favorable si este es favorable llega a su fin .| 11. EL Asistente Jurídico proyecta impugnación en contra de la sentencia cuando no es favorable y se radica la impugnación dentro del tiempo legal .|
| 12. EL Asistente Jurídico revisa la notificación del juzgado que admite tramite de impugnaión, llega fallo segunda estancia . EL Asistente Jurídico comunica a atención al usuario si hubieron cambios o no sentencia judicial; puede haber la posiilidad que se revise la corte constitucional y si si se sustancia informe ante corte constitucional respuesta revisada por jefe jurídico y se envia a la corte la respuesta.||
|| 13. EL Asistente Jurídico recibe la decisión de la corte y se informa esta decición al proceso correspondiente.|
| 14. EL Asistente Jurídico revisa si el fallo tiene requerimiento? si no llega a su fin y si sigue proceso, notifica , requerimiento cumplimiento al asistente jurídico quien solicita informe a los procesos correspondientes.||
| **7. Requerimiento Asociado** | R001 R002 |
| **8. Interfaz de Usuario Asociada** |.  |

### 1.4 MODELADO VISUAL DE LOS CASOS DE USO  GESTIÓN DE TUTELAS E INCIDENTES DE DASACATO

![Con titulo](img/GestiónTutela.jpg "Caso de uso")

## 2. ESPECIFICACIÓN DEL SISTEMA DE INFORMACIÓN

| Término | Descripción |
| ------- | ----------- |
| ORFEO |Es un sistema de Gestión Documental y de procesos desarrollado inicialmente por la Superintendencia de Servicios Públicos  |
|  | |

## 3. ESPECIFICACIÓN DE REQUERIMIENTOS

| | | |
| - | - | - |
| **N°** | **Tipo** | **Descripción** |
| R001 | Proceso | Normatividad vigente |
| R002 | Proceso | Informes y soportes de los diferentes lideres de proceso |

## 4. ESPECIFICACIÓN DE LA INTERFACE DE USUARIO

| |
| - |
| **1. Número** |
|  |
| **2. Propósito de la Interfaz** |
||
| **3. Gráfica de la Interfaz**|
|  |
 
### 4.1 IDENTIFICACIÓN DE PERFILES Y DIÁLOGOS

| |
| - |
| **1. Nombre del Perfil** |
| **2. Opciones a las que tiene Acceso**|
| **3. Tipo de Acceso** |
### 4.2 ESPECIFICACIÓN DE FORMATOS DE USUARIO

| Número | Nombre del Formato    |
| ------ | --------------------- |
| F001   | Matriz de seguimiento |