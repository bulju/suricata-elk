En el dockerhost, agregar parametro vm.max_map_count=262144, en /etc/sysctl.conf
Despues de modificar el archivo, correr "sysctl -p /etc/sysctl.conf/"
