# Proxy, instalando la funcion en tu .bashrc
1 agregar las funciones en tu ~/.bashrc

2 ejecuta > $ source ~/.bashrc

3 para usar el proxy con sudo, edita > /etc/sudoers

Busca La Linea

> Defaults env_reset

Agrega esta linea justo debajo

> Defaults env_keep += "no_proxy ftp_proxy http_proxy https_proxy"

# Como usar?
cualquiera de las dos formas puedes usar

> $ proxy-on

> Server: [ip server] 

> Port: [port number]

> $ proxy-on [server ip]:[port number]

# como quitar el proxy
> proxy-off
