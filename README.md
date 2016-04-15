# Chat con php ratchet websockets

## Instalación
	Instalar los paquetes de composer con `composer install`.

## Ejecutar
	Abrir tres terminales, una para el servidor y dos para los clientes del
chat:
```shell
# Terminal 1
$ php bin/chat-server.php

# Terminal 2
$ telnet localhost 8080

# Terminal 3
$ telnet localhost 8080
```

