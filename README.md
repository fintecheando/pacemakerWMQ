# pacemakerWMQ

Es requerido tener instalado el Software de IBM WMQ 9.2 en RHELv8 y el IBM WMQ Manager debe estar configurado en Multi instancia.

1. Instalar Scripts de PaceMaker para el Agente de IBM WMQ
```console
# ./installHAScripts_MQ
```
2. Crear un agente de Cluster de IBM WMQ para un Administrador de Colas
```console
# ./createHAResource_QM NOMBRE_WMQ_MANAGER
```
3. Eliminar un agente de Cluster de IBM WMQ para un Administrador de Colas
```console
# ./deleteHAResource_QM NOMBRE_WMQ_MANAGER
```
