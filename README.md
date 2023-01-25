# practicidad
volvemos a empezar

# Curso_practico

aca vamos a colocar lo resumido de la clase para Git & GitHub, asi que; comencemos.

para subir un nuevo repositorio 

1) colocar nombre al nuevo repositorio con una leve descripción, ademas colocar si es publico o privado

2)debemos conectar el repositorio con:

    #git remote add origin (osea al repositorio en Git y conectarlo a GitHub)

    #git branch -M main con esta rama 

    #git push -u origin main para finalizar 

3) si es desde cero se debe seguir las siguientes instrucciones que se hacen desde la consola ya sea desde VSC o de la pc.

    #git init (es para inicializar el repositorio en local )

    #ls es para ver las carpetas que estan "recuerda el cd ../ (atras) o cd "name_folder" para entrar

    #crear un .gitignore con el nombre de los archivos que son inicesarios o desde el mismo GitHub podemos lograr con la opcion de ocultar los arcihvos inecesarios mediante www.gitignore.io

    #git add .gitignore para agregar ese archivo y las modificaciones 

    #git status para mostrar los archivos incluidos

    #git add -A para agregar todos los archivos

    #git commit -m "agregar un mensaje de confirmación"

    #git branch -M main para cambiar la rama

    #git remote add origin ... url ...

    #git push origin main es para tener un origen del push sin el -u porque ya tiene origen definido, si no usamos el -u para mirar los origenes definidos

y ya, pasa todos los archivos al repositorio en GitHub para hacer los correspondientes 

# vamos ahora a crear un proyecto desde cero 

Se crea un nuevo proyecto o repositorio desde GitHub con nombre o caracteristicas diferentes, crear el README por defecto y un template por defecto y la licencia MIT license y luego clonarla para con el editor de codigo

1) se copia la URL y desde la terminal se abre la carpeta donde quiere copiar el repositorio y en el VSC se entra a  la carpeta donde esta creando los archivos con el comando cd y si tiene espacios usar las "nombre de carpeta" 

2) git clone ... URL de repositorio ...

3) cd "nombre del prpyecto" y ls para ver los archivos

4) code ./ -r (quiero utilizar el comando par aagregar un proyecto del sistema operativo al editor y no arranque otra ventana y reutilice la que estamos trabajando )

# en la carpeta gitignore se agregan los archivos que se quieres omitir

5) se usa el git add ".... nombre de carpeta ..." siempre que se haga un cambio se deben agregar los archivos siempre   con " git add -A " o de manera especifica con " git add "..nombre.."
