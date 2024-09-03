# HACK - GIT 8 

##### VOLVER A UN COMMIT ANTERIOR.


###### - Crear un nuevo repositorio en github nombre: git_h_8

 Se Crea un repositorio local

git init

Registrar el repositorio remoto con tú repositorio local

git remote add origin (pegar_la_ruta_del_repositorio_local)

Verificamos la ruta remota

git remote -v

Crea 5 archivos notas_1.txt, notas_2.txt etc... y por cada archivo emites un commit y su push correspondiente por cada commit

nota_1.txt - commit -m "feat nota 1"
nota_2.txt - commit -m "feat nota 2"
nota_3.txt - commit -m "feat nota 3"
nota_4.txt - commit -m "feat nota 4"
nota_5.txt - commit -m "feat nota 5"
Ahora vamos a regresar del actual commit, al commit anterior, al commit pasado, mediante git revert

git revert HEAD

+ Otra alternativa al mismo resultado

git revet código_del_commit_pasado
Luego si existe un conflicto solo seleccionamos lo que necesitamos, teniendo ya todo listo, se continua con el revert
git revert --continue

git commit -m "feat volvimos al commit anterior"

para salir del editor :wq + enter
Revisamos el proyecto para confirmar y podemos seguir creando cosas en nuestro proyecto.
##  FIN.



