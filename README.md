php server
==========

Servidor php para trabajar con pequeños proyectos (creado con gulp y browsersync)

# contenido

## Pre-requisitos

* Tener instalado php en tu equipo
* Nodejs y npm

## Configuracion

### Error watch ENOSPC [linux]

Si al momento de encender el servidor te sale el error "watch ENOSPC" en consola. Puedes solucionarlo con ejecutando el siguiente comando.-

```
echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p
```

## Encender el servidor

Para poner en marcha el servidor, abre la teminal y ubicate en el directorio principal del proyecto y ejecuta el siguiente comando.-

```
npm run dev
```

## Errores y aclaraciones sobre el código

Si encuentras algun error en el código o la forma de optimizarlo puedes informarme en el siguiente enlace para realizar las correcciones correspondientes.-

[Reportar errores](https://github.com/nemesis866/php-server/issues)
