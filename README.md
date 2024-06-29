# Roles de reacion Automatico

## [HOST de la API y el BOT](https://github.com/IzanaonYT/Reaction-Roles-BDFD/blob/master/Config/HostTuto/ver.md)

Que el bot tenga host, no significa que lo tendra de la app "Bot Designer Bot Discord"

Tener en cuenta que el bot reaciona cuando todos los requerimiento esten disponibles, como ver canales, agregar roles (role inferiores) y permisos.

![image](https://github.com/IzanaonYT/Reaction-Roles-BDFD/assets/148601206/6b9838a8-9285-487c-8d5d-eb1f9186c347)

BDFD EJEMPLO

```python
$var[url;tu url de render o dominio  de render]

$var[cuerpo;{]
$httpPost[$var[url]/api/reaction-roles/;$var[cuerpo]]
$httpResult
```
