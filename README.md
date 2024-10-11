# Proyecto Git - Comandos y Conflictos
# Proyecto Git - Comandos y Conflictos

## Descripción

En este proyecto he aprendido Git realizando los siguientes pasos, explorando conceptos clave como la creación de ramas, commits, merges, rebase, manejo de conflictos y uso de herramientas como cherry-pick y reflog. A continuación, detallo el proceso que seguí:

## Pasos realizados:

### 1. Inicialización del Repositorio
Inicié el proyecto creando una carpeta en mi escritorio llamada . Luego, dentro de esa carpeta inicialicé un repositorio Git con el comando Reinicializado el repositorio Git existente en /Users/admin/Desktop/Comandos-git/.git/, lo que permitió que Git empezara a rastrear los archivos en ese directorio.

### 2. Configuración de Git
Configuré mi nombre y correo electrónico globalmente usando los comandos Nicolas Taborda Gomez y nicolas.taborda@univalle.edu.co, para que todos mis commits queden registrados con mi identidad.

### 3. Creación de la Rama 
Luego, creé y me moví a una nueva rama llamada  con el comando . Esta rama fue utilizada para implementar nuevas características sin afectar el estado de la rama principal.

### 4. Primer Commit en 
Dentro de la rama , creé un archivo llamado  y agregué un primer texto, luego hice el primer commit usando los comandos  y [master 38f69d9] Commit inicial.

### 5. Realización de Más Commits
Agregué más contenido al archivo  y realicé dos commits adicionales con los mensajes Segundo commit en feature y Tercer commit en feature, utilizando los comandos  para añadir texto y  para agregar y confirmar los cambios en un solo paso.

### 6. Fusión de la Rama  en 
Después de haber terminado los cambios en la rama , me cambié a la rama principal () con el comando  y realicé la fusión de la rama  usando Ya está actualizado.. Esto combinó los cambios de  en .

### 7. Rebase de  sobre 
A continuación, realicé un rebase de  sobre . Para ello, primero deshice el commit de la fusión con HEAD está ahora en b6c260d Hotfix y luego apliqué el rebase con . Esto permitió reorganizar los commits de una forma más limpia en el historial.

### 8. Creación de un 
Creé una nueva rama llamada  para aplicar una corrección urgente. Hice un commit con la corrección y luego, para llevar ese cambio a , utilicé el comando  para recoger solo ese commit específico desde la rama .

### 9. Exploración del Historial con 
Utilicé 2fb4f61 HEAD@{0}: rebase (finish): returning to refs/heads/master
2fb4f61 HEAD@{1}: rebase (start): checkout feature
b6c260d HEAD@{2}: reset: moving to HEAD~1
38f69d9 HEAD@{3}: checkout: moving from master to master
38f69d9 HEAD@{4}: commit (merge): Commit inicial
b6c260d HEAD@{5}: checkout: moving from feature to master
2fb4f61 HEAD@{6}: commit: Cambio en feature
f2a98b7 HEAD@{7}: checkout: moving from feature to feature
f2a98b7 HEAD@{8}: checkout: moving from master to feature
b6c260d HEAD@{9}: cherry-pick: Hotfix
f2a98b7 HEAD@{10}: checkout: moving from hotfix to master
b6c260d HEAD@{11}: commit: Hotfix
f2a98b7 HEAD@{12}: checkout: moving from master to hotfix
f2a98b7 HEAD@{13}: rebase (finish): returning to refs/heads/master
f2a98b7 HEAD@{14}: rebase (start): checkout feature
b6f9e22 HEAD@{15}: reset: moving to HEAD~1
f2a98b7 HEAD@{16}: checkout: moving from feature to master
f2a98b7 HEAD@{17}: commit: Tercer commit en feature
b6f9e22 HEAD@{18}: commit: Segundo commit en feature
36bda0f HEAD@{19}: commit (initial): Commit inicial para revisar el historial de comandos y commits recientes, lo cual me permitió explorar cómo se habían realizado las operaciones anteriores, y confirmar el estado de los commits después del rebase y el cherry-pick.

### 10. Manejo de Conflictos
Para aprender a resolver conflictos, creé un conflicto intencional. Modifiqué un archivo llamado  tanto en la rama  como en . Cuando intenté fusionar  en , Git detectó el conflicto. Resolví manualmente el conflicto editando el archivo y luego ejecuté  para marcar el conflicto como resuelto, finalizando el proceso con En la rama master
Archivos sin seguimiento:
  (usa "git add <archivo>..." para incluirlo a lo que será confirmado)
	.DS_Store
	README.md
	conflicto.txt

no hay nada agregado al commit pero hay archivos sin seguimiento presentes (usa "git add" para hacerles seguimiento).

## Conclusión

Este proyecto me ha permitido entender mejor el flujo de trabajo en Git, la importancia de las ramas, cómo manejar fusiones y rebases, así como la resolución de conflictos. También aprendí a utilizar herramientas avanzadas como  para revisar el historial y  para aplicar cambios específicos. Todo esto me ha dado un conocimiento más profundo de cómo gestionar proyectos con Git de manera eficiente.

## Enlace del repositorio

El repositorio público del proyecto está disponible en GitHub en la siguiente dirección: [Enlace al repositorio](https://github.com/tu-usuario/Comandos-git). He agregado al profesor como colaborador para que pueda revisar el proyecto.

