# Acceder a contenido NSFW en Discord si la cuenta está clasificada como menor de edad.
**Advertencia:** Este código ya no funciona correctamente. 

Antes de comenzar, hay que notar unos cuantos puntos:
- Este script está creado con propósitos de educación únicamente, el mal uso del mismo queda a responsabilidad del cliente.
- El código no es mío, solo está subido de forma informativa.
- Al ejecutarlo, Discord lanzará un mensaje de que es inseguro y que tu cuenta puede ser robada, puedes leer el código y comprobar qué hace exactamente si tienes dudas.
- Esto no roba tu cuenta, es código abierto precisamente para que puedas analizar lo que estás ejecutando: y si sabes un poco, puedes ver que es completamente limpio.

# ¿Cómo usar el código?
Debes tener Discord Canary, Discord PTB o Discord Developement para que esto funcione. 

Para hacerlo funcionar hay que saber usar el menú de desarrollador (se abre con Control + Shift + I), y abrirlo en la pestaña de _Consola_ para copiar y ejecutarlo en el canal que queráis desbloquear. 

Menú de desarrollador y la consola señalada con una flecha:
![](https://cdn.discordapp.com/attachments/995109332289065041/1139016985448030258/image.png)
Texto a copiar y pegar ahí: 
```js
var findModule=a=>window.webpackChunkdiscord_app.push([[Math.random()],{},b=>{for(const c of Object.keys(b.c).map(a=>b.c[a].exports).filter(a=>a))if(c.default&&c.default[a]!==void 0)return c.default}]);findModule("getCurrentUser").getCurrentUser().nsfwAllowed=!0;```
