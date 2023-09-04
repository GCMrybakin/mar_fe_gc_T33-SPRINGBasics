# mar_fe_gc_T33-SPRINGBasics
T33 – SPRING Basics

# 1 Instalación de STS4 (adjuntar capturas de pantalla de la instalación).
Necesitaremos almenos la version de java 8 a superior para usar STS4, en mi caso usare el ide de eclipse.

![image](https://github.com/GCMrybakin/mar_fe_gc_T33-SPRINGBasics/assets/135844963/259019fc-e498-4b73-9620-2871f63c266f)

Cuando descargamos la version que usemos le damos doble click para instalarlo.

![image](https://github.com/GCMrybakin/mar_fe_gc_T33-SPRINGBasics/assets/135844963/3fcae122-4ccf-4ef4-b2de-5c9d18492e88)

Nos vamos a la carpeta que se nos a creado y abrimos el .exe

![image](https://github.com/GCMrybakin/mar_fe_gc_T33-SPRINGBasics/assets/135844963/16801e33-2b09-4e3f-a1e6-019430d575c7)
![image](https://github.com/GCMrybakin/mar_fe_gc_T33-SPRINGBasics/assets/135844963/d09c0bac-bd1a-4559-b698-91db461b6e3a)

Luego seleccionamos un directorio de trabajo y le damos a siguiente.

![image](https://github.com/GCMrybakin/mar_fe_gc_T33-SPRINGBasics/assets/135844963/822367fa-12e0-4c1a-b265-4d2b08bcfe10)

y ya tenemos STS4 instalado!


# 2 Crear un proyecto básico Spring Utilizando Maven. 
Abre tu IDE, en mi caso eclipse y selecciona la opción para crear un nuevo proyecto.
Elige la plantilla o arquetipo de proyecto de o Maven.

![image](https://github.com/GCMrybakin/mar_fe_gc_T33-SPRINGBasics/assets/135844963/11248b70-4ee7-4d5f-b705-4b7cb37327af)

Completa los detalles del proyecto, como el groupId y el artifactId.
Haz clic en "Finalizar" o "Crear proyecto" para generar el proyecto.

![image](https://github.com/GCMrybakin/mar_fe_gc_T33-SPRINGBasics/assets/135844963/1ce3d5e9-7e9b-4584-88fa-7f5912f5e77c)

Una vez creado el projecto en maven ponemos esto en el archivo pom.xml:
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-web</artifactId>
</dependency>

![image](https://github.com/GCMrybakin/mar_fe_gc_T33-SPRINGBasics/assets/135844963/cb3d5eb0-5ac0-427f-89b2-7537e2d10ad5)


Y ahora se puede usar spring, se puede utilizar el comando spring-boot:run para iniciar el projecto
