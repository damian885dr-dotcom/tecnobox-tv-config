# TecnoBox Tv remote config

Subi estos archivos a un repositorio publico llamado:

`tecnobox-tv-config`

En GitHub, activa Pages desde:

Settings > Pages > Deploy from a branch > main > root

La app compilada busca el config en:

`https://damian885dr-dotcom.github.io/tecnobox-tv-config/config.json`

Para reparar o cambiar canales sin reinstalar la APK:

1. Edita `channels.json`.
2. Sube el cambio a GitHub.
3. En la app toca `Actualizar lista`.

Si queres poner la app en mantenimiento, cambia en `config.json`:

```json
"maintenance": true,
"message": "Estamos reparando la lista de canales."
```
