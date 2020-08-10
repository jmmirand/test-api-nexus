# Test API nexus

## Objetivo

Generar librería y metodos Nexus compartidas desde un repositorio Github.

## Modo de Uso

Generamos metodos nexus en groovy en la carpeta /nexus/v1

Generamos versión del repositorio Github.

Primer paso cagar los métodos a utilizar en nuestra instancia Nexus, desde la versión Github generada

Una vez cargados los métodos ya están disponibles para ser utilizados.

## Ejemplo de uso desde Ansible.

Ejemplo en la carpeta ansible hay un ejemplo en ansible para utilizar la versión 0.0.1 de la librería y ejecutar el método hello-world

```
 ansible git:(master) ✗ ansible-playbook execute-groovy.yml
```
