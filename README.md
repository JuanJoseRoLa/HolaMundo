# HolaMundo

Lo que hemos realizado en este ejercicio es integrar Git en nuestro Android Studios, subir nuestro proyecto a un repositorio de GitHub y enlazarlo con una consola remota.
Para ello seguiremos los siguientes pasos:

1. Instalar el cliente Git 
- Para hacerlo en Linux se podra el siguiente comando: sudo apt-get install git
- Para hacerlo en Windows se tendra que descargar desde la pagina oficial: https://git-scm.com/downloads
2. Se comprueba la integracion de Git en Android Studios. Para mirarlo vaya File > Setting > Version Control > Git y se mira si en Path to Git executable se muestra 
el ejecutable del cliente Git.
3. Configurar Github en Android. Para eso vaya a File > Setting > Version Control > GitHub y introduzca los datos de su usuario.
4. Subir proyecto a un repositorio de GitHub. Para eso vaya a VCS > Import into Version Control > Share project on GitHub.
5. Enlacemos en repositorio con una consola remota. Para eso vaya a GitHub y copie en enlace del repositorio, despues nos vamos a la carpeta del proyecto y arbimos
una terminas y ponemos las siguientes lineas de comandos:
git remove add origin https://github.com/[nombreusuario]/[nombrerepositorio].git
git add .
git commit -m 'version inicial del proyecto'
