# ansible-playbooks

## Requerimientos para correr los playbooks:

* Sustituir el archivo id_rsa.pem por una clave privada valida con la cual acceder a las maquinas.
* Sustituir las IP en el archivo "hosts" con las de nuestras maquinas, deben aceptar la clave privada anterior.
* Sustituir las variables del archivo "vars.json" con nuestras credenciales y otras variables necesarias.
* Correr los playbooks con el siguiente comando:

``` ansible-playbook ./playbooks/node_provision_and_deploy.yml -e "@vars.json" ```
