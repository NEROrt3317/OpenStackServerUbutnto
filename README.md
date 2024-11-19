# OpenStackServerUbutnto
Proyecto de openstack con ubuntto server

# instalacion del servicio openstack
```
sudo snap install microstack --beta
```
```
snap list microstack 
```
```
sudo microstack init --auto --control 
```
# mostrar las maquinas virtuales 
```
microstack.openstack flavor list
```
# crear maquina 
```
microstack launch cirros -n virtua
```
# configurar el password para poder conectarnos al administrador web 
```
sudo snap get microstack config.credentials.keystone-password
```
# acceso de configuracion de openstack 
```
https://localhost:443
```
_NOTA_: Recuerde abrir los puerto en el virtualbox de los comandos que vaya abriendo por cada maquina virtual 

