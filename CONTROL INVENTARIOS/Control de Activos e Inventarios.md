# SISTEMA DE CONTROL DE ACTIVOS E INVENTARIOS			


Estandarizar el conjunto de actividades para llevar el control y mantener un sistema de información actualizado oportuno y confiable del inventario interno de la EPS - I MALLAMAS.

## 1. MODELADO DEL SISTEMA DE INFORMACIÓN

### 1.1 ACTORES 

![Con titulo](img/ActorAlmacen.jpg "Actores")

### 1.2 IDENTIFICACIÓN DE LOS CASOS DE USO

| N° | Procesos del Sistema de Información |
| ------ | ----------------------------------- |
| 1 |Generar Reporte  Inventario  |
| 2 |Comparar Inventario Generado con cada Dependencia |
| 3 |Revisar informe Generado coincide con lo Fisico |
| 4 |Realizar Informe de Novedad Presentada |
| 5 |Remitir Información a Dirección Administratva y Financiera  |
| 6 |Diligenciar Formato para Dar de Baja a Activos|
| 7 |Actualizar Inventario en Sistema|
| 8 |Verificar el Estado de los Elementos|
| 9 |Verificar Los elementos se Encuentren en Buen Estado|
| 10 |Gestionar las Acciones Pertinentes para Mejorar el Estado |
| 11 |Mejorar el Estado y Remitir Informe a Dirección Administrativa y Financiera|
|12 |Diligenciar y Firmar Acta de Revisión de Inventarios|
### 1.3 DESCRIPCIÓN DE LOS CASOS DE USO CONTROL DE ACTIVOS E INVENTARIOS

| | |
| - | - |
| **1. Caso de Uso** | CONTROL DE ACTIVOS E INVENTARIOS |
| **2. Descripción** | Estandarizar el conjunto de actividades para llevar el control y mantener un sistema de informacion actualizado oportuno y confiable del inventario interno de la EPS - I MALLAMAS|
| **3. Actor(es)**   | CoordinadorAlmacen, Funcionarios y Dirección Administrativa y Financiera |
| **4. Pre Condiciones** |  Aplica a  todos los equipos y/o activos fijos de la EPS - I MALLAMAS|
| **5. Pos Condiciones** | Acta Generada  |
| **6. Flujo de Eventos** ||
| *Actor(es)* | *Sistema* |
||1.El Coordinador de Almacén Genera del Sistema Reporte de Inventario por Dependencia y por Funcionario |
| 2.El Coordinador de Almacén Confronta Inventario Generado con lo encontrado en cada Dependencia ||
|3.El Coordinador de Almacén Compara el Inventario Generado con lo Fisico ||
|4.El Coordinador de Almacén Realiza Informe de la Novedad Presentada .| |
|5. El Coordinador de Almacén Remite Informe a Dirección Administrativa y Financiera Solicitando Visto Bueno para dar de Baja al Activo||
|6.El Coordinador de Almacén Diligencia Formato para dar de Baja a Activos ||
| |7. El Coordinador de Almacén Actualiza Inventario en Sistema|
| 8.El Coordinador de Almacén Verifica el Estado de los Elementos ||
| 9.El Coordinador de Almacén Verifica el Buen estado de los Elementos ||
|10.El Coordinador de Almacén Gestiona las Acciones Pertinentes para Mejorar el Estado .||
|11.El Coordinador de Almacén verifica y Remite Informe a Dirección Administrativa y Financiera.||
|12.El Coordinador de Almacén Diligencia y Firma acta de revisión de inventarios.||
| **7. Requerimiento Asociado** | R001 |
| **8. Interfaz de Usuario Asociada** |I001 |

### 1.4 MODELADO VISUAL DE LOS CASOS DE USO CONTROL DE ACTIVOS E INVENTARIOS

![Con titulo](img/ControlActivosInventarios.jpg "Caso de uso")

## 2. ESPECIFICACIÓN DEL SISTEMA DE INFORMACIÓN

| Término | Descripción |
| ------- | ----------- |
| INVENTARIO | Lista ordenada de bienes y demás cosas valorables que pertenecen a una persona, Empresa o Institución.  |
| ||



## 3. ESPECIFICACIÓN DE REQUERIMIENTOS

| | | |
| - | - | - |
| **N°** | **Tipo** | **Descripción** |
| R001 | Físico | Formato de Inventario |
## 4. ESPECIFICACIÓN DE LA INTERFACE DE USUARIO

| |
| - |
| **1. Número** |
| I001 |
| **2. Propósito de la Interfaz** |
| Formato de Inventario|
| **3. Gráfica de la Interfaz**|
| ![Con titulo](img/inventario/img14.jpg "Interfaz de Usuario")
| ![Con titulo](img/inventario/img15.jpg "Interfaz de Usuario")
| ![Con titulo](img/inventario/img17.jpg "Interfaz de Usuario")
| ![Con titulo](img/inventario/img18.jpg "Interfaz de Usuario")
| ![Con titulo](img/inventario/img20.jpg "Interfaz de Usuario")
### 4.1 IDENTIFICACIÓN DE PERFILES Y DIÁLOGOS

| |
| - |
| **1. Nombre del Perfil** |
| Coordinador de Almacen|
| **2. Opciones a las que tiene Acceso**|
| Activos Dependencia, Editar|
| **3. Tipo de Acceso** |
| Acta, Eliminar, Verificar |