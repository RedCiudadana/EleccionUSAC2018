# Datos

Los datos que alimentan el sitio provienen de un [Google spreadseet](https://docs.google.com/spreadsheets/d/1kO6Xp7QBmUZp1_umFsXygfNfR8QQLPMKSHuErZey41o/pubhtml).

Este spreadhseet se vuelca en archivos JSON estáticos dentro de [`public/static-files`](public/static-files)
que están a disposición para consumo.

Además de datos, estos archivos estáticos cuentan algunos parámetros de configuración de la aplicación.

### Consumo

Se recomienda consumir los archivos a través de [RawGit](https://rawgit.com), un
servicio que devuelve correctamente el `Content-Type` del contenido.

Por ejemplo, en lugar de consumir directamente el archivo [`perfil.json`](static-files/perfil.json),
este se puede consumir por medio de RawGit con [esta URL para desarrollo](https://rawgit.com/RedCiudadana/JusticiaAbiertaBeta/master/public/static-files/perfil.json)
y [esta URL para producción](https://cdn.rawgit.com/RedCiudadana/JusticiaAbiertaBeta/e4077346/public/static-files/perfil.json).

### TODO: Archivos de datos
