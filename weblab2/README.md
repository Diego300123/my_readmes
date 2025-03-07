# Gig economy

El anterior diseñador web (muy poco profesional) se ha fugado con el
tesorero de la empresa. Hay un sitio web que hay que terminar HOY y
tienes que terminarlo TÚ (no ChatGPT).

Se trata de una página tributo a Satoru Iwata presidente de Nintendo.

## Acto primero: El servidor FTP

Nuestro presidente está en Japón con el cliente y en una hora (antes
de las 20:55) accederá mediante el cliente de FTP Filezilla a la
dirección `ftpes://ftp.192.168.57.10.nip.io` con el usuario `nintendo`
y la contraseña `satoru` para subir la página web definitiva hecha
por el diseñador _Modus Ponens_.

Tienes que arreglar el servidor FTP QUE NO FUNCIONA. La configuración
está plagada de errores y omisiones. No puede entrar el usuario y no
funciona el acceso seguro.

Haz un `vagrant up` y lo ves por ti mismo.

El script de iniciación descarga un "mockup" de la página web en la
carpeta `htdocs` para que hagas pruebas de subir la página con
Filezilla a tu servidor.

... más tarde ... antes de las 20:55 ...

1. El servidor FTP conecta mediante `ftpes` y
2. podemos entrar con el usuario `nintendo` y su contraseña `satoru`.

Te sientes tan orgulloso/a de ello que se lo enseñas a ese hombre
aburrido que da vueltas por la clase. ¡Mire, este servidor FTP lo he
hecho yo! El hombre toma nota y te dice: "Si, es muy bonito. 30 puntos
para Grijandor. Sigue así"

## Acto segundo: El servidor web

Podemos haber llegado aquí de dos formas:

a) el servidor FTP funciona ó
b) el servidor FTP NO funciona

Si el servidor FTP NO funciona, tu jefe se cortará el dedo meñique y
pedirá perdón al cliente. Luego, te enviará la web por Google Drive
para que la pongas en el servidor.

Si el servidor FTP funcionaba, sólo te queda verla en el servidor web.

Pero justo antes de subirla la página, tu jefe se da cuenta de que el
servidor web no funciona, hay que arreglarlo.

Debemos acceder a `https://iwata.192.168.57.10.nip.io` y ver la web
(en nuestro caso será de nuevo el "mockup" porque no hay presupuesto
en nuestra historia para otro diseño).

Pero de nuevo no funciona nada. Tienes que arreglar el servidor web
para poder acceder a través de página segura .. antes de las 21:45.
Enseña la página web funcionando y tendrás 40 puntos más para
Grijandor.

Si eres capaz de hacer que al subir un cambio a través de FTP se
actualice la web inmediatamente, sumarás 10 puntos más.

Si los certificados son correctos, sumarás 10 puntos más.

## Acto tercero: El desenlace

Sube los ficheros de configuración necesarios para arrancar el
proyecto mediante Vagrant sin fallos a la tarea de Moodle. Si los
ficheros no tienen fallos y pueden reproducir el proyecto sin
intervención del usuario sumarás 10 puntos más.

Te has ganado el fin de semana, disfrútalo.

 
