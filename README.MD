# Tutorial de Git
Bienvenidos a nuestra guia git.
```
Git Reference
```
Es un archivo que contiene un hash SHA-1 de una confirmación de Git. Al hacer referencia a una confirmación de Git, puede usar la referencia de Git, que es un nombre fácil de recordar, en lugar del hash.
```
git config (user.name, user.email)
```
Es una función util que sirve para definir valores de configuración git. Al ejecutar git config , se modificará un archivo de texto de configuración.

```
git commit
```
El comando git commit captura una instantánea de los cambios preparados en ese momento del proyecto. Las instantáneas confirmadas pueden considerarse como versiones "seguras" de un proyecto: Git no las cambiará nunca a no ser que se lo pidas expresamente.

```
git branch (-f)
```
El comando git branch te permite crear, enumerar y eliminar ramas, así como cambiar su nombre. No te permite cambiar entre ramas o volver a unir un historial bifurcado. Por este motivo, git branch está estrechamente integrado con los comandos git checkout y git merge .
merg
```
git checkout (-b)
```
El comando git checkout te permite desplazarte entre las ramas creadas por git branch . Al extraer una rama, se actualizan los archivos en el directorio de trabajo para reflejar la versión almacenada en esa rama y se indica a Git que registre todas las confirmaciones nuevas en dicha rama.

```
 Git Merge
```
La fusión es la forma que tiene Git de volver a unir un historial bifurcado. El comando git merge permite tomar las líneas independientes de desarrollo creadas por git branch e integrarlas en una sola rama. Ten en cuenta que todos los comandos presentados a continuación se fusionan en la rama actual.

```
Git rebase
```
Comando de la plataforma de Git enfocado en integrar modificaciones de una rama a otra, a través de reorganizar o cambiar la base de una rama de commit a otra. Esto deriva en que parezca que se ha creado la rama desde un commit diferente.

```
Git cherry-pick
```
Es un potente comando que permite que las confirmaciones arbitrarias de Git se elijan por referencia y se añadan al actual HEAD de trabajo


```
Git switch
```
Lo podemos utilizar, para cambiar entre ramas y poder crearlas si no existen. Con el argumento -c (crear) git creará la nueva rama y cambiará a ella.

```
Git tag
```
Sirve básicamente como una rama firmada que no permuta, es decir, siempre se mantiene inalterable.

```
Git bisect
```
Es un algoritmo de búsqueda sencillo de utilizar que nos permite escanear historiales de código bastante largos en un tiempo razonablemente breve y además no es invasivo.
