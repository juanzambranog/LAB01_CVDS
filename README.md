# LABORATORIO 1

## PARTE I (Trabajo Individual).

1.	Crea un repositorio localmente.

      Creamos un repositorio de manera local usando los siguientes comandos en GIT:
  	      
  	      $ mkdir Local_repo
          $ cd Local_repo
          $ git init
   
      ![image](https://github.com/user-attachments/assets/580e1d39-406e-412f-9fb3-0a21ddec729e)

3. Agrega un archivo de ejemplo al repositorio, el README.md puede ser una gran opción.

      Añadimos un archivo README al repositorio local usando:

         $ echo > README.md
         $ git add README.md
         $ git add README.md

    ![image](https://github.com/user-attachments/assets/b5cc14f6-d19d-478c-b5e3-f5634c7d9e9c)



    ![image](https://github.com/user-attachments/assets/7780ac3a-a2a5-440b-b1a9-d4759dc5cbde)



    ![image](https://github.com/user-attachments/assets/70d4910f-55ec-4fb6-bc24-39a81e648612)


5.	Averigua para qué sirve y como se usan estos comandos **git add** y **git commit -m “mensaje”**

    ### git add :

    El comando git add agrega un cambio del directorio de trabajo al área de preparación. Le indica a Git que desea incluir actualizaciones a un archivo en particular en la próxima confirmación. Sin embargo, git add no afecta realmente al repositorio de ninguna manera significativa, los cambios no se registran realmente hasta que ejecuta git commit.

      Podemos usar el comando:
   
         git add [filename]
      
      para añadir un archivo en especifico o podemos usar 

         git add . 
      para añadir todos los cambios del directorio actual.

    ### git commit -m “mensaje”:

    El comando git commit -m "mensaje" se usa para guardar los cambios preparados en el historial del repositorio. El mensaje entre comillas describe brevemente los cambios realizados. Registra los cambios del área de preparación (staging area) en el repositorio y crea un punto en el historial de Git al que puedes volver más tarde.

         git commit -m “mensaje”

7. Abre una cuenta de github, si ya la tienes, enlazala con el correo institucional.
   

   En mi caso mi cuenta de GitHub ya estaba creada con mi correo institucional.

    ![image](https://github.com/user-attachments/assets/ba92c54f-6c15-4341-b1f1-f1af2bad20e9)


        
9. Crea un repositorio en blanco (vacío) en GitHub.        

    ![image](https://github.com/user-attachments/assets/2e1136f7-f813-4be8-ae96-fd7bb1c4487b)


10.	Configura el repositorio local con el repositorio remoto.

       Conectamos el repositorio lecal con el remoto usando:
   	
   	        git init

            git add .
            
            git commit -m "first commit"
            
            git remote add origin https://github.com/juanzambranog/LAB01_CVDS.git
            
            git push -u origin master

      ![image](https://github.com/user-attachments/assets/b6dcd9c4-9243-4200-b054-7e2b48703192)

   
      ![image](https://github.com/user-attachments/assets/5118a8bd-1c6f-4c34-850b-e93382f367b8)

   
      ![image](https://github.com/user-attachments/assets/19dba0fc-7ab7-495d-a10f-8db7c5f82790)
   

      ![image](https://github.com/user-attachments/assets/3130ce79-430a-4482-aca4-7887ddd3df6e)


7. Sube los cambios, teniendo en cuenta lo que averiguaste en el punto 3
    Utiliza los siguientes comando en el directorio donde tienes tu proyecto, en este orden:

   Subimos los cambios realizados en el repositorio local al remoto usando:

            git add .

            git commit -m "Actualizar README"

   ![image](https://github.com/user-attachments/assets/53f3c8c7-6c55-4cd6-9384-4948b2f96e86)


9.	Configura el correo en git local de manera correcta

      Enlazamos la cuenta del repositorio remoto con el git local para poder subir los cambios. 

      ![image](https://github.com/user-attachments/assets/eac79da8-024c-4df3-9b57-5b9dec14c4ee)


   





