# EJEMPLOS DE COMO ACCEDER A BASES DE DATOS MySQL DESDE JAVA

## COPIA DEL REPOSITORIO REMOTO EN SU COMPUTADORA LOCAL


Si así lo desea, puede crear una copia local de este repositorio, pero para que pueda estar subiendo a su propio repositorio los cambios que le vaya haciendo, debe hacer lo siguiente:
1. Haga un fork (copia de este repositorio en su propia cuenta de Github) dando click en la opción Fork que aparece arriba a la derecha del nombre del repositorio

2. Entre al repositorio creado

3. En tal página dé click en el botón Code y copie el URL que aparece en el cuadro de texto de nombre **Clone with HTTPS** (comienza con *https://*)

4. En una consola de Git Bash en Windows (o en una terminal en Linux o Mac), cree una carpeta donde quiera que se contengan sus prácticas del semestre (si es que aún no la has creado) y colócate en tal carpeta. La carpeta la puedes crear desde el Git Bash o terminal Linux/Mac usando el comando `mkdir` (o con el explorador de archivos de su sistema operativo) y en la consola de Git Bash o terminal de Linux/Mac te puedes cambiar a la carpeta mencionada usando el comando `cd`

5. Clone el repositorio privado dando el comando `git clone URL ejemplosjdbc`
 (donde **URL** es el URL que copió en el paso 3)\
 Este comando creará dentro de la carpeta creada en el paso 4) una subcarpeta de nombre **ejemplosjdbc** donde estará una copia local de su repositorio remoto.\

## EjemploJDBC.java

Este archivo contiene un ejemplo de como acceder a la base de datos usando **DriverManager**


## EjemploJDBCDataSource.java

Este archivo contiene un ejemplo de como acceder a la base de datos usando una implementación específica de la interface **DataSource**

## NOTAS IMPORTANTES

En ambos ejemplos se asume que la base de datos a usar se denomina **nuevapoo2** y que se conectará con el usuario **usuario2021** y clave **clavecita** (que son la base de datos y usuario creados en las sesiones previas). Modifique estos datos si no coincide con su configuración.

También es necesario que haya configurado correctamente la variable de entorno **CLASSPATH** tal como se solicitó en la Práctica 4.
