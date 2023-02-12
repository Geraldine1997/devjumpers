Cree mi REPOSITORIO "DEVJUMPERS" en GITHUB
  
Clone mi repositorio:     
$ git clone https://github.com/Geraldine1997/devjumpers.git   

Ingrese al main del repositorio:    
$ cd devjumpers  

**README**   
Cree el archivo README:  
$ touch README.md     

**COMMIT INICIAL**      
para agregar el proyecto a la nube con el commit inicial:      
$ git add .     
$ git commit -m "commit inicial"   

**PUSH INICIAL**    
mi primer push:
$ git push   

**IGNORAR ARCHIVO**  
creacion del archivo .gitignore:    
$ touch .gitignore

creacion de archivo .txt:   
$touch privado.txt

creacion de carpeta:   
$ mkdir privada   
$ git status  
$ git add .   

**AÑADIR FICHERO 1.txt**   
$touch 1.txt  
$ git add .
$ git commit -m ".gitignore y creacion de archivo 1.txt"      
$ git push      

**CREAR UNA RAMA v0.2**   
$ git branch v0.2

Posicioné mi carpeta de trabajo en esta rama.:   
$ git checkout v0.2

**AÑADO EL FICHERO 1.txt**     
$ touch 1.txt    
$ touch 2.txt   

subo los cambios al repositorio remoto:   
$ git add .    
$ git commit -m "creacion de archico 1.txt y 2.txt"        
 
**MERGE DIRECTO**    
me posiciono en la rama "main":   
$ git checkout main

hago un merge de la rama v0.2 en la rama "main":   
$ git merge v0.2

**MERGE CONFLICTO**   
en la rama main modifico el archivo 1.txt y hago un commit:    
$ echo "hola" >1.txt    
$ git add .    
$ git commit -m "modificacion del archivo 1.txt"

me posiciono en la rama v0.2, cambio el archivo 1.txt y hago un commit:    
$ git checkout v0.2   
$ echo "adios" >1.txt  
$ git add .    
$ git commit -m "modificacion en 1.txt"      

me vuelvo a posicionar en la rama main y hago un merge con la rama v0.2:        
$ git checkout main      
$ git merge v0.2    
me aparece un CONFLICTO:    
Auto-merging 1.txt   
CONFLICT (content): Merge conflict in 1.txt   
Automatic merge failed; fix conflicts and then commit the result.   

**INVESTIGACION Y APLICACION DE LOS COMANDOS  --merged Y --no-merged:** 
$ git branch --merged    
  *main     
$ git branch --no-merged    
  v0.2    

**SOLUCION DE CONFLICTO**   
-abro el Visual Studio Code eliminando manualmente el conflicto.       
$ git add .    
$ git commit -m "conflicto solucionado"      

**BORRO RAMA v0.2:**   
$ git branch -d v0.2   

**LISTADO DE CAMBIO**

$ git log --oneline --decorate --all --graph   
*   fa6f299 (HEAD -> main) conflicto solucionado    
|\    
| * 3a6efc8 modificacion en 1.txt     
| * 6f7ddb2 creacion de archico 1.txt y 2.txt    
* | 05e613f agrego texto en 1.txt    
|/   
* 603e6fe (origin/main) .gitignore y creacion de archivo 1.txt     
* 16ac070 commit inicial      
   
**FINALIZANDO**   
$ git add .       
$ git commit -m "trabajo terminado"    
$ git push     



<table>
<thead>
<tr>
<th>Nombre</th>
<th>Github</th>
</tr>
</thead>
<tbody>
<tr>
<td>Armando Torres Quintana</td>
<td><a href="https://github.com/ArmaTQ?tab=stars">ArmaTQ</a></td>
</tr>
<tr>
<td>Camila Rios</td>
<td><a href="https://github.com/camilarios01?tab=stars">camilarios01</a></td>
</tr>
<tr>
<td>Iván de la Parte</td>
<td><a href="https://github.com/ivandelaparte?tab=stars">ivandelaparte</a></td>
</tr>
<tr>
<td>Maria Arteaga</td>
<td><a href="https://github.com/maryjse?tab=stars">maryjse</a></td>
</tr>
<tr>
<td>Damian Coronel</td>
<td><a href="https://github.com/Damsh-bit?tab=stars">Damsh-bit</a></td>
</tr>
</tbody>
</table>




