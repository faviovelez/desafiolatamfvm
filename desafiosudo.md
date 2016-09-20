$ sudo touch archivo.txt
[sudo] password for favio:
$ ls -la archivo.txt
-rw-r--r-- 1 root root 0 sep 16 15:31 archivo.txt
$ chmod 222 archivo.txt
chmod: cambiando los permisos de 'archivo.txt': Operación no permitida
$ chown favio:adm archivo.txt
chown: cambiando el propietario de 'archivo.txt': Operación no permitida
$ ls -la archivo.txt
-rw-r--r-- 1 root root 0 sep 16 15:31 archivo.txt
$ chmod 600 archivo.txt
chmod: cambiando los permisos de 'archivo.txt': Operación no permitida
$ sudo chwon favio:adm archivo.txt
$ ls -la archivo.txt
-rw-r--r-- 1 favio adm 0 sep 16 15:31 archivo.txt
$ rm archivo.txt

