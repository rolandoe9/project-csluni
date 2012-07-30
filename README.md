project-csluni
==============

1. creamos una cuenta gratuita en https://githup.com
2. creamos un repositorio
3. descargamos consola de github http://git-scm.com/downloads/
4. descargamos el contenido de un proyecto : clone git https://github.com/Mejorandola/curso-responsive-design.git
5. conectar mi pc a github
6. git config --global user .name 'rolando'
7. git config --global user .email 'rolandoe9@gmail.com'
8. generamos un llave ssh : ssh-keygen
9. llave creada en : /c/user/alfredo/.ssh
10. id creada en : /c/user/alfredo/.ssh/id_rsa.pub
11. cat ~/.ssh/id_rsa.pub
12. copiamos la llave ssh generada en nuestra cuenta de github
13. creamos una carpeta : mkdir proyecto-csluni-github
14. iniciamos un repositorio en esta carpeta : git init
15. creamos un archivo : touch README2
16. agregamos el archivo a nuestro repositorio: git add README2
17. revisamos el status de nuestro repositorio : git status
18. envio al repositorio cuando hacemos un cambio: git commit -m 'este es mi primer archivo desde mi computadora'
19. tenemos dos repositorios uno en githup y el otro en local
    *git pull origin master : con esto nos traemos todo el contenido 
    del repositorio en githup a nuestro repositorio en local
    *git push origin master : con esto enviamos nuestros archivos al repositorio de githup
