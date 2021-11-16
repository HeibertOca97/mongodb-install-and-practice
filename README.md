# Instalacion Mongodb en Linux (usando repositorio de Ubuntu)

Actualizar paquetes
```
$ sudo apt update && sudo apt upgrade -y
```

Instalar MongoDB
```
$ sudo apt install mongodb
```

Posteriormente MongoDB se inicia automáticamente despues la instalación e incluso despues de cada inicio de su Sistema Operativo (mas adelante vera como configurar esto).
Para verificar esto utilizara los siguientes comando:

Verificar estado
```
$ sudo systemctl status mongodb
```

Ejecución de MongoDB
```
$ sudo systemctl status mongodb
$ sudo systemctl stop mongodb
$ sudo systemctl start mongodb
$ sudo systemctl restart mongodb
```

Configurar si MongoDB inicia automáticamente cuando se inicia el sistema o no
```
$ sudo systemctl disable mongodb
$ sudo systemctl enable mongodb
```

Iniciar el shell de MongoDB
```
$ mongo
```

Desinstalar MongoDB
```
$ sudo systemctl stop mongodb
$ sudo apt purge mongodb
$ sudo apt autoremove
```