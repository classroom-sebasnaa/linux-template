# Enunciados de Ejercicios

## 1. Crear y Exportar una Variable

Vamos a crear una variable local llamada `gato` y exportarla.

Sigue estos pasos:

1. Crea una variable local llamada `gato` y asígnale el valor que quieras.
2. Muestra su valor por pantalla con el comando `echo`.
3. Mira si es una variable de entorno con el comando `env`.
4. Expórtala con `export`.
5. Comprueba de nuevo si es una variable de entorno.
6. Borra la variable.

## 2. Comprobar tu SHELL y Ver Shells Disponibles

Comprueba tu SHELL actual y luego verifica qué shells están disponibles en el sistema.

## 3. Variables de Entorno Más Usadas

Averigua qué contienen las siguientes variables de entorno más usadas:

- `HOME`
- `USER`
- `SHELL`
- `HOSTNAME`
- `TERM`
- `LOGNAME`
- `PATH`
- `PWD`
- `OLDPWD`
- `PS1`
- `PS2`

## 4. Encontrar Errores en Scripts

Encuentra los errores que hay en los siguientes scripts:

```bash
minombre=Alfonso
miapellido = Sanz
miedad=41
echo "Mi nombre es $minombre"
echo "Mi apellido es $miapellido"
echo "Mi edad es miedad"
```

## 5. Cambiar el valor de la variable PATH

Cambiar el valor de la variable PATH para que incluya nuestro directorio personal.

## 6. Modificar Archivos de Configuración de Shell

Modificar el archivo `/home/user/.bash_profile` o el `.profile` (`.profile` se ejecuta si no hay `.bash_profile`) para añadir la ruta de nuestros scripts.

## 7. Cambiar el Prompt

Cambiar el prompt para que muestre la fecha, nombre de usuario y la carpeta actual. 
Nota: Si se cambia en el `$HOME/.bashrc` se hará permanente.

## 8. Crear un Shell Script

Crear un shell script que:

- Borre la pantalla
- Diga “Hola, nombre de usuario. La fecha actual es: .”
- Indique que estás en el “directorio actual”

## 9. Hacer que el Script se Ejecute Siempre al Iniciar Sesión

Hacer que el script anterior se ejecute siempre cuando hagamos login con nuestro usuario.

## 10. Crear un Shell Script Informativo

Crear un shell script que:

- Diga su nombre
- Indique con cuántos parámetros lo han llamado
- Muestre todos los parámetros
- Muestre el PID del proceso

## 11. Realizar un Script Informativo

Realizar un script que muestre:

- El nombre del script
- El número de parámetros que se le pasan
- Una lista con los parámetros recibidos
- El identificador del usuario que ejecuta el script
- El nombre de usuario
- El directorio home del usuario
- El directorio actual

## 21. División y Almacenamiento de Resultado

Realizar un script que defina dos variables, `a=20` y `b=5`. Muestra el resultado de la división de `a` entre `b` por pantalla. Después, guarda el resultado en una variable llamada `resultado`.

## 22. Cálculo de Índice de Masa Corporal (IMC)

Realizar un script que solicite al usuario por teclado su peso y su estatura y muestre la siguiente salida por pantalla (respetando los saltos de línea y las tabulaciones):


## 23. Extracción de Subcadenas

Extraer subcadenas en un script. Dada la cadena `abcdeABCDE1234567`, extraer diferentes subcadenas.

## 24. Búsqueda de Palabra en Archivos

¿En qué ficheros aparece la palabra `FILE`? (En mayúscula o minúscula).

## 25. Filtrado de Procesos de Usuario

Script que filtra los procesos de un usuario.

## 26. Uso de Grep en /etc/passwd

Uso de `grep`, trabajando con el fichero `/etc/passwd`.

a) Mostrar la línea correspondiente a la cuenta `man`.
b) Mostrar las cuentas que empiecen por `a`.
c) Mostrar las cuentas que empiecen por `a` o `r`.
d) Mostrar las cuentas que terminen por `c`.
e) Mostrar las cuentas que usen `bash` como intérprete de comandos.
f) Mostrar las cuentas que NO usen `bash` como intérprete de comandos.
g) Mostrar las cuentas que no empiecen por vocal.
h) Mostrar las cuentas que empiecen por mayúscula.
i) Mostrar las líneas cuyo tercer campo tenga una sola cifra.
j) Mostrar las líneas que tengan cifras de 3 a 5 dígitos.
k) Mostrar las líneas que tengan cifras de 3 dígitos en el cuarto campo.
l) Mostrar las cuentas `root` o de `ftp`.
m) ¿Qué ficheros de cabecera usan la constante `MAXDOUBLE`?
n) ¿En qué ficheros aparece la palabra `bash`? (En mayúscula o minúscula).


## 27. Uso de sort

Uso de `sort`:

1. Ordenar el fichero `/etc/passwd` por orden alfabético.
2. Ordenarlo en sentido inverso.
3. Ordenarlo ignorando mayúsculas.
4. Ordenarlo según el tercer campo.
5. Ordenarlo según el tercer campo en orden numérico.
6. Ordenarlo según el cuarto campo en orden numérico y eliminando repeticiones.

## 28. Uso de Arrays

Uso de arrays:

- Crea un menú empleando arrays. En cada posición del array introduce un plato (ej. Espaguetis; melón con jamón… etc.). Emplea 4 platos diferentes.
- Modifica un plato (ej. El plato n1 2 por otro diferente).
- Añade un 5º plato al array.
- Muestra todo el menú del día con una orden (todos los elementos del array).

## 29. Generación de Frase Aleatoria

Script que genera una frase aleatoria para una galleta de la fortuna. Debes crear un array de 10 elementos, donde cada frase es uno de los elementos. Después, con `RANDOM`, selecciona aleatoriamente una de las frases.

## 30. Creación y Modificación de Usuarios y Grupos

Script que realiza lo siguiente:

- Crear un usuario con el ID 999 y el nombre `navin`.
- Crear el grupo `oficina1`.
- Cambiarle el nombre a `oficina2`.
- Crear el usuario `sonia` en `oficina2`.
