## Tarea 4.11. Practica4. Git. Resolviendo un conflicto

1. Asegúrate de que tienes configurado el editor Visual Studio Code como tu editor de Git. (git config --global core.editor "code --wait")
2. Crea un repositorio local y avanza en la rama "master" añadiendo un fichero "index.html" con la estructura básica html. El body estará vacío
3. Crea y salta a "rama-1". Avanza en un commit con tu nombre de pila en un párrafo dentro del body
4. Vuelve a la rama master
5. Crea y salta a "rama-2". Avanza en un commit con tu apellido en un párrafo dentro del body
6. Muestra el estado del repositorio de forma gráfica y resumida  
    ![Captura1](img/Captura1.JPG)
7. Haz un merge a rama-1. Intentas fusionar ambas ramas. Aparecerá un conflicto porque ambos commits trabajan en la misma porción <body></body> de un mismo archivo index.html. Git no será capaz de fusionarlas directamente. 
8. El editor VS Code reconoce los conflictos de fusión. Las diferencias se resaltan y hay acciones en línea para aceptar los cambios. Deja un único párrafo con tu nombre de pila y apellido.
    ![Captura2](img/Captura2.JPG)
9. Una vez que se resuelto el conflicto confirma el archivo en conflicto para que pueda realizar esos cambios  
10. Muestra de nuevo el estado del repositorio de forma gráfica y resumida  
    ![Captura3](img/Captura3.JPG)
11. Vuelve a la rama master y realiza otro merge. Es una fusión fast-forward. Los dos commits a fusionar tienen relación de ancestro. Entonces el merge no produce un commit nuevo, sencillamente avanza la rama, "avance rápido"
12. Visualiza las ramas que han sido fusionadas con la rama master  
    ![Captura4](img/Captura4.JPG)
13. Elimina las ramas correctamente fusionadas (sin asterisco) para quedarte SOLO con la rama master. 
    ![Captura5](img/Captura5.JPG)
14. Realiza una copia a este repositorio remoto
15. Recuerda añadir estas instrucciones con los pantallazos en el fichero README.md
16. En GitHub entra en Insights/network y visualiza el gráfico del repositorio con los merge y cinco commits  
    ![Captura6](img/Captura6.JPG)  
    ![Captura7](img/Captura7.JPG)